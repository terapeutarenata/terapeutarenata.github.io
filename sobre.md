---
layout: default
title: "Sobre Mim"
description: "Conheça a trajetória, a formação em homeopatia hahnemanniana e a filosofia de atendimento por trás do consultório online."
permalink: /sobre/
---

<section class="page-hero">
  <div class="container hero-grid">
    <div>
      <p class="crumb"><a href="{{ '/' | relative_url }}">Início</a> / Sobre mim</p>
      <span class="eyebrow">Sobre mim</span>
      <h1>A pergunta que mudou minha forma de olhar para a saúde</h1>
      <p class="lede">
        Antes de qualquer diploma, houve uma pergunta simples que não me saía da cabeça: por que tantas
        pessoas seguem de consultório em consultório, tomando cada vez mais remédios, e continuam se sentindo mal?
      </p>
    </div>
    <div class="media-frame" style="max-width:320px; justify-self:end;">
      <img src="{{ '/assets/images/sobre-mim.jpg' | relative_url }}" alt="Ilustração 'Sobre Mim': caderno de anotações e xícara de chá com flores, convidando a conhecer minha história e abordagem terapêutica">
    </div>
  </div>
</section>

<section>
  <div class="container prose">

    <h2>Como conheci a homeopatia</h2>
    <p>
      Foi observando de perto — em mim e em pessoas próximas — um padrão que se repetia: um sintoma
      aparecia, um medicamento alopático era prescrito para controlá-lo, e pouco tempo depois surgia um
      sintoma novo, muitas vezes mais incômodo que o anterior. Em vez de a pessoa ficar mais saudável a
      cada consulta, parecia que a lista de queixas só crescia.
    </p>
    <p>
      Essa observação me levou até a homeopatia, que enxerga o sintoma de um jeito diferente: não como um
      inimigo a ser calado, mas como um sinal de que algo, no conjunto da pessoa, está pedindo atenção.
      Quando esse sinal é apenas suprimido, sem que a causa seja realmente trabalhada, é comum que o
      organismo expresse o desequilíbrio de outra forma — às vezes em outro órgão, às vezes em outro
      plano, físico ou emocional. Foi entender essa lógica que me fez estudar homeopatia a sério, e não
      parar mais.
    </p>

    {% include sprig.html %}

    <h2>Minha filosofia de atendimento</h2>
    <p>
      Sigo a linha da <strong>homeopatia hahnemanniana clássica</strong> — a homeopatia tal como descrita
      por Samuel Hahnemann, seu criador, no <em>Organon da Arte de Curar</em>. Isso significa, na prática:
    </p>
    <ul>
      <li>Uma consulta longa e detalhada, porque cada pessoa adoece — e se recupera — à sua maneira.</li>
      <li>Um único medicamento por vez, escolhido a partir do conjunto de sintomas físicos, emocionais e
        de personalidade da pessoa, e não da doença isolada.</li>
      <li>Acompanhamento próximo da resposta ao tratamento, com ajustes ao longo do tempo.</li>
      <li>Respeito total ao tratamento médico convencional em curso — a homeopatia entra como
        complemento, nunca como substituição.</li>
    </ul>

    <blockquote>
      "Não existe doença, existe doente." É essa frase, atribuída à tradição homeopática, que resume o
      motivo de eu insistir em consultas longas e detalhadas, mesmo quando a queixa parece simples.
    </blockquote>

    <h2>Por que escolhi essa profissão</h2>
    <p>
      Escolhi esse caminho pensando em quem já está cansado de ir e vir entre consultórios sem sentir que
      chegou a algum lugar. Pessoas que colecionam exames normais e continuam se sentindo mal. Pessoas que
      ouvem "está tudo bem" e sabem, no corpo, que não está. Meu trabalho é dedicar tempo e escuta a esse
      tipo de história — investigar com calma, sem pressa de calar o sintoma, para tentar entender a raiz
      do que está acontecendo.
    </p>

    <div class="callout">
      <strong>Importante:</strong> este site tem caráter educativo. A homeopatia e os florais de Bach são
      terapias complementares; não substituem diagnóstico, acompanhamento ou tratamento médico. Cada caso
      é avaliado individualmente, e nenhum resultado é garantido previamente.
    </div>

    <h2>Formação</h2>
    <ul>
      <li>Formação em Homeopatia (linha hahnemanniana clássica).</li>
      <li>Atualização contínua através de estudos de caso, pesquisas e produção de conteúdos educacionais.</li>
    </ul>
    <p class="small-print">
      Continuo meu caminho em constantes atualizações sobre meus conhecimentos.
    </p>

    <div class="cta-band" style="margin-top:40px;">
      <div>
        <h2>Quer conversar sobre o seu caso?</h2>
        <p>Me conte brevemente o que te trouxe até aqui.</p>
      </div>
      <a class="btn btn-primary" href="https://wa.me/{{ site.whatsapp_number }}?text={{ site.whatsapp_message | url_encode }}" target="_blank" rel="noopener">Falar no WhatsApp</a>
    </div>

  </div>
</section>
