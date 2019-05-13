---
title: LPI
layout: default
---
# Estão abertas as incrições para o I Minicurso da LPI!

<img id="banner" src="/assets/facebook.jpeg" alt="I minicurso da LPI - Banner">

[comment]: <> <img class="quadro" src="/assets/arte-divulgacao2.jpeg" alt="I minicurso da LPI">

Sabe aquela dúvida sobre os possíveis achados num hemograma num contexto de infecções? Paciente com meningite, o que posso encontrar no estudo do líquor dessa pessoa? Essas e muitas outras questões sobre hemograma, sumário de urina, radiografia e exame do LCR no contexto das doenças infecciosas serão abordadas no Minicurso da LPI! Tu vai perder é?

E tem mais! Teremos discussão de casos clínicos sobre os temas! IMPERDÍVEL! Sem falar que a participação no minicurso dá um bônus de 10% na prova do processo seletivo da LPI... E como faço para me inscrever??

## Inscrição
1. Primeiro, fazer o pagamento de R$ 25, 00 se você for participar só do minicurso, R$ 30,00 se for minicurso + processo seletivo, por transferência bancária ou depósito “na boca do caixa”, NÃO ACEITAMOS PAGAMENTOS FEITOS POR ENVELOPES. A conta é:
```
Agência: 0963-6
Conta: 73833-6
CPF: 109.740.184-73
Nome: Antônio Cassiano Diniz Netto
Banco do Brasil
```
  > (Para alunos da FCM as incriçoes podem ser presenciais!!! É só procurar um dos ligantes e pedir informações)
2. Preencher o formulário de inscrição:<a class="botao" href="https://docs.google.com/forms/d/e/1FAIpQLSe2cmnIVgeufEd_hGlaiWT3FcU_t1Czu9BWm-3UTMujj-B9OA/viewform?usp=sf_link"><i class="fas fa-file-alt"></i>Formulário</a>
3. Enviar para o e-mail da LPI, <a href="mailto:ligainfectoupe@gmail.com=feedback">ligainfectoupe@gmail.com</a>, a foto do comprovante de pagamento + print de que foi enviado o formulário de inscrição + nome completo + CPF + instituição de ensino.


**As vagas são limitadas!!** Garanta já a sua!

**OBS:** quem for participar apenas do processo seletivo, os passos são os mesmos, mas o valor da inscrição somente no processo seletivo é de R$ 15,00

## Processo seletivo
Todas as informações sobre o nosso processo seletivo estão contidas no edital abaixo. As incrições estão abertas até 6 de Junho de 2019.

**Edital do processo seletivo:** <a class="botao" href="/assets/edital-selecao-2019.1.pdf"><i class="fas fa-link"></i>Edital</a>

<div class="post-list">
  <ul>
    {% for post in site.posts limit:10 %}
      <li class="post-list-li">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <a href="{{ post.url }}"></a>
        <p class="post-info">{{ post.date | date: "%-d" }} de {% assign m = post.date | date: "%-m" %}
        {% case m %}
          {% when '1' %}janeiro
          {% when '2' %}fevereiro
          {% when '3' %}março
          {% when '4' %}abril
          {% when '5' %}maio
          {% when '6' %}junho
          {% when '7' %}julho
          {% when '8' %}agosto
          {% when '9' %}setembro
          {% when '10' %}outubro
          {% when '11' %}novembro
          {% when '12' %}dezembro
        {% endcase %}{{ post.date | date: "%Y"}} - por {{ post.author }}</p>
        {{ post.excerpt | truncatewords: 40}}
      </li>
    {% endfor %}
  </ul>
</div>
