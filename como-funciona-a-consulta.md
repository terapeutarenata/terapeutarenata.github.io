---
layout: default
title: "Como Funciona a Consulta"
description: "Veja o passo a passo de uma consulta online de homeopatia e florais de Bach: agendamento, questionário, consulta, estudo de caso, escolha do medicamento e acompanhamento."
permalink: /como-funciona-a-consulta/
---

<section class="page-hero">
  <div class="container">
    <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Como funciona a consulta</p>
    <span class="eyebrow">Passo a passo</span>
    <h1>Como funciona a consulta, do primeiro contato ao acompanhamento</h1>
    <p class="lede">
      Um processo pensado para ser claro desde o início — você sabe exatamente o que esperar em cada etapa.
    </p>
    <div class="media-frame" style="max-width:320px; margin-top:24px;">
      <img src="{{ '/assets/images/como-funciona.jpg' | relative_url }}" alt="Ilustração 'Cuidado Integral': figura em meditação com uma flor, representando o acolhimento individualizado ao longo da consulta">
    </div>
  </div>
</section>

<section>
  <div class="container">
    <div class="ledger">

      <div class="ledger-item">
        <span class="ledger-num">01</span>
        <div>
          <h3>Agendamento pelo WhatsApp</h3>
          <p>
            Tudo começa com uma mensagem contando, em poucas linhas, o que te trouxe até aqui. A partir
            daí, combinamos data e horário para a primeira consulta e você recebe as orientações de pagamento.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">02</span>
        <div>
          <h3>Questionário prévio</h3>
          <p>
            Antes da consulta, você recebe um questionário detalhado sobre sua saúde física e emocional,
            histórico de tratamentos e rotina. Preenchê-lo com calma, com antecedência, ajuda a
            aproveitar melhor o tempo da consulta.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">03</span>
        <div>
          <h3>Consulta por videochamada</h3>
          <p>
            A primeira consulta é longa e detalhada — geralmente entre 60 e 90 minutos — para que
            possamos conversar sobre sua história com calma, sem pressa, cobrindo aspectos físicos,
            emocionais e de rotina que fazem diferença na avaliação.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">04</span>
        <div>
          <h3>Estudo do caso</h3>
          <p>
            Depois da consulta, dedico um tempo para organizar e estudar tudo o que foi conversado —
            incluindo, quando aplicável, a repertorização homeopática e a análise dos estados
            emocionais para os florais de Bach.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">05</span>
        <div>
          <h3>Escolha do medicamento ou dos florais</h3>
          <p>
            Com base no estudo do caso, defino o medicamento homeopático (ou a combinação de florais)
            mais adequado ao seu momento, além das orientações de uso.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">06</span>
        <div>
          <h3>Envio das orientações</h3>
          <p>
            Você recebe por escrito as orientações de uso, incluindo dosagem, horários e cuidados, além
            de onde adquirir o medicamento indicado.
          </p>
        </div>
      </div>

      <div class="ledger-item">
        <span class="ledger-num">07</span>
        <div>
          <h3>Acompanhamento e retorno</h3>
          <p>
            Combinamos uma data de retorno para avaliar a resposta ao tratamento e fazer os ajustes
            necessários. O intervalo entre consultas varia conforme o caso e é sempre conversado com você.
          </p>
        </div>
      </div>

    </div>

    {% include sprig.html %}

    <div class="callout" style="max-width:72ch;">
      Consultas de retorno costumam ser mais curtas que a primeira consulta, já que o estudo inicial do
      caso já foi feito. O objetivo do acompanhamento é observar a evolução ao longo do tempo — e não
      apenas prescrever uma vez e encerrar o cuidado.
    </div>

    <div class="cta-band" style="margin-top:40px;">
      <div>
        <h2>Pronto para começar?</h2>
        <p>O primeiro passo é uma mensagem simples no WhatsApp.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Agendar minha consulta</a>
    </div>
  </div>
</section>
