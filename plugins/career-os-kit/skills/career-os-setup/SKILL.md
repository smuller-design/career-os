---
name: career-os-setup
description: Monta o sistema Career OS para a pessoa do zero, num projeto do Claude — cria os docs-base a partir dos templates, entrevista a pessoa pra montar o Mapa de Competências com a calibração dela e as 3 jogadas do ciclo, e guia a conectar o Microsoft 365/Google e a criar as 2 rotinas (semanal e mensal). Use quando a pessoa disser "monte meu Career OS", "setup career os", "quero montar o career os", "configurar meu brag document", "montar meu sistema de carreira/PDI", ou quando ela instalou o career-os-kit e quer começar. Também use pra ATUALIZAR um Career OS já existente (detecta o que já tem). NÃO é a rotina semanal nem a mensal (essas rodam sozinhas depois); esta é o setup único, feito com a pessoa junto.
---

# career-os-setup — o wizard de montagem

Você está montando o Career OS de uma pessoa, do zero (ou atualizando). Conduza como um wizard: poucos passos, uma coisa de cada vez, em linguagem simples. O objetivo é transformar "vários arquivos e muitos passos" numa conversa guiada que entrega o sistema pronto.

**Tom:** direto, caloroso, concreto, sem jargão de implementação. Não fale de "arquivos markdown", "frontmatter" ou caminhos — fale do que o sistema vai fazer.

**Princípio de qualidade (o mais importante):** o que faz o sistema valer é o **Mapa de Competências preenchido com a calibração real** e **3 jogadas boas**. Seja chato de propósito nesses dois passos — não aceite jogada vaga ("melhorar storytelling") nem Mapa genérico. Se a pessoa tentar pular, explique que sem isso o sistema mede contra uma régua genérica e "não é efetivo". Todo o resto pode ser rápido; esses dois, não.

## Passo 0 — Onde isto está rodando (a casa do sistema)

A casa do Career OS é um **projeto do Claude na nuvem** — é lá que os docs vivem e é o que a rotina automática consegue ler (a rotina na nuvem não lê arquivos locais).

- Se você tem a ferramenta de projetos disponível (Cowork/claude.ai) e já está dentro de um projeto, use-o. Se não está num projeto, peça pra pessoa **criar um projeto chamado "Career OS"** e rodar você de dentro dele.
- Se você está no Claude Code (sem projeto na nuvem): explique que a parte "roda sozinho toda semana" precisa dos docs num projeto na nuvem; oriente a pessoa a criar o projeto no app do Claude e rodar o setup lá. Você pode criar os docs como arquivos locais se ela quiser coletar pelo Code, mas deixe claro que a rotina automática lê o projeto na nuvem.

Antes de criar qualquer doc, **cheque o que já existe** no projeto. Se já houver docs do Career OS, você está ATUALIZANDO: não sobrescreva cegamente — pergunte o que ela quer atualizar e preserve o conteúdo dela.

## Passo 1 — Criar os docs-base

Os templates estão em `references/templates/`. Crie no projeto da pessoa estes docs, a partir dos templates correspondentes (copie o conteúdo do template e grave como um doc novo no projeto):

- `Inbox — captura rápida` ← `templates/inbox.md`
- `Brag Document/Template` ← `templates/brag-do-mes.md`
- `O que depende de mim` ← `templates/o-que-depende-de-mim.md`
- `Mapa de Competências` ← `templates/mapa-de-competencias.md`
- `Registro de Impacto` ← `templates/registro-de-impacto.md`
- `Como funciona` ← `templates/como-funciona.md`
- a entrada do mês corrente `AAAA-MM — <Mês>` ← a partir de `templates/brag-do-mes.md` (4 campos vazios; descubra o mês atual)
- crie uma pasta/seção **Transcrições** (vazia por enquanto)

Troque os exemplos fictícios ("Marina") pelos dados reais conforme for preenchendo com a pessoa. Avise em uma linha que criou a base e que agora vêm os 2 passos que personalizam tudo.

## Passo 2 — Montar o Mapa de Competências (o passo que mira a pessoa)

Peça a **última calibração/avaliação** da pessoa — as notas por competência (auto × gestor, se tiver) e os comentários. Pode ser colada, anexada, ou ela conta e você estrutura.

Com isso:

1. Transcreva as competências no formato do Mapa (Competência | Nota | Status | o que fazer pra subir).
2. Marque ⭐ as **prioritárias** (as de nota mais baixa / as que mais pesam pra subir de nível).
3. Escreva, em 2-3 linhas, o **padrão central** — o gap que mais se repete na avaliação. Essa é a régua acima da régua; extraia dos comentários do gestor, não invente.

Se a pessoa não tiver a calibração à mão, não chute um Mapa genérico: faça uma entrevista curta (quais competências o seu papel cobra? onde o gestor disse que você precisa crescer? qual crítica se repete?) e marque que o Mapa é provisório até ela trazer a calibração real.

## Passo 3 — Objetivo do ciclo + as 3 jogadas

No doc `O que depende de mim`, preencha:

- **Objetivo do ciclo** (ex.: ser promovida, mudar de time, consolidar no nível) + a data do próximo ciclo de avaliação.
- **As 3 jogadas** que mais aproximam desse objetivo, **cada uma com data**. Exija concretude: uma jogada é uma ação específica que ataca uma competência prioritária E fecha ciclo / dá visibilidade — não "melhorar X". Se a pessoa der algo vago, devolva uma versão concreta e confirme. Puxe as jogadas do padrão central + das prioritárias do Mapa.

Explique: as rotinas vão cobrar **essas 3**, não a lista inteira. É isso que move o ponteiro.

## Passo 4 — Conectar o Microsoft 365 / Google

Explique que a rotina varre a semana sozinha via conector (e-mail, calendário, chat/Teams). Oriente a pessoa a **conectar o Microsoft 365 ou o Google** ao Claude. Se possível, verifique se o conector está ativo fazendo uma busca mínima (ex.: eventos da semana). Se não estiver conectado, avise que sem isso a rotina roda "cega" (só com o que estiver no Inbox) — e que vale conectar antes de seguir.

## Passo 5 — Criar as 2 rotinas

Os prompts estão em `references/rotina-semanal.md` e `references/rotina-mensal.md`. **Personalize-os** com o nome, o cargo/contexto e o objetivo do ciclo da pessoa (troque os `[colchetes]`). Depois:

- Entregue os dois prompts já preenchidos.
- Guie a pessoa a criar duas rotinas na aba **Rotinas → Nova rotina**: colar o prompt semanal (sugestão: sexta, fim de tarde) e o mensal (dia 1, de manhã).
- Oriente a deixar a **aprovação automática** ligada (pra rodar sem travar) e a rotina **ligada ao projeto "Career OS"**.
- Se você tiver ferramenta pra criar tarefas agendadas diretamente, ofereça criar por ela — mas confirme antes, e ainda assim mostre o prompt pra ela saber o que vai rodar.

## Passo 6 — Teste e fechamento

- Ofereça **rodar a rotina semanal uma vez** na hora pra testar. Se vier vazia, peça 2-3 linhas no Inbox e rode de novo.
- Reforce a **regra de ouro**: as rotinas leem os docs do projeto + e-mail/chat/calendário, mas **não leem as conversas no Claude**. O que é só de chat, levar pro doc.
- Feche dizendo, em linguagem simples, qual é a parte dela daqui pra frente: responder as perguntas em aberto e fazer as 3 jogadas. O sistema cuida do resto.

## Lembretes

- Uma coisa de cada vez. Não despeje os 6 passos de uma vez.
- Não exponha detalhes técnicos a menos que perguntem.
- Não invente dados da pessoa (calibração, jogadas). Pergunte.
- Preserve conteúdo existente ao atualizar.
