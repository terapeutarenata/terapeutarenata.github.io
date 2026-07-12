---
layout: default
title: "Perguntas Frequentes"
description: "40 perguntas frequentes sobre homeopatia e florais de Bach: segurança, crianças, gestantes, tratamento junto com remédios, tempo de resposta e mais."
permalink: /faq/
---

<section class="page-hero">
  <div class="container">
    <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Perguntas frequentes</p>
    <span class="eyebrow">Tire suas dúvidas</span>
    <h1>Perguntas frequentes</h1>
    <p class="lede">
      Reunimos aqui as dúvidas mais comuns sobre homeopatia, florais de Bach e o funcionamento das
      consultas. Não encontrou sua pergunta? Mande uma mensagem no WhatsApp.
    </p>
  </div>
</section>

<section>
  <div class="container">

    <nav class="faq-nav" aria-label="Categorias de perguntas">
      {% for group in site.data.faq %}
        <a href="#{{ group.slug }}">{{ group.category }}</a>
      {% endfor %}
    </nav>

    {% assign qn = 0 %}
    {% for group in site.data.faq %}
      <h2 id="{{ group.slug }}">{{ group.category }}</h2>
      <div class="faq-list" style="margin-bottom:36px;">
        {% for item in group.items %}
          {% assign qn = qn | plus: 1 %}
          <details class="faq-item">
            <summary>
              <span><span class="q-num">{{ qn }}</span>{{ item.q }}</span>
              <span class="icon">+</span>
            </summary>
            <div class="faq-answer">{{ item.a }}</div>
          </details>
        {% endfor %}
      </div>
    {% endfor %}

    {% include sprig.html %}

    <div class="cta-band">
      <div>
        <h2>Ainda tem dúvidas?</h2>
        <p>Mande sua pergunta direto no WhatsApp — respondo pessoalmente.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Falar no WhatsApp</a>
    </div>
  </div>
</section>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {% for group in site.data.faq %}
      {% for item in group.items %}
        {
          "@type": "Question",
          "name": {{ item.q | jsonify }},
          "acceptedAnswer": {
            "@type": "Answer",
            "text": {{ item.a | jsonify }}
          }
        }{% unless forloop.last and forloop.parentloop.last %},{% endunless %}
      {% endfor %}
    {% endfor %}
  ]
}
</script>
