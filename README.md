# motores-de-video

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![motores-de-video](guia/assets/banner.jpg)](https://inematds.github.io/motores-de-video/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

Este repositÃ³rio Ã© um Ã­ndice: ele explica, em uma pÃ¡gina, cada motor que o INEMA usa para produzir vÃ­deos â€” explicativos, reels, radares diÃ¡rios, vÃ­deos feitos em cÃ³digo. Serve para quem quer saber qual motor usar, ou estudar um deles. Cada motor tem o que faz, para que tipo de vÃ­deo serve, o formato, se usa avatar, como Ã© acionado, o link do cÃ³digo e atÃ© 3 vÃ­deos reais publicados no YouTube. Para ler, nÃ£o precisa instalar nada.

## ðŸ“– Guia de uso

PÃ¡gina completa (motores em cartÃµes, com os vÃ­deos): **https://inematds.github.io/motores-de-video/guia/**

## Os motores

Exemplos atualizados em 09/11/2026. Os links vÃªm do histÃ³rico de publicaÃ§Ãµes e abrem no YouTube.

### Explicativos com avatar

#### ðŸŽ¬ explicavideos (explicavideo)

Motor base dos vÃ­deos explicativos: o roteiro vira cenas com ilustraÃ§Ãµes, capÃ­tulos e legenda, e o avatar do Nei fala o texto. Tem um perfil viral, com gancho na abertura e imagens de impacto.

- **Serve para:** Explicar um assunto, uma ferramenta ou um projeto do INEMA, do vÃ­deo longo ao corte curto.
- **Formato:** 16:9 e 9:16
- **Avatar:** Sim â€” avatar e voz do Nei pelo estÃºdio HeyGen (hÃ¡ versÃ£o sem avatar, com voz local)
- **Como Ã© acionado:** Terminal (sessÃ£o com o agente) ou bot: /explicavideo <assunto> no inemaccbot
- **RepositÃ³rio:** [github.com/inematds/explicavideos](https://github.com/inematds/explicavideos)
- **Exemplos publicados:**
  - [EsqueÃ§a todas as IAs: chegou o novo rei â€” Claude Fable 5.2 nos nÃºmeros: custo, esforÃ§o #shorts](https://www.youtube.com/watch?v=cgZSgxjXaWs) â€” INEMA Tec, 09/11/2026, 9:16
  - [Seu time de bots pela assinatura que vocÃª jÃ¡ paga: 193 de 193 testes, sem API (kit grÃ¡tis)](https://www.youtube.com/watch?v=lA9BHfoVZDo) â€” INEMA FTD, 09/11/2026, 16:9
  - [Do chat ao agente em 4 degraus: aprenda do zero, ainda em 2026, sem programar #shorts](https://www.youtube.com/watch?v=FSf-jUT_n6U) â€” INEMA TDS, 09/11/2026, 9:16

#### ðŸ” refazvideo

Passo a passo para um agente de IA refazer um vÃ­deo de referÃªncia como explicativo prÃ³prio, em portuguÃªs: baixa, transcreve, escreve um roteiro novo, mostra uma prÃ©via e sÃ³ gera o avatar depois do "pode fazer".

- **Serve para:** Explicar em portuguÃªs um assunto que apareceu num bom vÃ­deo, sem gravar a si mesmo.
- **Formato:** 16:9 e 9:16
- **Avatar:** Sim â€” avatar e voz do Nei (HeyGen); renderiza no explicavideos
- **Como Ã© acionado:** Terminal (sessÃ£o com o agente), com prÃ©via e OK antes do avatar
- **RepositÃ³rio:** [github.com/inematds/refazvideo](https://github.com/inematds/refazvideo)
- **Exemplos publicados:**
  - [IA sem censura: como funciona, onde usar e quanto custa](https://www.youtube.com/watch?v=ZsnxZmxcOSQ) â€” INEMA Tec, 09/11/2026, 16:9
  - [Como criar agentes de IA que aprendem com os prÃ³prios erros](https://www.youtube.com/watch?v=bnLvmYcP4PI) â€” INEMA FTD, 08/11/2026, 16:9
  - [MovieFlow: uma frase vira um filme (13 modelos de IA) #shorts](https://www.youtube.com/watch?v=WizdRuVKl1U) â€” INEMA FTD, 06/11/2026, 9:16

#### ðŸ—ºï¸ r7exp

Explicativo visual que ensina opÃ§Ãµes: um grÃ¡fico que funciona como mapa, a mesma pessoa atravessando cada cenÃ¡rio, painÃ©is que entram na palavra falada e, no fim, o que vocÃª pode fazer.

- **Serve para:** Temas com caminhos ou cenÃ¡rios ("qual futuro", "qual escolha"), em que cada opÃ§Ã£o precisa ser explicada.
- **Formato:** 16:9 completo + um reel 9:16 por opÃ§Ã£o
- **Avatar:** Sim â€” avatar do Nei (meia tela no comeÃ§o, depois no canto)
- **Como Ã© acionado:** Terminal (sessÃ£o com o agente); motor ainda em protÃ³tipo
- **RepositÃ³rio:** [github.com/inematds/r7exp](https://github.com/inematds/r7exp)
- **Exemplos publicados:**
  - [A IA descobre. E vocÃª? #shorts](https://www.youtube.com/watch?v=0aE_BstdJkY) â€” INEMA Futuros, 04/11/2026, 9:16
  - [A IA resolveu 100 anos de ciÃªncia? As 3 descobertas explicadas no mapa](https://www.youtube.com/watch?v=PJIsN8MMHVE) â€” INEMA Futuros, 29/10/2026, 16:9
  - [PHP2Shell: seu site estÃ¡ exposto? Veja como se proteger](https://www.youtube.com/watch?v=YkqpuErgrqE) â€” INEMA TDS, 23/10/2026, 16:9

#### ðŸŒŽ TraduÃ§Ã£o de vÃ­deo EN/ES

Leva um vÃ­deo pronto para inglÃªs e espanhol no mesmo formato do portuguÃªs: roteiro e deixas traduzidos pelo tradutor central, avatar e voz do Nei no idioma novo, montagem no explicavideos. Em espanhol, cada vÃ­deo entra numa fila que publica aos poucos no canal Inema Espanhol.

- **Serve para:** VersÃµes EN/ES de explicativos, reels e aulas.
- **Formato:** 16:9 e 9:16 (igual ao original)
- **Avatar:** Sim â€” avatar e voz do Nei no idioma
- **Como Ã© acionado:** Terminal (sessÃ£o) + fila-espanhol com timer (1 vÃ­deo a cada 2 h, atÃ© 8 por dia)
- **RepositÃ³rio:** [github.com/inematds/explicavideos](https://github.com/inematds/explicavideos) Â· fila-espanhol: repositÃ³rio privado
- **Exemplos publicados:**
  - [REA: tu agente de IA sin trabas para adaptar programas en tu computadora](https://www.youtube.com/watch?v=S1uTys1xGnc) â€” Inema Espanhol, 17/10/2026, 16:9
  - [IA Cultivada: por quÃ© tu IA repite errores y cÃ³mo hacer que mejore](https://www.youtube.com/watch?v=hzuNcPqHOEI) â€” Inema Espanhol, 14/10/2026, 16:9
  - [Codex + Claude: uno planifica, el otro critica #Shorts](https://www.youtube.com/watch?v=L3-LqTC_qeI) â€” Inema Espanhol, 14/10/2026, 9:16

### Reels virais 9:16

#### âš¡ r7ex

Linha de produÃ§Ã£o de reels com roteiro de 7 etapas de gatilho, do gancho com nÃºmero ao pedido de comentÃ¡rio, e acabamento de telejornal: tÃ­tulo desenhado na abertura, painÃ©is no tempo da fala, contador e legenda que acende com a voz.

- **Serve para:** Reel viral de 40 a 50 segundos a partir de uma tese ou opiniÃ£o forte.
- **Formato:** 9:16
- **Avatar:** Sim â€” Nei em meia tela no gancho, depois no canto (HeyGen)
- **Como Ã© acionado:** Terminal (/r7ex) ou bot: /r7ex <tema> no inemaccbot; publicaÃ§Ã£o por fila com timer
- **RepositÃ³rio:** [github.com/inematds/r7ex](https://github.com/inematds/r7ex)
- **Exemplos publicados:**
  - [Para de criar app de IA: os 13 negÃ³cios com IA do pior ao melhor #shorts](https://www.youtube.com/watch?v=9xtleXd3Kaw) â€” INEMA FTD, 08/11/2026, 9:16
  - [Seu prompt nÃ£o Ã© cadeado: 5 travas para o agente de IA #shorts](https://www.youtube.com/watch?v=CxjmcmF-GWg) â€” INEMA Tec, 08/11/2026, 9:16
  - [Ex-chefe do Google avisa: NÃƒO estamos prontos para a IA #shorts](https://www.youtube.com/watch?v=0VdykM91Gzw) â€” INEMA Futuros, 08/11/2026, 9:16

#### ðŸ§© rtex

Reel de "N peÃ§as": um tema por vÃ­deo, gancho forte no quadro de abertura, os passos do mÃ©todo e, no fim, uma pergunta de opiniÃ£o para o pÃºblico responder. Validador, crÃ­tico automÃ¡tico e QA conferem o formato antes de publicar.

- **Serve para:** Reel de mÃ©todo ou lista ("as 3 peÃ§as deâ€¦") que puxa comentÃ¡rio.
- **Formato:** 9:16 (60â€“90 s)
- **Avatar:** Sim â€” avatar do Nei pelo estÃºdio HeyGen
- **Como Ã© acionado:** Terminal ou bot: /rtex <tema> no inemaccbot; fila com timer
- **RepositÃ³rio:** [github.com/inematds/rtex](https://github.com/inematds/rtex)
- **Exemplos publicados:**
  - [Seu design virou colagem: coloque critÃ©rio antes do efeito #shorts](https://www.youtube.com/watch?v=DLPw-sI_TJI) â€” INEMA FTD, 09/11/2026, 9:16
  - [Pare de pedir slide assim pro Claude: 3 peÃ§as pra ter a sua cara #shorts](https://www.youtube.com/watch?v=mz2WjAoNwok) â€” INEMA Tec, 06/11/2026, 9:16
  - [Pare de disparar em volume para lista fria: prospecte por sinal com IA #shorts](https://www.youtube.com/watch?v=dydHb8BkkJk) â€” INEMA TDS, 05/11/2026, 9:16

#### ðŸ–Œï¸ rtexjp

Monta reels ilustrados em azul-marinho a partir de um roteiro.json: gera a voz no prÃ³prio computador, desenha cada cena, mistura a trilha e confere sozinho o formato. Sem gravar e sem serviÃ§o de avatar pago.

- **Serve para:** Reel no padrÃ£o rtex quando nÃ£o hÃ¡ avatar gravado: tudo ilustrado.
- **Formato:** 9:16
- **Avatar:** Personagem ilustrado do Nei (sem HeyGen), voz local
- **Como Ã© acionado:** Terminal ou bot: /rtexjp <tema> no inemaccbot
- **RepositÃ³rio:** [github.com/inematds/rtexjp](https://github.com/inematds/rtexjp)
- **Exemplos publicados:**
  - [VocÃª paga 200 dÃ³lares. A IA custa atÃ© 5 mil. #shorts](https://www.youtube.com/watch?v=UKqxVXTDVfI) â€” INEMA TDS, 05/11/2026, 9:16
  - [E se a China fechar a torneira da IA grÃ¡tis? #shorts](https://www.youtube.com/watch?v=78O5l2Coiv4) â€” INEMA TDS, 05/11/2026, 9:16
- Por enquanto, sÃ³ 2 exemplos encontrados no histÃ³rico.

#### 7ï¸âƒ£ reel7etapas (antecessor do r7ex)

O primeiro modelo de reel em 7 etapas de gatilho (gancho, desejo, medo, facilidade, descoberta, benefÃ­cio, comentÃ¡rio), com uma imagem por etapa e montagem em Python. Desde 18/10/2026 o padrÃ£o Ã© o r7ex; o repositÃ³rio guarda o motor antigo e o histÃ³rico.

- **Serve para:** ReferÃªncia do roteiro de 7 etapas; reels novos saem pelo r7ex.
- **Formato:** 9:16
- **Avatar:** Sim â€” avatar do Nei (HeyGen)
- **Como Ã© acionado:** Terminal (/reel7etapas) â€” substituÃ­do pelo r7ex
- **RepositÃ³rio:** [github.com/inematds/reel7etapas](https://github.com/inematds/reel7etapas)
- **Exemplos publicados:**
  - [Vem aÃ­ demissÃ£o em massa de gerentes? A IA vai cobrar preparo #shorts](https://www.youtube.com/watch?v=xpDV5qQe5oE) â€” INEMA FTD, 18/10/2026, 9:16
- Motor antigo: o exemplo mostra o padrÃ£o anterior, que levou ao r7ex. Para ver o formato atual, veja os exemplos do r7ex.

### Radares diÃ¡rios automÃ¡ticos

#### ðŸ’° finviral

Assiste por transcriÃ§Ã£o aos vÃ­deos dos maiores influenciadores de finanÃ§as, separa nÃºmeros, fatos e polÃªmicas e monta um vÃ­deo com nÃºmeros grandes animados, a fonte de cada dado na tela e o Nei comentando. Sem recomendaÃ§Ã£o de investimento.

- **Serve para:** Resumo diÃ¡rio do que se falou de finanÃ§as; no fim de semana, "A semana explicada".
- **Formato:** 9:16 diÃ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim â€” Nei comentando (HeyGen)
- **Como Ã© acionado:** Timer: segunda a sexta 02:00, balanÃ§o no sÃ¡bado
- **RepositÃ³rio:** [github.com/inematds/finviral](https://github.com/inematds/finviral)
- **Exemplos publicados:**
  - [US$ 3 trilhÃµes somem de Wall Street: a bolha da IA vai estourar?](https://www.youtube.com/watch?v=lVnzzTdXz9I) â€” INEMA TIA, 09/11/2026, 9:16
  - [Selic parada em 13,75%: o que esperar atÃ© dezembro, explicado](https://www.youtube.com/watch?v=pZ2ZCs_Udyo) â€” INEMA TIA, 08/11/2026, 16:9
  - [Financiamento de imÃ³vel vai de 11% a 15% apÃ³s a eleiÃ§Ã£o: o que muda](https://www.youtube.com/watch?v=4x2j7Xbq5ng) â€” INEMA TIA, 06/11/2026, 9:16

#### ðŸ©º saudeviral

O mesmo radar para mÃ©dicos, nutricionistas e psicÃ³logos de maior audiÃªncia: tudo relatado e atribuÃ­do, e o que nÃ£o tem consenso na medicina sai com o carimbo "SEM CONSENSO". NÃ£o substitui consulta mÃ©dica.

- **Serve para:** Resumo diÃ¡rio do que os influenciadores de saÃºde disseram.
- **Formato:** 9:16 diÃ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim â€” Nei comentando (HeyGen)
- **Como Ã© acionado:** Timer: segunda a sexta 05:00, balanÃ§o no sÃ¡bado
- **RepositÃ³rio:** [github.com/inematds/saudeviral](https://github.com/inematds/saudeviral)
- **Exemplos publicados:**
  - [Seu tipo sanguÃ­neo muda o risco de cÃ¢ncer? O radar da saÃºde](https://www.youtube.com/watch?v=fN8iKWuTbmg) â€” INEMA TIA, 09/11/2026, 9:16
  - [Borderline, luto do vivo e 1.800 degraus | A semana explicada](https://www.youtube.com/watch?v=xgvdLWqTtQw) â€” INEMA TIA, 08/11/2026, 16:9
  - [Luto de quem estÃ¡ vivo, borderline e a gema do ovo: a semana da saÃºde](https://www.youtube.com/watch?v=BC4_4tpDUYE) â€” INEMA TIA, 08/11/2026, 9:16

#### âš–ï¸ advviral

Radar do que os maiores advogados do YouTube disseram sobre direitos: consumidor, previdÃªncia, trabalho, dÃ­vidas, imÃ³vel, famÃ­lia e golpes. Nada vira conselho para o seu caso, e proposta de lei Ã© chamada de proposta.

- **Serve para:** Resumo diÃ¡rio de direitos, em linguagem simples.
- **Formato:** 9:16 diÃ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim â€” Nei comentando (HeyGen)
- **Como Ã© acionado:** Timer: segunda a sexta 08:00, balanÃ§o no sÃ¡bado
- **RepositÃ³rio:** [github.com/inematds/advviral](https://github.com/inematds/advviral)
- **Exemplos publicados:**
  - [Processos contra o INSS mais que dobraram: por que tanta gente vai Ã  JustiÃ§a](https://www.youtube.com/watch?v=TE9-6B4NbxM) â€” INEMA TIA, 09/11/2026, 9:16
  - [Ataque hacker de US$ 49 mi Ã  cripto: quem paga? | A semana explicada](https://www.youtube.com/watch?v=glv2cyDDECc) â€” INEMA TIA, 08/11/2026, 16:9
  - [Aposentadoria com 15 anos paga sÃ³ 60% da mÃ©dia, e mais 4 direitos](https://www.youtube.com/watch?v=pB4iDtByzyc) â€” INEMA TIA, 07/11/2026, 16:9

#### âš½ futviral

Resumo do que os 10 maiores canais de futebol disseram: BrasileirÃ£o, futebol europeu, mercado da bola e negÃ³cios, com carimbos (RUMOR, NEGOCIANDO, FECHADO, POLÃŠMICA). Rumor Ã© tratado como rumor e aposta nÃ£o entra.

- **Serve para:** Radar diÃ¡rio de futebol.
- **Formato:** 9:16 diÃ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim â€” Nei comentando (HeyGen)
- **Como Ã© acionado:** Timer: gera Ã s 9h, publica ao meio-dia
- **RepositÃ³rio:** [github.com/inematds/futviral](https://github.com/inematds/futviral)
- **Exemplos publicados:**
  - [GrÃªmio na zona de rebaixamento e na final de R$ 78 milhÃµes](https://www.youtube.com/watch?v=7VM2auexshA) â€” Inema Club24, 09/11/2026, 9:16
  - [FUTVIRAL: Flamengo pode ser campeÃ£o no Allianz e Vasco decide hoje](https://www.youtube.com/watch?v=d-J-JeG8dTU) â€” Inema Club24, 08/11/2026, 9:16
  - [Flamengo a 2 vitÃ³rias do tÃ­tulo no Allianz? A semana explicada](https://www.youtube.com/watch?v=aVWqhfVehwA) â€” Inema Club24, 08/11/2026, 16:9

#### ðŸ§¾ contaviral

Resumo do que os 10 maiores canais de contabilidade e tributos disseram: leis e portarias, Reforma TributÃ¡ria, MEI e Simples, imposto de renda e obrigaÃ§Ãµes fiscais, com carimbos (MUDOU A REGRA, PROPOSTA, PRAZO, ALERTA).

- **Serve para:** Radar diÃ¡rio contÃ¡bil e tributÃ¡rio.
- **Formato:** 9:16 diÃ¡rio + 16:9 longo no fim de semana
- **Avatar:** Sim â€” Nei comentando (HeyGen)
- **Como Ã© acionado:** Timer: gera Ã s 10h, publica Ã s 13h
- **RepositÃ³rio:** [github.com/inematds/contaviral](https://github.com/inematds/contaviral)
- **Exemplos publicados:**
  - [PerdÃ£o do MEI: quem parcelou pode parar? E o Seletivo sÃ³ em fevereiro](https://www.youtube.com/watch?v=0EG5d9CgNLo) â€” INEMA TIA, 09/11/2026, 9:16
  - [CBS a 11,34%? A alÃ­quota que assustou e o que mais mudou na semana](https://www.youtube.com/watch?v=noBpqjKgdNQ) â€” INEMA TIA, 08/11/2026, 9:16
  - [CBS de 11,34%, inflaÃ§Ã£o e perdÃ£o do MEI: a semana contÃ¡bil explicada](https://www.youtube.com/watch?v=qsYlEy48vaY) â€” INEMA TIA, 08/11/2026, 16:9

### Outras linhas e sÃ©ries

#### ðŸŒªï¸ eventosextremospub (clima)

Transforma alertas de tempo severo num vÃ­deo de "sala de crise": baixa dados pÃºblicos (alertas do INMET por municÃ­pio, satÃ©lite GOES-19, previsÃ£o do Open-Meteo), anima tudo num mapa 3D do Sul do Brasil e mostra a fonte de cada nÃºmero.

- **Serve para:** Clima do dia, previsÃ£o e alertas da semana.
- **Formato:** 9:16
- **Avatar:** Sim â€” Nei pelo estÃºdio HeyGen
- **Como Ã© acionado:** Timers ao longo do dia (Clima 24 h, PrevisÃ£o do Dia, Clima do DIA, alertas)
- **RepositÃ³rio:** [github.com/inematds/eventosextremospub](https://github.com/inematds/eventosextremospub)
- **Exemplos publicados:**
  - [O clima no mundo 09/11: duna cai sobre barracas em Gaza, enxurrada no Iraque #Shorts](https://www.youtube.com/watch?v=i11SMouAllE) â€” Eventos Extremos INEMA, 09/11/2026, 9:16
  - [654 cidades em alerta de tempestade amanhÃ£ Â· Alerta da semana 09/11 #Shorts](https://www.youtube.com/watch?v=E8xsGn0xRXQ) â€” Eventos Extremos INEMA, 09/11/2026, 9:16
  - [Clima do dia 09/11: geada em novembro e 0,8 Â°C na serra catarinense #Shorts](https://www.youtube.com/watch?v=eN05Dt_jM0M) â€” Eventos Extremos INEMA, 09/11/2026, 9:16

#### ðŸ‘€ Vigia de canal

Todo dia olha um canal de referÃªncia; se houver vÃ­deo novo, faz um explicavideo inspirado no conteÃºdo, na voz do Nei, e publica direto. Sem vÃ­deo novo, nÃ£o faz nada, e nunca repete um vÃ­deo.

- **Serve para:** Explicativos automÃ¡ticos, sem ninguÃ©m pedir, quando sai conteÃºdo novo na referÃªncia.
- **Formato:** 16:9 + 9:16 (menos de 2 min)
- **Avatar:** Sim â€” avatar e voz do Nei
- **Como Ã© acionado:** Timer diÃ¡rio Ã s 14h
- **RepositÃ³rio:** repositÃ³rio privado
- **Exemplos publicados:**
  - [5 palavras e o projeto no ar: por que o prompt curto funciona melhor #shorts](https://www.youtube.com/watch?v=Lw-LdQiyUpA) â€” INEMA LOOPY, 07/11/2026, 9:16
  - [Prompt de 5 palavras e zero cÃ³digo: 7 hÃ¡bitos de quem estÃ¡ no topo da IA](https://www.youtube.com/watch?v=T6d1k8fgVHQ) â€” INEMA LOOPY, 07/11/2026, 16:9
  - [A IA desligou 25 apps da TV e achou um minerador escondido: 3 usos que quase ninguÃ©m faz](https://www.youtube.com/watch?v=hageCcHOcLE) â€” INEMA LOOPY, 06/11/2026, 9:16

#### ðŸ™ï¸ historia-timelapse

Timelapse 3D da histÃ³ria de uma cidade: relevo real, prÃ©dios do OpenStreetMap nascendo no ano em que o bairro foi ocupado, contador de populaÃ§Ã£o do IBGE e cartÃµes com nÃºmero, explicaÃ§Ã£o e fonte.

- **Serve para:** HistÃ³ria de cidades em vÃ­deo; sai em fases (sÃ³ mÃºsica, narrada, com avatar).
- **Formato:** 16:9
- **Avatar:** Opcional â€” fase 3 com avatar do Nei
- **Como Ã© acionado:** Terminal (skill historia-timelapse); fila de publicaÃ§Ã£o
- **RepositÃ³rio:** [github.com/inematds/historia-timelapse](https://github.com/inematds/historia-timelapse)
- **Exemplos publicados:**
  - [Porto Alegre de 1772 a 2024: 252 anos em um timelapse 3D com luz realista](https://www.youtube.com/watch?v=WzPVdaal1OY) â€” Aventuras INEMA, 24/10/2026, 16:9
  - [O centro de ItaguaÃ­ em 3D: da Matriz de 1729 Ã  cidade do futuro](https://www.youtube.com/watch?v=dalR1xWPFlE) â€” Aventuras INEMA, 23/10/2026, 16:9
  - [Rio de Janeiro de 1500 a 2024: 524 anos de histÃ³ria em timelapse 3D](https://www.youtube.com/watch?v=Ij4KsTN_SB0) â€” Aventuras INEMA, 23/10/2026, 16:9

#### ðŸ”ï¸ aventurasinemavideo (MemÃ³rias de Aventura)

Transforma matÃ©rias reais do acervo do INEMA Aventura (2001 a 2012), com o relato e as fotos dos prÃ³prios aventureiros, em filmes narrados de 1 a 3 minutos: fotos restauradas com movimento e narraÃ§Ã£o na voz do Nei.

- **Serve para:** A sÃ©rie MemÃ³rias de Aventura.
- **Formato:** 16:9
- **Avatar:** NÃ£o â€” fotos do acervo + narraÃ§Ã£o
- **Como Ã© acionado:** Terminal / lote, com publicaÃ§Ã£o no canal Aventuras INEMA
- **RepositÃ³rio:** [github.com/inematds/aventurasinemavideo](https://github.com/inematds/aventurasinemavideo)
- **Exemplos publicados:**
  - [Beto Monteiro vence sob calor de 35Â°C na FÃ³rmula Truck | MemÃ³rias de Aventura #166](https://www.youtube.com/watch?v=vjsykS5_9HU) â€” Aventuras INEMA, 09/11/2026, 16:9
  - [Allam Khodair: de 4Âº a vencedor na Stock Car 2010 | MemÃ³rias de Aventura #165](https://www.youtube.com/watch?v=PLPcwWAQgqE) â€” Aventuras INEMA, 09/11/2026, 16:9
  - [De Curitiba ao Alasca de moto: 34 mil km em 1997 | MemÃ³rias de Aventura #164](https://www.youtube.com/watch?v=iqrvHLIET2Y) â€” Aventuras INEMA, 09/11/2026, 16:9

#### ðŸ”¥ gitbombando

Todo dia faz o reel "Bombando no GitHub": os 10 projetos que mais ganharam estrelas, em contagem regressiva, com cartÃ£o, foto do dono, o que faz em portuguÃªs simples e o nÃºmero de estrelas. TambÃ©m gera dois carrossÃ©is.

- **Serve para:** Novidades do GitHub Trending em 1 minuto.
- **Formato:** 9:16
- **Avatar:** Sim â€” avatar do Nei (HeyGen)
- **Como Ã© acionado:** Timer: gera Ã s 9h, publica Ã s 11h
- **RepositÃ³rio:** [github.com/inematds/gitbombando](https://github.com/inematds/gitbombando)
- **Exemplos publicados:**
  - [CaÃ§a-apelidos dispara ao topo do GitHub com +4.294 estrelas em um dia #Shorts](https://www.youtube.com/watch?v=W3Mds0R28_A) â€” INEMA Tec, 09/11/2026, 9:16
  - [Cloudflare segue no topo e um caÃ§a-apelidos invade o pÃ³dio: +2.085 estrelas no GitHub #Shorts](https://www.youtube.com/watch?v=vXoQJMnVT1w) â€” INEMA Tec, 08/11/2026, 9:16
  - [17.100 estrelas em 7 dias: o controle remoto de todas as IAs lidera o GitHub #Shorts](https://www.youtube.com/watch?v=3FXsmsRC0YA) â€” INEMA Tec, 08/11/2026, 9:16

### VÃ­deo feito em cÃ³digo (sem cÃ¢mera)

#### ðŸ’» video-codigo

Skill para o Claude Code e o Codex em que cada quadro Ã© escrito em cÃ³digo (HTML, Canvas ou SVG) e vira MP4. A voz, quando hÃ¡, Ã© gerada no computador e cada imagem entra no instante da palavra.

- **Serve para:** LanÃ§amento, anÃºncio, explicativo ou filme de produto sem cÃ¢mera e sem editor.
- **Formato:** 16:9 e 9:16 do mesmo projeto
- **Avatar:** NÃ£o (rosto opcional, atÃ© meia tela)
- **Como Ã© acionado:** Terminal (skill no Claude Code ou Codex)
- **RepositÃ³rio:** [github.com/inematds/video-codigo](https://github.com/inematds/video-codigo)
- **Exemplos publicados:**
  - [Lead que espera esfria: do WhatsApp Ã  venda em 1 minuto, feito com cÃ³digo #Shorts](https://www.youtube.com/watch?v=4ILX66Hddtk) â€” INEMA FTD, 06/11/2026, 9:16
  - [Do WhatsApp Ã  venda: filme de produto feito 100% com cÃ³digo](https://www.youtube.com/watch?v=tWv1mEIK62c) â€” INEMA FTD, 06/11/2026, 16:9
- Por enquanto, sÃ³ 2 exemplos encontrados no histÃ³rico.

#### ðŸª reel-ciencia-3d

Kit com skill para o Claude Code que transforma uma pergunta "E seâ€¦?" num reel de ciÃªncia de cerca de 60 segundos, feito sÃ³ com cÃ³digo (HyperFrames e Three.js), com a fonte de cada nÃºmero e voz local.

- **Serve para:** DivulgaÃ§Ã£o cientÃ­fica em vÃ­deo curto, sem errar nÃºmero.
- **Formato:** 9:16 (~60 s)
- **Avatar:** NÃ£o
- **Como Ã© acionado:** Terminal (skill no Claude Code)
- **RepositÃ³rio:** [github.com/inematds/reel-ciencia-3d](https://github.com/inematds/reel-ciencia-3d)
- **Exemplos publicados:**
  - [E se o Sol sumisse agora? AnimaÃ§Ã£o 3D feita sÃ³ com cÃ³digo](https://www.youtube.com/watch?v=FDtJim4xHjY) â€” INEMA FTD, 06/11/2026, 9:16
  - [E se a Lua sumisse? AnimaÃ§Ã£o 3D feita sÃ³ com cÃ³digo](https://www.youtube.com/watch?v=nUsGrdZ-8MY) â€” INEMA FTD, 06/11/2026, 9:16
  - [E se a Terra nÃ£o tivesse inclinaÃ§Ã£o? AnimaÃ§Ã£o 3D feita sÃ³ com cÃ³digo](https://www.youtube.com/watch?v=BmSeV6r0FdQ) â€” INEMA FTD, 06/11/2026, 9:16

#### ðŸŽ™ï¸ video-sem-rosto

Kit que ensina o Claude Code a fazer explicativos na horizontal sem gravar nada: voz clonada gerada no computador, a pÃ¡gina real do site, imagens 3D e legenda sincronizada.

- **Serve para:** Explicar uma ferramenta, um repositÃ³rio ou uma novidade sem aparecer.
- **Formato:** 16:9
- **Avatar:** NÃ£o
- **Como Ã© acionado:** Terminal (skill no Claude Code)
- **RepositÃ³rio:** [github.com/inematds/video-sem-rosto](https://github.com/inematds/video-sem-rosto)
- Ainda sem vÃ­deo publicado no YouTube por este motor; os vÃ­deos de demonstraÃ§Ã£o estÃ£o no guia do projeto.

#### ðŸŽ“ videos-cursos-inema

Motor que transforma um curso INEMA (site estÃ¡tico) numa sÃ©rie de vÃ­deos narrados e animados, em trÃªs partes selecionÃ¡veis: landing, um vÃ­deo por trilha e uma aula completa por mÃ³dulo.

- **Serve para:** VÃ­deos de divulgaÃ§Ã£o e aulas de um curso.
- **Formato:** 16:9 (e 9:16 com --vertical)
- **Avatar:** NÃ£o â€” narraÃ§Ã£o com voz clonada local
- **Como Ã© acionado:** Terminal (skill videos-cursos-inema)
- **RepositÃ³rio:** [github.com/inematds/videos-cursos-inema](https://github.com/inematds/videos-cursos-inema)
- Nenhum vÃ­deo deste motor aparece no histÃ³rico de publicaÃ§Ãµes; o guia do projeto mostra o exemplo do curso FEP.

### Apoio

#### ðŸ”Š inemavox

SuÃ­te de voz com IA local que todos os motores usam por baixo: baixa vÃ­deos, transcreve, gera voz (TTS), dubla e corta, com os modelos rodando na placa de vÃ­deo, sem custo de API.

- **Serve para:** Voz, transcriÃ§Ã£o, download e mÃºsica/efeitos para os outros motores.
- **Como Ã© acionado:** Terminal (scripts) ou API local
- **RepositÃ³rio:** [github.com/inematds/inemavox](https://github.com/inematds/inemavox)
- Motor de apoio: nÃ£o publica vÃ­deo prÃ³prio.

## O processo, do inÃ­cio ao fim

ðŸ§  = sessÃ£o com o Nei Â· âš™ï¸ = script (sem gastar tokens) Â· ðŸ¤– = `claude -p`

1. ðŸ§  Motor novo ou mudanÃ§a de texto: editar `catalogo.json` (texto em PT, regra que identifica os vÃ­deos, `excluir`/`fixar`).
2. âš™ï¸ `python3 traduzir.py` â€” traduz para EN/ES sÃ³ as chaves novas, pelo tradutor central `inema-traduz`, e grava `i18n/en.json` e `i18n/es.json`.
3. âš™ï¸ `python3 atualizar-exemplos.py` â€” lÃª o histÃ³rico do yt-pubx (`~/.local/share/yt-pubx/historico.jsonl`) e, se existir, o registro de produÃ§Ãµes (separa explicavideo de refazvideo); escolhe atÃ© 3 vÃ­deos pÃºblicos, recentes e variados por motor e grava `motores.json`.
4. âš™ï¸ O mesmo comando roda `python3 gerar.py`, que regrava `README.md`, `README.en.md`, `README.es.md` e `guia/index.html`, `guia/en/`, `guia/es/` a partir do `motores.json`.
5. ðŸ§  Conferir a pÃ¡gina e o README; `git push`. O GitHub Pages (Actions) publica a partir da branch `main`.

Fora da mÃ¡quina que publica os vÃ­deos nÃ£o existe o histÃ³rico do yt-pubx: o script avisa, mantÃ©m os exemplos que jÃ¡ estÃ£o no `motores.json` e sÃ³ aplica os textos novos. Os exemplos nÃ£o sÃ£o reconferidos no YouTube: o script sÃ³ lÃª arquivos locais. VÃ­deo reprovado ou trocado entra em `excluir` no `catalogo.json`.

## Arquivos

| | |
|---|---|
| `catalogo.json` | fonte editada Ã  mÃ£o: textos dos motores, canais, regras de identificaÃ§Ã£o |
| `motores.json` | dados do Ã­ndice gerados pelo script (motores + exemplos) |
| `atualizar-exemplos.py` | relÃª o histÃ³rico e regrava o motores.json |
| `gerar.py` | gera os READMEs e o guia a partir do motores.json |
| `traduzir.py` | traduz os textos novos para EN/ES (inema-traduz) |
| `i18n/` | textos da pÃ¡gina e dos motores em PT, EN e ES |

## LicenÃ§a

MIT. Projeto do [INEMA.CLUB](https://inema.club).

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>