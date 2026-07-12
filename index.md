---
layout: default
title: "Homeopatia e Florais de Bach Online"
description: "Consultas online de homeopatia hahnemanniana clássica e florais de Bach, com {{ site.therapist_name }}. Atendimento individualizado por videochamada para todo o Brasil."
permalink: /
---

<section class="hero">
  <div class="container hero-grid">
    <div>
      {% include sprig.html %}
      <span class="eyebrow">Homeopatia clássica &amp; Florais de Bach · Atendimento 100% online</span>
      <h1>Um cuidado que investiga a raiz, não só o sintoma.</h1>
      <p class="lede">
        Sou {{ site.therapist_name }}, {{ site.credentials | downcase }}. Atendo por videochamada
        pessoas que já passaram por muitos consultórios, exames e tratamentos e ainda sentem que
        falta algo — um olhar que enxergue a pessoa inteira, não apenas o diagnóstico.
      </p>

      <div class="hero-tags">
        <span class="tag">Homeopatia hahnemanniana tradicional</span>
        <span class="tag">Florais de Bach</span>
        <span class="tag">Consulta por vídeo</span>
        <span class="tag">{{ site.city_state }}</span>
      </div>

      <div class="hero-actions">
        <a class="btn btn-whatsapp" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">
          Agendar pelo WhatsApp
        </a>
        <a class="btn btn-ghost" href="{{ '/como-funciona-a-consulta/' | relative_url }}">Como funciona a consulta</a>
      </div>
    </div>

    <div>
      <div class="media-frame">
        <img src="{{ '/assets/images/home-hero-banner.jpg' | relative_url }}" alt="Banner ilustrativo: Equilíbrio que floresce de dentro — terapias naturais para corpo, mente e emoções, com frascos de glóbulos homeopáticos, floral e flores silvestres">
      </div>
      <div class="hero-card">
      <h3>Em poucas palavras</h3>
      <ul>
        <li><strong>O que faço:</strong> avaliação individualizada e acompanhamento em homeopatia e florais de Bach.</li>
        <li><strong>Para quem:</strong> adultos, crianças, gestantes e idosos que buscam um cuidado complementar.</li>
        <li><strong>Onde:</strong> qualquer lugar do Brasil, por videochamada.</li>
        <li><strong>Como começar:</strong> uma mensagem no WhatsApp já dá início ao agendamento.</li>
      </ul>
      </div>
    </div>
  </div>
</section>

<section>
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">O que eu faço</span>
      <h2>Duas abordagens, um mesmo cuidado: olhar a pessoa como um todo.</h2>
      <p>
        Homeopatia e florais de Bach são sistemas terapêuticos diferentes, mas partem do mesmo princípio:
        sintomas físicos e emocionais fazem parte de uma mesma história, e tratá-los separadamente raramente
        resolve o que está na origem.
      </p>
    </div>

    <div class="grid-2">
      <div class="card">
        <h3>Homeopatia</h3>
        <p>
          Consulta detalhada, escolha individualizada do medicamento homeopático e acompanhamento da
          resposta do organismo ao longo do tempo, seguindo os princípios clássicos descritos por Hahnemann.
        </p>
        <p><a href="{{ '/homeopatia/' | relative_url }}">Entender como funciona a homeopatia →</a></p>
      </div>
      <div class="card">
        <h3>Florais de Bach</h3>
        <p>
          Trinta e oito florais que atuam sobre estados emocionais como medo, insegurança, exaustão ou
          dificuldade de adaptação — sempre combinados a partir de uma escuta cuidadosa, e não de fórmulas prontas.
        </p>
        <p><a href="{{ '/florais-de-bach/' | relative_url }}">Entender os florais de Bach →</a></p>
      </div>
    </div>
  </div>
</section>

<section class="section-alt">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Para quem atendo</span>
      <h2>Pessoas que já tentaram outros caminhos e querem investigar mais fundo.</h2>
      <p>Alguns exemplos de quem costuma me procurar — sem prometer resultado para nenhuma condição específica:</p>
    </div>
    <div class="pill-grid">
      <span class="pill">Quadros que se repetem apesar de vários tratamentos</span>
      <span class="pill">Ansiedade, insônia ou esgotamento</span>
      <span class="pill">Crianças com dificuldades recorrentes</span>
      <span class="pill">Gestantes que buscam cuidado suave</span>
      <span class="pill">Fases de transição ou luto</span>
      <span class="pill">Quem quer se conhecer melhor emocionalmente</span>
    </div>
    <p style="margin-top:20px;"><a href="{{ '/quem-pode-se-beneficiar/' | relative_url }}">Ver a página completa sobre quem pode se beneficiar →</a></p>
  </div>
</section>

<section>
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Como marcar</span>
      <h2>Três passos para começar</h2>
    </div>
    <div class="ledger">
      <div class="ledger-item">
        <span class="ledger-num">01</span>
        <div>
          <h3>Chame no WhatsApp</h3>
          <p>Conte brevemente o que te trouxe até aqui e combinamos um horário para a primeira consulta.</p>
        </div>
      </div>
      <div class="ledger-item">
        <span class="ledger-num">02</span>
        <div>
          <h3>Preencha o questionário</h3>
          <p>Antes da consulta, você recebe um questionário para organizar sua história de saúde.</p>
        </div>
      </div>
      <div class="ledger-item">
        <span class="ledger-num">03</span>
        <div>
          <h3>Consulta por videochamada</h3>
          <p>Conversamos com calma, sem pressa, para entender o quadro completo antes de qualquer indicação.</p>
        </div>
      </div>
    </div>
    <p style="margin-top:20px;"><a href="{{ '/como-funciona-a-consulta/' | relative_url }}">Ver o passo a passo completo da consulta →</a></p>
  </div>
</section>

<section class="section-alt">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Perguntas frequentes</span>
      <h2>Dúvidas comuns antes de agendar</h2>
    </div>
    <div class="faq-list">
      <details class="faq-item">
        <summary><span><span class="q-num">01</span>Homeopatia e florais de Bach têm contraindicação?</span><span class="icon">+</span></summary>
        <div class="faq-answer">
          De forma geral, são considerados de baixo risco e costumam ser usados como complemento ao
          tratamento médico convencional, nunca em substituição a ele. Cada caso é avaliado individualmente
          na consulta.
        </div>
      </details>
      <details class="faq-item">
        <summary><span><span class="q-num">02</span>Posso fazer o tratamento junto com remédios de uso contínuo?</span><span class="icon">+</span></summary>
        <div class="faq-answer">
          Sim, na maioria dos casos. Não se deve interromper nenhum medicamento prescrito por médico sem
          orientação dele. Esse ponto é sempre conversado na avaliação inicial.
        </div>
      </details>
      <details class="faq-item">
        <summary><span><span class="q-num">03</span>Crianças e gestantes podem ser atendidas?</span><span class="icon">+</span></summary>
        <div class="faq-answer">
          Sim, ambas as abordagens são compatíveis com crianças e gestantes, com condução adequada a cada fase da vida.
        </div>
      </details>
      <details class="faq-item">
        <summary><span><span class="q-num">04</span>Quanto tempo leva para perceber alguma diferença?</span><span class="icon">+</span></summary>
        <div class="faq-answer">
          Varia muito de pessoa para pessoa e de queixa para queixa. Isso é explicado com detalhes na
          consulta, depois de conhecer seu caso.
        </div>
      </details>
    </div>
    <p style="margin-top:22px;"><a href="{{ '/faq/' | relative_url }}">Ver todas as perguntas frequentes →</a></p>
  </div>
</section>

<section>
  <div class="container">
    <div class="cta-band">
      <div>
        <h2>Vamos conversar sobre o seu caso?</h2>
        <p>Mande uma mensagem contando brevemente o que você está buscando. Sem compromisso.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">
        Falar no WhatsApp
      </a>
    </div>
  </div>
</section>
