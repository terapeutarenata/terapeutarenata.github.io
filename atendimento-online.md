---
layout: default
title: "Atendimento Online"
description: "Saiba como funciona o atendimento online de homeopatia e florais de Bach: duração, plataformas usadas (WhatsApp e Google Meet), formas de pagamento e privacidade."
permalink: /atendimento-online/
---

<section class="page-hero">
  <div class="container">
    <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Atendimento online</p>
    <span class="eyebrow">Consultas por videochamada</span>
    <h1>Atendimento 100% online, para qualquer lugar do Brasil</h1>
    <p class="lede">
      Todas as consultas são feitas por videochamada. Veja abaixo como funciona na prática.
    </p>
  </div>
</section>

<section>
  <div class="container prose">

    <h2>Como funciona</h2>
    <p>
      Depois de agendar pelo WhatsApp e preencher o questionário prévio, você recebe um link de
      videochamada para o horário combinado. A consulta acontece de onde for mais confortável para
      você — de casa, do trabalho, ou de qualquer lugar com uma boa conexão de internet e um pouco de
      privacidade para conversar com tranquilidade.
    </p>

    <h2>Duração</h2>
    <ul>
      <li><strong>Primeira consulta:</strong> entre 60 e 90 minutos, para uma anamnese completa.</li>
      <li><strong>Consultas de retorno:</strong> geralmente entre 30 e 45 minutos.</li>
    </ul>

    <h2>Plataformas utilizadas</h2>
    <p>
      Uso duas ferramentas, de forma bem simples:
    </p>
    <ul>
      <li><strong>WhatsApp:</strong> para agendamento, envio do questionário, combinados e dúvidas rápidas entre consultas.</li>
      <li><strong>Google Meet:</strong> para a videochamada da consulta em si — não é necessário criar conta, basta clicar no link no horário combinado.</li>
    </ul>

    {% include sprig.html %}

    <h2>Pagamento</h2>
    <p>
      O pagamento é combinado no agendamento, geralmente via Pix ou cartão, com confirmação antes da
      consulta. Detalhes de valores e formas de pagamento estão na <a href="{{ '/valores/' | relative_url }}">página de valores</a>.
    </p>

    <h2>Privacidade</h2>
    <p>
      Todas as informações compartilhadas na consulta — questionário, conversa e histórico — são
      tratadas com sigilo profissional e não são divulgadas a terceiros. Recomendo que você também
      escolha um local privado para a videochamada, especialmente ao tratar de temas emocionais mais
      sensíveis.
    </p>
    <p class="small-print">
      Para detalhes sobre uso do site e dados de contato, veja os <a href="{{ '/termos-de-uso/' | relative_url }}">termos de uso</a>.
    </p>

    <div class="cta-band" style="margin-top:36px;">
      <div>
        <h2>Alguma dúvida sobre o atendimento online?</h2>
        <p>Fico à disposição no WhatsApp para esclarecer antes de você agendar.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Falar no WhatsApp</a>
    </div>
  </div>
</section>
