ï»¿# motores-de-video

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![motores-de-video](guia/assets/banner.jpg)](https://inematds.github.io/motores-de-video/guia/)

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

## O que êÂ©

Este repositêÂ³rio êÂ© um êÂ­ndice: ele explica, em uma pêÂ¡gina, cada motor que o INEMA usa para produzir vêÂ­deos ê¢â¬â explicativos, reels, radares diêÂ¡rios, vêÂ­deos feitos em cêÂ³digo. Serve para quem quer saber qual motor usar, ou estudar um deles. Cada motor tem o que faz, para que tipo de vêÂ­deo serve, o formato, se usa avatar, como êÂ© acionado, o link do cêÂ³digo e atêÂ© 3 vêÂ­deos reais publicados no YouTube. Para ler, nêÂ£o precisa instalar nada.

## ê°Å¸ââ Guia de uso

PêÂ¡gina completa (motores em cartêÂµes, com os vêÂ­deos): **https://inematds.github.io/motores-de-video/guia/**

## Os motores

Exemplos atualizados em 09/11/2026. Os links vêÂªm do histêÂ³rico de publicaêÂ§êÂµes e abrem no YouTube.

### Explicativos com avatar

#### ê°Å¸Å½Â¬ explicavideos (explicavideo)

Motor base dos vêÂ­deos explicativos: o roteiro vira cenas com ilustraêÂ§êÂµes, capêÂ­tulos e legenda, e o avatar do Nei fala o texto. Tem um perfil viral, com gancho na abertura e imagens de impacto.

- **Serve para:** Explicar um assunto, uma ferramenta ou um projeto do INEMA, do vêÂ­deo longo ao corte curto.
- **Formato:** 16:9 e 9:16
- **Avatar:** Sim ê¢â¬â avatar e voz do Nei pelo estêÂºdio HeyGen (hêÂ¡ versêÂ£o sem avatar, com voz local)
- **Como êÂ© acionado:** Terminal (sessêÂ£o com o agente) ou bot: /explicavideo <assunto> no inemaccbot
- **RepositêÂ³rio:** [github.com/inematds/explicavideos](https://github.com/inematds/explicavideos)
- **Exemplos publicados:**
  - [EsqueêÂ§a todas as IAs: chegou o novo rei ê¢â¬â Claude Fable 5.2 nos nêÂºmeros: custo, esforêÂ§o #shorts](https://www.youtube.com/watch?v=cgZSgxjXaWs) ê¢â¬â INEMA Tec, 09/11/2026, 9:16
  - [Seu time de bots pela assinatura que vocêÂª jêÂ¡ paga: 193 de 193 testes, sem API (kit grêÂ¡tis)](https://www.youtube.com/watch?v=lA9BHfoVZDo) ê¢â¬â INEMA FTD, 09/11/2026, 16:9
  - [Do chat ao agente em 4 degraus: aprenda do zero, ainda em 2026, sem programar #shorts](https://www.youtube.com/watch?v=FSf-jUT_n6U) ê¢â¬â INEMA TDS, 09/11/2026, 9:16

#### ê°Å¸âÂ refazvideo

Passo a passo para um agente de IA refazer um vêÂ­deo de referêÂªncia como explicativo prêÂ³prio, em portuguêÂªs: baixa, transcreve, escreve um roteiro novo, mostra uma prêÂ©via e sêÂ³ gera o avatar depois do "pode fazer".

- **Serve para:** Explicar em portuguêÂªs um assunto que apareceu num bom vêÂ­deo, sem gravar a si mesmo.
- **Formato:** 16:9 e 9:16
- **Avatar:** Sim ê¢â¬â avatar e voz do Nei (HeyGen); renderiza no explicavideos
- **Como êÂ© acionado:** Terminal (sessêÂ£o com o agente), com prêÂ©via e OK antes do avatar
- **RepositêÂ³rio:** [github.com/inematds/refazvideo](https://github.com/inematds/refazvideo)
- **Exemplos publicados:**
  - [IA sem censura: como funciona, onde usar e quanto custa](https://www.youtube.com/watch?v=ZsnxZmxcOSQ) ê¢â¬â INEMA Tec, 09/11/2026, 16:9
  - [Como criar agentes de IA que aprendem com os prêÂ³prios erros](https://www.youtube.com/watch?v=bnLvmYcP4PI) ê¢â¬â INEMA FTD, 08/11/2026, 16:9
  - [MovieFlow: uma frase vira um filme (13 modelos de IA) #shorts](https://www.youtube.com/watch?v=WizdRuVKl1U) ê¢â¬â INEMA FTD, 06/11/2026, 9:16

#### ê°Å¸âÂºê¯Â¸Â r7exp

Explicativo visual que ensina opêÂ§êÂµes: um grêÂ¡fico que funciona como mapa, a mesma pessoa atravessando cada cenêÂ¡rio, painêÂ©is que entram na palavra falada e, no fim, o que vocêÂª pode fazer.

- **Serve para:** Temas com caminhos ou cenêÂ¡rios ("qual futuro", "qual escolha"), em que cada opêÂ§êÂ£o precisa ser explicada.
- **Formato:** 16:9 completo + um reel 9:16 por opêÂ§êÂ£o
- **Avatar:** Sim ê¢â¬â avatar do Nei (meia tela no comeêÂ§o, depois no canto)
- **Como êÂ© acionado:** Terminal (sessêÂ£o com o agente); motor ainda em protêÂ³tipo
- **RepositêÂ³rio:** [github.com/inematds/r7exp](https://github.com/inematds/r7exp)
- **Exemplos publicados:**
  - [A IA descobre. E vocêÂª? #shorts](https://www.youtube.com/watch?v=0aE_BstdJkY) ê¢â¬â INEMA Futuros, 04/11/2026, 9:16
  - [A IA resolveu 100 anos de ciêÂªncia? As 3 descobertas explicadas no mapa](https://www.youtube.com/watch?v=PJIsN8MMHVE) ê¢â¬â INEMA Futuros, 29/10/2026, 16:9
  - [PHP2Shell: seu site estêÂ¡ exposto? Veja como se proteger](https://www.youtube.com/watch?v=YkqpuErgrqE) ê¢â¬â INEMA TDS, 23/10/2026, 16:9

#### ê°Å¸ÅÅ½ TraduêÂ§êÂ£o de vêÂ­deo EN/ES

Leva um vêÂ­deo pronto para inglêÂªs e espanhol no mesmo formato do portuguêÂªs: roteiro e deixas traduzidos pelo tradutor central, avatar e voz do Nei no idioma novo, montagem no explicavideos. Em espanhol, cada vêÂ­deo entra numa fila que publica aos poucos no canal Inema Espanhol.

- **Serve para:** VersêÂµes EN/ES de explicativos, reels e aulas.
- **Formato:** 16:9 e 9:16 (igual ao original)
- **Avatar:** Sim ê¢â¬â avatar e voz do Nei no idioma
- **Como êÂ© acionado:** Terminal (sessêÂ£o) + fila-espanhol com timer (1 vêÂ­deo a cada 2 h, atêÂ© 8 por dia)
- **RepositêÂ³rio:** [github.com/inematds/explicavideos](https://github.com/inematds/explicavideos) êÂ· fila-espanhol: repositêÂ³rio privado
- **Exemplos publicados:**
  - [REA: tu agente de IA sin trabas para adaptar programas en tu computadora](https://www.youtube.com/watch?v=S1uTys1xGnc) ê¢â¬â Inema Espanhol, 17/10/2026, 16:9
  - [IA Cultivada: por quêÂ© tu IA repite errores y cêÂ³mo hacer que mejore](https://www.youtube.com/watch?v=hzuNcPqHOEI) ê¢â¬â Inema Espanhol, 14/10/2026, 16:9
  - [Codex + Claude: uno planifica, el otro critica #Shorts](https://www.youtube.com/watch?v=L3-LqTC_qeI) ê¢â¬â Inema Espanhol, 14/10/2026, 9:16

### Reels virais 9:16

#### ê¢Å¡Â¡ r7ex

Linha de produêÂ§êÂ£o de reels com roteiro de 7 etapas de gatilho, do gancho com nêÂºmero ao pedido de comentêÂ¡rio, e acabamento de telejornal: têÂ­tulo desenhado na abertura, painêÂ©is no tempo da fala, contador e legenda que acende com a voz.

- **Serve para:** Reel viral de 40 a 50 segundos a partir de uma tese ou opiniêÂ£o forte.
- **Formato:** 9:16
- **Avatar:** Sim ê¢â¬â Nei em meia tela no gancho, depois no canto (HeyGen)
- **Como êÂ© acionado:** Terminal (/r7ex) ou bot: /r7ex <tema> no inemaccbot; publicaêÂ§êÂ£o por fila com timer
- **RepositêÂ³rio:** [github.com/inematds/r7ex](https://github.com/inematds/r7ex)
- **Exemplos publicados:**
  - [Para de criar app de IA: os 13 negêÂ³cios com IA do pior ao melhor #shorts](https://www.youtube.com/watch?v=9xtleXd3Kaw) ê¢â¬â INEMA FTD, 08/11/2026, 9:16
  - [Seu prompt nêÂ£o êÂ© cadeado: 5 travas para o agente de IA #shorts](https://www.youtube.com/watch?v=CxjmcmF-GWg) ê¢â¬â INEMA Tec, 08/11/2026, 9:16
  - [Ex-chefe do Google avisa: NêÆO estamos prontos para a IA #shorts](https://www.youtube.com/watch?v=0VdykM91Gzw) ê¢â¬â INEMA Futuros, 08/11/2026, 9:16

#### ê°Å¸Â§Â© rtex

Reel de "N peêÂ§as": um tema por vêÂ­deo, gancho forte no quadro de abertura, os passos do mêÂ©todo e, no fim, uma pergunta de opiniêÂ£o para o pêÂºblico responder. Validador, crêÂ­tico automêÂ¡tico e QA conferem o formato antes de publicar.

- **Serve para:** Reel de mêÂ©todo ou lista ("as 3 peêÂ§as deê¢â¬Â¦") que puxa comentêÂ¡rio.
- **Formato:** 9:16 (60ê¢â¬â90 s)
- **Avatar:** Sim ê¢â¬â avatar do Nei pelo estêÂºdio HeyGen
- **Como êÂ© acionado:** Terminal ou bot: /rtex <tema> no inemaccbot; fila com timer
- **RepositêÂ³rio:** [github.com/inematds/rtex](https://github.com/inematds/rtex)
- **Exemplos publicados:**
  - [Seu design virou colagem: coloque critêÂ©rio antes do efeito #shorts](https://www.youtube.com/watch?v=DLPw-sI_TJI) ê¢â¬â INEMA FTD, 09/11/2026, 9:16
  - [Pare de pedir slide assim pro Claude: 3 peêÂ§as pra ter a sua cara #shorts](https://www.youtube.com/watch?v=mz2WjAoNwok) ê¢â¬â INEMA Tec, 06/11/2026, 9:16
  - [Pare de disparar em volume para lista fria: prospecte por sinal com IA #shorts](https://www.youtube.com/watch?v=dydHb8BkkJk) ê¢â¬â INEMA TDS, 05/11/2026, 9:16

#### ê°Å¸âÅê¯Â¸Â rtexjp

Monta reels ilustrados em azul-marinho a partir de um roteiro.json: gera a voz no prêÂ³prio computador, desenha cada cena, mistura a trilha e confere sozinho o formato. Sem gravar e sem serviêÂ§o de avatar pago.

- **Serve para:** Reel no padrêÂ£o rtex quando nêÂ£o hêÂ¡ avatar gravado: tudo ilustrado.
- **Formato:** 9:16
- **Avatar:** Personagem ilustrado do Nei (sem HeyGen), voz local
- **Como êÂ© acionado:** Terminal ou bot: /rtexjp <tema> no inemaccbot
- **RepositêÂ³rio:** [github.com/inematds/rtexjp](https://github.com/inematds/rtexjp)
- **Exemplos publicados:**
  - [VocêÂª paga 200 dêÂ³lares. A IA custa atêÂ© 5 mil. #shorts](https://www.youtube.com/watch?v=UKqxVXTDVfI) ê¢â¬â INEMA TDS, 05/11/2026, 9:16
  - [E se a China fechar a torneira da IA grêÂ¡tis? #shorts](https://www.youtube.com/watch?v=78O5l2Coiv4) ê¢â¬â INEMA TDS, 05/11/2026, 9:16
- Por enquanto, sêÂ³ 2 exemplos encontrados no histêÂ³rico.

#### 7ê¯Â¸Âê¢ÆÂ£ reel7etapas (antecessor do r7ex)

O primeiro modelo de reel em 7 etapas de gatilho (gancho, desejo, medo, facilidade, descoberta, benefêÂ­cio, comentêÂ¡rio), com uma imagem por etapa e montagem em Python. Desde 18/10/2026 o padrêÂ£o êÂ© o r7ex; o repositêÂ³rio guarda o motor antigo e o histêÂ³rico.

- **Serve para:** ReferêÂªncia do roteiro de 7 etapas; reels novos saem pelo r7ex.
- **Formato:** 9:16
- **Avatar:** Sim ê¢â¬â avatar do Nei (HeyGen)
- **Como êÂ© acionado:** Terminal (/reel7etapas) ê¢â¬â substituêÂ­do pelo r7ex
- **RepositêÂ³rio:** [github.com/inematds/reel7etapas](https://github.com/inematds/reel7etapas)
- **Exemplos publicados:**
  - [Vem aêÂ­ demissêÂ£o em massa de gerentes? A IA vai cobrar preparo #shorts](https://www.youtube.com/watch?v=xpDV5qQe5oE) ê¢â¬â INEMA FTD, 18/10/2026, 9:16
- Motor antigo: o exemplo mostra o padrêÂ£o anterior, que levou ao r7ex. Para ver o formato atual, veja os exemplos do r7ex.

### Radares diêÂ¡rios automêÂ¡ticos

#### ê°Å¸âÂ° finviral

Assiste por transcriêÂ§êÂ£o aos vêÂ­deos dos maiores influenciadores de finanêÂ§as, separa nêÂºmeros, fatos e polêÂªmicas e monta um vêÂ­deo com nêÂºmeros grandes animados, a fonte de cada dado na tela e o Nei comentando. Sem recomendaêÂ§êÂ£o de investimento.

- **Serve para:** Resumo diêÂ¡rio do que se falou de finanêÂ§as; no fim de semana, "A semana explicada".
- **Formato:** 9:16 diêÂ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim ê¢â¬â Nei comentando (HeyGen)
- **Como êÂ© acionado:** Timer: segunda a sexta 02:00, balanêÂ§o no sêÂ¡bado
- **RepositêÂ³rio:** [github.com/inematds/finviral](https://github.com/inematds/finviral)
- **Exemplos publicados:**
  - [US$ 3 trilhêÂµes somem de Wall Street: a bolha da IA vai estourar?](https://www.youtube.com/watch?v=lVnzzTdXz9I) ê¢â¬â INEMA TIA, 09/11/2026, 9:16
  - [Selic parada em 13,75%: o que esperar atêÂ© dezembro, explicado](https://www.youtube.com/watch?v=pZ2ZCs_Udyo) ê¢â¬â INEMA TIA, 08/11/2026, 16:9
  - [Financiamento de imêÂ³vel vai de 11% a 15% apêÂ³s a eleiêÂ§êÂ£o: o que muda](https://www.youtube.com/watch?v=4x2j7Xbq5ng) ê¢â¬â INEMA TIA, 06/11/2026, 9:16

#### ê°Å¸Â©Âº saudeviral

O mesmo radar para mêÂ©dicos, nutricionistas e psicêÂ³logos de maior audiêÂªncia: tudo relatado e atribuêÂ­do, e o que nêÂ£o tem consenso na medicina sai com o carimbo "SEM CONSENSO". NêÂ£o substitui consulta mêÂ©dica.

- **Serve para:** Resumo diêÂ¡rio do que os influenciadores de saêÂºde disseram.
- **Formato:** 9:16 diêÂ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim ê¢â¬â Nei comentando (HeyGen)
- **Como êÂ© acionado:** Timer: segunda a sexta 05:00, balanêÂ§o no sêÂ¡bado
- **RepositêÂ³rio:** [github.com/inematds/saudeviral](https://github.com/inematds/saudeviral)
- **Exemplos publicados:**
  - [Seu tipo sanguêÂ­neo muda o risco de cêÂ¢ncer? O radar da saêÂºde](https://www.youtube.com/watch?v=fN8iKWuTbmg) ê¢â¬â INEMA TIA, 09/11/2026, 9:16
  - [Borderline, luto do vivo e 1.800 degraus | A semana explicada](https://www.youtube.com/watch?v=xgvdLWqTtQw) ê¢â¬â INEMA TIA, 08/11/2026, 16:9
  - [Luto de quem estêÂ¡ vivo, borderline e a gema do ovo: a semana da saêÂºde](https://www.youtube.com/watch?v=BC4_4tpDUYE) ê¢â¬â INEMA TIA, 08/11/2026, 9:16

#### ê¢Å¡âê¯Â¸Â advviral

Radar do que os maiores advogados do YouTube disseram sobre direitos: consumidor, previdêÂªncia, trabalho, dêÂ­vidas, imêÂ³vel, famêÂ­lia e golpes. Nada vira conselho para o seu caso, e proposta de lei êÂ© chamada de proposta.

- **Serve para:** Resumo diêÂ¡rio de direitos, em linguagem simples.
- **Formato:** 9:16 diêÂ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim ê¢â¬â Nei comentando (HeyGen)
- **Como êÂ© acionado:** Timer: segunda a sexta 08:00, balanêÂ§o no sêÂ¡bado
- **RepositêÂ³rio:** [github.com/inematds/advviral](https://github.com/inematds/advviral)
- **Exemplos publicados:**
  - [Processos contra o INSS mais que dobraram: por que tanta gente vai êÂ  JustiêÂ§a](https://www.youtube.com/watch?v=TE9-6B4NbxM) ê¢â¬â INEMA TIA, 09/11/2026, 9:16
  - [Ataque hacker de US$ 49 mi êÂ  cripto: quem paga? | A semana explicada](https://www.youtube.com/watch?v=glv2cyDDECc) ê¢â¬â INEMA TIA, 08/11/2026, 16:9
  - [Aposentadoria com 15 anos paga sêÂ³ 60% da mêÂ©dia, e mais 4 direitos](https://www.youtube.com/watch?v=pB4iDtByzyc) ê¢â¬â INEMA TIA, 07/11/2026, 16:9

#### ê¢Å¡Â½ futviral

Resumo do que os 10 maiores canais de futebol disseram: BrasileirêÂ£o, futebol europeu, mercado da bola e negêÂ³cios, com carimbos (RUMOR, NEGOCIANDO, FECHADO, POLêÅ MICA). Rumor êÂ© tratado como rumor e aposta nêÂ£o entra.

- **Serve para:** Radar diêÂ¡rio de futebol.
- **Formato:** 9:16 diêÂ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim ê¢â¬â Nei comentando (HeyGen)
- **Como êÂ© acionado:** Timer: gera êÂ s 9h, publica ao meio-dia
- **RepositêÂ³rio:** [github.com/inematds/futviral](https://github.com/inematds/futviral)
- **Exemplos publicados:**
  - [GrêÂªmio na zona de rebaixamento e na final de R$ 78 milhêÂµes](https://www.youtube.com/watch?v=7VM2auexshA) ê¢â¬â Inema Club24, 09/11/2026, 9:16
  - [FUTVIRAL: Flamengo pode ser campeêÂ£o no Allianz e Vasco decide hoje](https://www.youtube.com/watch?v=d-J-JeG8dTU) ê¢â¬â Inema Club24, 08/11/2026, 9:16
  - [Flamengo a 2 vitêÂ³rias do têÂ­tulo no Allianz? A semana explicada](https://www.youtube.com/watch?v=aVWqhfVehwA) ê¢â¬â Inema Club24, 08/11/2026, 16:9

#### ê°Å¸Â§Â¾ contaviral

Resumo do que os 10 maiores canais de contabilidade e tributos disseram: leis e portarias, Reforma TributêÂ¡ria, MEI e Simples, imposto de renda e obrigaêÂ§êÂµes fiscais, com carimbos (MUDOU A REGRA, PROPOSTA, PRAZO, ALERTA).

- **Serve para:** Radar diêÂ¡rio contêÂ¡bil e tributêÂ¡rio.
- **Formato:** 9:16 diêÂ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim ê¢â¬â Nei comentando (HeyGen)
- **Como êÂ© acionado:** Timer: gera êÂ s 10h, publica êÂ s 13h
- **RepositêÂ³rio:** [github.com/inematds/contaviral](https://github.com/inematds/contaviral)
- **Exemplos publicados:**
  - [PerdêÂ£o do MEI: quem parcelou pode parar? E o Seletivo sêÂ³ em fevereiro](https://www.youtube.com/watch?v=0EG5d9CgNLo) ê¢â¬â INEMA TIA, 09/11/2026, 9:16
  - [CBS a 11,34%? A alêÂ­quota que assustou e o que mais mudou na semana](https://www.youtube.com/watch?v=noBpqjKgdNQ) ê¢â¬â INEMA TIA, 08/11/2026, 9:16
  - [CBS de 11,34%, inflaêÂ§êÂ£o e perdêÂ£o do MEI: a semana contêÂ¡bil explicada](https://www.youtube.com/watch?v=qsYlEy48vaY) ê¢â¬â INEMA TIA, 08/11/2026, 16:9

### Outras linhas e sêÂ©ries

#### ê°Å¸ÅÂªê¯Â¸Â eventosextremospub (clima)

Transforma alertas de tempo severo num vêÂ­deo de "sala de crise": baixa dados pêÂºblicos (alertas do INMET por municêÂ­pio, satêÂ©lite GOES-19, previsêÂ£o do Open-Meteo), anima tudo num mapa 3D do Sul do Brasil e mostra a fonte de cada nêÂºmero.

- **Serve para:** Clima do dia, previsêÂ£o e alertas da semana.
- **Formato:** 9:16
- **Avatar:** Sim ê¢â¬â Nei pelo estêÂºdio HeyGen
- **Como êÂ© acionado:** Timers ao longo do dia (Clima 24 h, PrevisêÂ£o do Dia, Clima do DIA, alertas)
- **RepositêÂ³rio:** [github.com/inematds/eventosextremospub](https://github.com/inematds/eventosextremospub)
- **Exemplos publicados:**
  - [O clima no mundo 09/11: duna cai sobre barracas em Gaza, enxurrada no Iraque #Shorts](https://www.youtube.com/watch?v=i11SMouAllE) ê¢â¬â Eventos Extremos INEMA, 09/11/2026, 9:16
  - [654 cidades em alerta de tempestade amanhêÂ£ êÂ· Alerta da semana 09/11 #Shorts](https://www.youtube.com/watch?v=E8xsGn0xRXQ) ê¢â¬â Eventos Extremos INEMA, 09/11/2026, 9:16
  - [Clima do dia 09/11: geada em novembro e 0,8 êÂ°C na serra catarinense #Shorts](https://www.youtube.com/watch?v=eN05Dt_jM0M) ê¢â¬â Eventos Extremos INEMA, 09/11/2026, 9:16

#### ê°Å¸ââ¬ Vigia de canal

Todo dia olha um canal de referêÂªncia; se houver vêÂ­deo novo, faz um explicavideo inspirado no conteêÂºdo, na voz do Nei, e publica direto. Sem vêÂ­deo novo, nêÂ£o faz nada, e nunca repete um vêÂ­deo.

- **Serve para:** Explicativos automêÂ¡ticos, sem ninguêÂ©m pedir, quando sai conteêÂºdo novo na referêÂªncia.
- **Formato:** 16:9 + 9:16 (menos de 2 min)
- **Avatar:** Sim ê¢â¬â avatar e voz do Nei
- **Como êÂ© acionado:** Timer diêÂ¡rio êÂ s 14h
- **RepositêÂ³rio:** repositêÂ³rio privado
- **Exemplos publicados:**
  - [5 palavras e o projeto no ar: por que o prompt curto funciona melhor #shorts](https://www.youtube.com/watch?v=Lw-LdQiyUpA) ê¢â¬â INEMA LOOPY, 07/11/2026, 9:16
  - [Prompt de 5 palavras e zero cêÂ³digo: 7 hêÂ¡bitos de quem estêÂ¡ no topo da IA](https://www.youtube.com/watch?v=T6d1k8fgVHQ) ê¢â¬â INEMA LOOPY, 07/11/2026, 16:9
  - [A IA desligou 25 apps da TV e achou um minerador escondido: 3 usos que quase ninguêÂ©m faz](https://www.youtube.com/watch?v=hageCcHOcLE) ê¢â¬â INEMA LOOPY, 06/11/2026, 9:16

#### ê°Å¸Ââ¢ê¯Â¸Â historia-timelapse

Timelapse 3D da histêÂ³ria de uma cidade: relevo real, prêÂ©dios do OpenStreetMap nascendo no ano em que o bairro foi ocupado, contador de populaêÂ§êÂ£o do IBGE e cartêÂµes com nêÂºmero, explicaêÂ§êÂ£o e fonte.

- **Serve para:** HistêÂ³ria de cidades em vêÂ­deo; sai em fases (sêÂ³ mêÂºsica, narrada, com avatar).
- **Formato:** 16:9
- **Avatar:** Opcional ê¢â¬â fase 3 com avatar do Nei
- **Como êÂ© acionado:** Terminal (skill historia-timelapse); fila de publicaêÂ§êÂ£o
- **RepositêÂ³rio:** [github.com/inematds/historia-timelapse](https://github.com/inematds/historia-timelapse)
- **Exemplos publicados:**
  - [Porto Alegre de 1772 a 2024: 252 anos em um timelapse 3D com luz realista](https://www.youtube.com/watch?v=WzPVdaal1OY) ê¢â¬â Aventuras INEMA, 24/10/2026, 16:9
  - [O centro de ItaguaêÂ­ em 3D: da Matriz de 1729 êÂ  cidade do futuro](https://www.youtube.com/watch?v=dalR1xWPFlE) ê¢â¬â Aventuras INEMA, 23/10/2026, 16:9
  - [Rio de Janeiro de 1500 a 2024: 524 anos de histêÂ³ria em timelapse 3D](https://www.youtube.com/watch?v=Ij4KsTN_SB0) ê¢â¬â Aventuras INEMA, 23/10/2026, 16:9

#### ê°Å¸Ââê¯Â¸Â aventurasinemavideo (MemêÂ³rias de Aventura)

Transforma matêÂ©rias reais do acervo do INEMA Aventura (2001 a 2012), com o relato e as fotos dos prêÂ³prios aventureiros, em filmes narrados de 1 a 3 minutos: fotos restauradas com movimento e narraêÂ§êÂ£o na voz do Nei.

- **Serve para:** A sêÂ©rie MemêÂ³rias de Aventura.
- **Formato:** 16:9
- **Avatar:** NêÂ£o ê¢â¬â fotos do acervo + narraêÂ§êÂ£o
- **Como êÂ© acionado:** Terminal / lote, com publicaêÂ§êÂ£o no canal Aventuras INEMA
- **RepositêÂ³rio:** [github.com/inematds/aventurasinemavideo](https://github.com/inematds/aventurasinemavideo)
- **Exemplos publicados:**
  - [Beto Monteiro vence sob calor de 35êÂ°C na FêÂ³rmula Truck | MemêÂ³rias de Aventura #166](https://www.youtube.com/watch?v=vjsykS5_9HU) ê¢â¬â Aventuras INEMA, 09/11/2026, 16:9
  - [Allam Khodair: de 4êÂº a vencedor na Stock Car 2010 | MemêÂ³rias de Aventura #165](https://www.youtube.com/watch?v=PLPcwWAQgqE) ê¢â¬â Aventuras INEMA, 09/11/2026, 16:9
  - [De Curitiba ao Alasca de moto: 34 mil km em 1997 | MemêÂ³rias de Aventura #164](https://www.youtube.com/watch?v=iqrvHLIET2Y) ê¢â¬â Aventuras INEMA, 09/11/2026, 16:9

#### ê°Å¸âÂ¥ gitbombando

Todo dia faz o reel "Bombando no GitHub": os 10 projetos que mais ganharam estrelas, em contagem regressiva, com cartêÂ£o, foto do dono, o que faz em portuguêÂªs simples e o nêÂºmero de estrelas. TambêÂ©m gera dois carrossêÂ©is.

- **Serve para:** Novidades do GitHub Trending em 1 minuto.
- **Formato:** 9:16
- **Avatar:** Sim ê¢â¬â avatar do Nei (HeyGen)
- **Como êÂ© acionado:** Timer: gera êÂ s 9h, publica êÂ s 11h
- **RepositêÂ³rio:** [github.com/inematds/gitbombando](https://github.com/inematds/gitbombando)
- **Exemplos publicados:**
  - [CaêÂ§a-apelidos dispara ao topo do GitHub com +4.294 estrelas em um dia #Shorts](https://www.youtube.com/watch?v=W3Mds0R28_A) ê¢â¬â INEMA Tec, 09/11/2026, 9:16
  - [Cloudflare segue no topo e um caêÂ§a-apelidos invade o pêÂ³dio: +2.085 estrelas no GitHub #Shorts](https://www.youtube.com/watch?v=vXoQJMnVT1w) ê¢â¬â INEMA Tec, 08/11/2026, 9:16
  - [17.100 estrelas em 7 dias: o controle remoto de todas as IAs lidera o GitHub #Shorts](https://www.youtube.com/watch?v=3FXsmsRC0YA) ê¢â¬â INEMA Tec, 08/11/2026, 9:16

### VêÂ­deo feito em cêÂ³digo (sem cêÂ¢mera)

#### ê°Å¸âÂ» video-codigo

Skill para o Claude Code e o Codex em que cada quadro êÂ© escrito em cêÂ³digo (HTML, Canvas ou SVG) e vira MP4. A voz, quando hêÂ¡, êÂ© gerada no computador e cada imagem entra no instante da palavra.

- **Serve para:** LanêÂ§amento, anêÂºncio, explicativo ou filme de produto sem cêÂ¢mera e sem editor.
- **Formato:** 16:9 e 9:16 do mesmo projeto
- **Avatar:** NêÂ£o (rosto opcional, atêÂ© meia tela)
- **Como êÂ© acionado:** Terminal (skill no Claude Code ou Codex)
- **RepositêÂ³rio:** [github.com/inematds/video-codigo](https://github.com/inematds/video-codigo)
- **Exemplos publicados:**
  - [Lead que espera esfria: do WhatsApp êÂ  venda em 1 minuto, feito com cêÂ³digo #Shorts](https://www.youtube.com/watch?v=4ILX66Hddtk) ê¢â¬â INEMA FTD, 06/11/2026, 9:16
  - [Do WhatsApp êÂ  venda: filme de produto feito 100% com cêÂ³digo](https://www.youtube.com/watch?v=tWv1mEIK62c) ê¢â¬â INEMA FTD, 06/11/2026, 16:9
- Por enquanto, sêÂ³ 2 exemplos encontrados no histêÂ³rico.

#### ê°Å¸ÂªÂ reel-ciencia-3d

Kit com skill para o Claude Code que transforma uma pergunta "E seê¢â¬Â¦?" num reel de ciêÂªncia de cerca de 60 segundos, feito sêÂ³ com cêÂ³digo (HyperFrames e Three.js), com a fonte de cada nêÂºmero e voz local.

- **Serve para:** DivulgaêÂ§êÂ£o cientêÂ­fica em vêÂ­deo curto, sem errar nêÂºmero.
- **Formato:** 9:16 (~60 s)
- **Avatar:** NêÂ£o
- **Como êÂ© acionado:** Terminal (skill no Claude Code)
- **RepositêÂ³rio:** [github.com/inematds/reel-ciencia-3d](https://github.com/inematds/reel-ciencia-3d)
- **Exemplos publicados:**
  - [E se o Sol sumisse agora? AnimaêÂ§êÂ£o 3D feita sêÂ³ com cêÂ³digo](https://www.youtube.com/watch?v=FDtJim4xHjY) ê¢â¬â INEMA FTD, 06/11/2026, 9:16
  - [E se a Lua sumisse? AnimaêÂ§êÂ£o 3D feita sêÂ³ com cêÂ³digo](https://www.youtube.com/watch?v=nUsGrdZ-8MY) ê¢â¬â INEMA FTD, 06/11/2026, 9:16
  - [E se a Terra nêÂ£o tivesse inclinaêÂ§êÂ£o? AnimaêÂ§êÂ£o 3D feita sêÂ³ com cêÂ³digo](https://www.youtube.com/watch?v=BmSeV6r0FdQ) ê¢â¬â INEMA FTD, 06/11/2026, 9:16

#### ê°Å¸Å½â¢ê¯Â¸Â video-sem-rosto

Kit que ensina o Claude Code a fazer explicativos na horizontal sem gravar nada: voz clonada gerada no computador, a pêÂ¡gina real do site, imagens 3D e legenda sincronizada.

- **Serve para:** Explicar uma ferramenta, um repositêÂ³rio ou uma novidade sem aparecer.
- **Formato:** 16:9
- **Avatar:** NêÂ£o
- **Como êÂ© acionado:** Terminal (skill no Claude Code)
- **RepositêÂ³rio:** [github.com/inematds/video-sem-rosto](https://github.com/inematds/video-sem-rosto)
- Ainda sem vêÂ­deo publicado no YouTube por este motor; os vêÂ­deos de demonstraêÂ§êÂ£o estêÂ£o no guia do projeto.

#### ê°Å¸Å½â videos-cursos-inema

Motor que transforma um curso INEMA (site estêÂ¡tico) numa sêÂ©rie de vêÂ­deos narrados e animados, em trêÂªs partes selecionêÂ¡veis: landing, um vêÂ­deo por trilha e uma aula completa por mêÂ³dulo.

- **Serve para:** VêÂ­deos de divulgaêÂ§êÂ£o e aulas de um curso.
- **Formato:** 16:9 (e 9:16 com --vertical)
- **Avatar:** NêÂ£o ê¢â¬â narraêÂ§êÂ£o com voz clonada local
- **Como êÂ© acionado:** Terminal (skill videos-cursos-inema)
- **RepositêÂ³rio:** [github.com/inematds/videos-cursos-inema](https://github.com/inematds/videos-cursos-inema)
- Nenhum vêÂ­deo deste motor aparece no histêÂ³rico de publicaêÂ§êÂµes; o guia do projeto mostra o exemplo do curso FEP.

### Apoio

#### ê°Å¸âÅ  inemavox

SuêÂ­te de voz com IA local que todos os motores usam por baixo: baixa vêÂ­deos, transcreve, gera voz (TTS), dubla e corta, com os modelos rodando na placa de vêÂ­deo, sem custo de API.

- **Serve para:** Voz, transcriêÂ§êÂ£o, download e mêÂºsica/efeitos para os outros motores.
- **Como êÂ© acionado:** Terminal (scripts) ou API local
- **RepositêÂ³rio:** [github.com/inematds/inemavox](https://github.com/inematds/inemavox)
- Motor de apoio: nêÂ£o publica vêÂ­deo prêÂ³prio.

## O processo, do inêÂ­cio ao fim

ê°Å¸Â§Â  = sessêÂ£o com o Nei êÂ· ê¢Å¡â¢ê¯Â¸Â = script (sem gastar tokens) êÂ· ê°Å¸Â¤â = `claude -p`

1. ê°Å¸Â§Â  Motor novo ou mudanêÂ§a de texto: editar `catalogo.json` (texto em PT, regra que identifica os vêÂ­deos, `excluir`/`fixar`).
2. ê¢Å¡â¢ê¯Â¸Â `python3 traduzir.py` ê¢â¬â traduz para EN/ES sêÂ³ as chaves novas, pelo tradutor central `inema-traduz`, e grava `i18n/en.json` e `i18n/es.json`.
3. ê¢Å¡â¢ê¯Â¸Â `python3 atualizar-exemplos.py` ê¢â¬â lêÂª o histêÂ³rico do yt-pubx (`~/.local/share/yt-pubx/historico.jsonl`) e, se existir, o registro de produêÂ§êÂµes (separa explicavideo de refazvideo); escolhe atêÂ© 3 vêÂ­deos pêÂºblicos, recentes e variados por motor e grava `motores.json`.
4. ê¢Å¡â¢ê¯Â¸Â O mesmo comando roda `python3 gerar.py`, que regrava `README.md`, `README.en.md`, `README.es.md` e `guia/index.html`, `guia/en/`, `guia/es/` a partir do `motores.json`.
5. ê°Å¸Â§Â  Conferir a pêÂ¡gina e o README; `git push`. O GitHub Pages (Actions) publica a partir da branch `main`.

Fora da mêÂ¡quina que publica os vêÂ­deos nêÂ£o existe o histêÂ³rico do yt-pubx: o script avisa, mantêÂ©m os exemplos que jêÂ¡ estêÂ£o no `motores.json` e sêÂ³ aplica os textos novos. Os exemplos nêÂ£o sêÂ£o reconferidos no YouTube: o script sêÂ³ lêÂª arquivos locais. VêÂ­deo reprovado ou trocado entra em `excluir` no `catalogo.json`.

## Arquivos

| | |
|---|---|
| `catalogo.json` | fonte editada êÂ  mêÂ£o: textos dos motores, canais, regras de identificaêÂ§êÂ£o |
| `motores.json` | dados do êÂ­ndice gerados pelo script (motores + exemplos) |
| `atualizar-exemplos.py` | relêÂª o histêÂ³rico e regrava o motores.json |
| `gerar.py` | gera os READMEs e o guia a partir do motores.json |
| `traduzir.py` | traduz os textos novos para EN/ES (inema-traduz) |
| `i18n/` | textos da pêÂ¡gina e dos motores em PT, EN e ES |

## LicenêÂ§a

MIT. Projeto do [INEMA.CLUB](https://inema.club).

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>