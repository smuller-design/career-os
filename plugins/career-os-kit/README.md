# Career OS Kit

Um sistema que transforma o que você faz no dia a dia em **evidência de impacto**, quase sozinho — para PDI, avaliação e promoção. Baseado no "brag document" da Julia Evans + IA + rotinas automáticas.

Este plugin empacota tudo que antes eram "vários arquivos e muitos passos" numa instalação só.

## O que vem dentro

- **Skill `career-os-setup`** — o wizard. Você roda **uma vez** e ele monta o sistema inteiro pra você: cria os docs no seu projeto, te entrevista pra montar o Mapa de Competências com a sua calibração e as suas 3 jogadas do ciclo, e te guia a ligar o conector e criar as 2 rotinas.
- **Skill `pdi-demand-checker`** — um espelho de PDI em tempo real: no meio de uma demanda, te diz se você está mirando os seus pontos e te dá um empurrão pra fechar o ciclo / dar visibilidade.
- **Templates + prompts das rotinas** — viajam dentro do wizard; você não precisa copiar nada à mão.

## Como instalar e montar (self-serve, ~3 passos)

1. **Instale o plugin** `career-os-kit`.
2. **Abra um projeto novo no Claude** chamado "Career OS" (é a casa do sistema — fica na nuvem pra rotina conseguir ler).
3. **Rode o wizard:** diga `monte meu Career OS` (ou use a skill `career-os-setup`). Ele vai:
   - criar os docs-base no projeto,
   - te pedir a sua calibração pra montar o Mapa (é o passo que faz o sistema mirar VOCÊ),
   - te ajudar a definir as 3 jogadas do ciclo,
   - te guiar a **conectar o Microsoft 365 / Google** e a criar as **2 rotinas** (semanal e mensal) na aba Rotinas.

Depois disso, o sistema roda quase sozinho. A sua parte: responder as perguntas em aberto e fazer as 3 jogadas.

## Pré-requisitos (por pessoa — não dá pra empacotar)

- Um **projeto do Claude** (a casa dos docs; dá memória ao sistema).
- O **conector** do seu trabalho ligado: **Microsoft 365** ou **Google Workspace** (e-mail, calendário, chat). É o que deixa a rotina varrer a semana sozinha. Sem ele, o sistema ainda funciona, mas você depende mais de largar coisas no Inbox.
- A sua **última calibração/avaliação** (notas e comentários por competência).

## A regra de ouro

As rotinas rodam em **sessões novas e isoladas**: leem os **docs do projeto** e o seu **e-mail/chat/calendário** — mas **não leem as suas conversas no Claude**. Um print ou transcrição que fica só num chat não é capturado. Se é importante, leve pro doc (cole no Inbox ou salve em Transcrições).

## Manutenção / atualização

Quando o plugin for atualizado, **novas instalações** e quem **rodar o setup de novo** pegam a versão nova. Os docs que você já criou no seu projeto **não se atualizam sozinhos** — se quiser a melhoria, rode o wizard de novo (ele detecta o que já existe) ou peça pro Claude aplicar a mudança. As 2 rotinas, como o prompt fica colado na sua tarefa agendada, também não atualizam sozinhas: o wizard mostra a versão atual do prompt quando você pedir.

---

_Conceito de brag document: Julia Evans (jvns.ca). Sistema "Career OS" montado em cima disso com IA + rotinas._
