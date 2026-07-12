---
layout: default
title: "Valores"
description: "Como funcionam os valores das consultas de homeopatia e florais de Bach e como solicitar um orçamento personalizado."
permalink: /valores/
---

<section class="page-hero">
  <div class="container">
    <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Valores</p>
    <span class="eyebrow">Investimento</span>
    <h1>Valores e orçamento</h1>
    <p class="lede">
      Os valores variam conforme o tipo de consulta (primeira consulta ou retorno) e a abordagem
      (homeopatia, florais de Bach, ou as duas em conjunto). Solicite um orçamento personalizado pelo WhatsApp.
    </p>
  </div>
</section>

<section>
  <div class="container prose">

    <h2>Como funcionam os valores</h2>
    <p>
      Como cada acompanhamento é individualizado, o valor exato é informado no momento do agendamento,
      considerando:
    </p>
    <ul>
      <li>Se é sua primeira consulta ou um retorno.</li>
      <li>Se o acompanhamento será em homeopatia, florais de Bach, ou nas duas abordagens em conjunto.</li>
      <li>A faixa etária do paciente (consultas infantis podem ter estrutura diferente).</li>
    </ul>

    <div class="grid-2" style="margin-top:1.6em;">
      <div class="card">
        <h3>Primeira consulta</h3>
        <p>Inclui anamnese completa, estudo do caso e escolha do medicamento ou dos florais, com orientações detalhadas de uso.</p>
      </div>
      <div class="card">
        <h3>Consultas de retorno</h3>
        <p>Avaliação da resposta ao tratamento e ajustes necessários, em encontros mais curtos que a consulta inicial.</p>
      </div>
    </div>

    {% include sprig.html %}

    <h2>Formas de pagamento</h2>
    <p>Pix e cartão. O pagamento é confirmado antes da realização da consulta.</p>

    <h2>Como solicitar um orçamento</h2>
    <p>
      Mande uma mensagem no WhatsApp contando se você busca homeopatia, florais de Bach ou as duas
      abordagens, se é para você ou para outra pessoa (indicando idade, no caso de crianças), e se será
      primeira consulta ou retorno. Assim, consigo te passar o valor certo e já sugerir horários disponíveis.
    </p>

    <div class="cta-band" style="margin-top:32px;">
      <div>
        <h2>Solicitar orçamento</h2>
        <p>Resposta rápida, geralmente no mesmo dia útil.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Pedir orçamento no WhatsApp</a>
    </div>
  </div>
</section>
