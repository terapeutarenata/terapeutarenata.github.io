---
layout: default
title: "Contato"
description: "Fale com {{ site.therapist_name }} pelo WhatsApp ou e-mail para agendar sua consulta de homeopatia e florais de Bach."
permalink: /contato/
---

<section class="page-hero">
  <div class="container hero-grid">
    <div>
      <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Contato</p>
      <span class="eyebrow">Fale comigo</span>
      <h1>Vamos conversar</h1>
      <p class="lede">
        A forma mais rápida de agendar ou tirar dúvidas é pelo WhatsApp. Também respondo por e-mail,
        geralmente em até um dia útil.
      </p>
    </div>
    <div class="media-frame" style="max-width:320px; justify-self:end;">
      <img src="{{ '/assets/images/contato.jpg' | relative_url }}" alt="Ilustração 'Contato': envelope entre flores, com ícones de e-mail, WhatsApp e Instagram">
    </div>
  </div>
</section>

<section>
  <div class="container">
    <div class="grid-3">
      <div class="card">
        <h3>WhatsApp</h3>
        <p>{{ site.whatsapp_display }}</p>
        <p><a class="btn btn-whatsapp" style="margin-top:8px;" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Chamar agora</a></p>
      </div>
      <div class="container">
    <div class="grid-3">
      <div class="card">
        <h3>Horário de atendimento</h3>
        <p>{{ site.office_hours }}</p>
        <p>{{ site.city_state }}</p>
       </div>

    {% include sprig.html %}

    <div class="prose">
      <h2>Antes de escrever</h2>
      <p>Para agilizar o primeiro contato, se possível já informe:</p>
      <ul>
        <li>Se você busca homeopatia, florais de Bach, ou ambos.</li>
        <li>Se é para você ou para outra pessoa (e a idade, no caso de crianças).</li>
        <li>Um breve resumo do que te trouxe até aqui.</li>
      </ul>
      <p>
        Veja também as <a href="{{ '/faq/' | relative_url }}">perguntas frequentes</a> e a página de
        <a href="{{ '/valores/' | relative_url }}">valores</a> antes de agendar.
      </p>
    </div>
  </div>
</section>
