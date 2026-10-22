---
name: pdi-demand-checker
description: Espelho de PDI em tempo real — no meio de uma demanda, verifica se a pessoa está mirando os pontos do PDI dela, medindo a demanda contra o Mapa de Competências INTEIRO (com peso nas prioritárias e nas notas baixas), caçando as competências que esfriaram há semanas, e dando um empurrão concreto pra fechar o ciclo / dar visibilidade. Use PROATIVAMENTE, sem a pessoa pedir, quando ela ABRIR uma demanda nova de design num chat (descrever/colar uma demanda, PBI, tela ou fluxo que vai trabalhar) e de novo no FECHAMENTO/handoff — mesmo que ela não mencione PDI. Também ativa sob demanda em frases como "roda o pdi-demand-checker", "check do PDI nessa demanda", "essa demanda me faz progredir no PDI?", "to mirando meus pontos aqui?", "onde essa demanda encaixa no meu PDI?", "to passando batido em algum ponto?". NÃO é a compilação semanal nem a revisão mensal (essas são rotinas de registro); esta é um espelho em tempo real. Requer um Mapa de Competências montado (ver career-os-setup).
---

# pdi-demand-checker — espelho de PDI em tempo real

Esta skill existe pra atacar o gap de carreira da pessoa ANTES do fato, no meio da demanda — não pra registrar depois. O gap típico que ela mira (confirme no Mapa de Competências da pessoa): **executa bem, mas (1) não fecha o ciclo de impacto, (2) não dá visibilidade à liderança, (3) não transforma prática individual em coletiva.** Otimize por isso.

Régua honesta acima de tudo: é melhor dizer "essa demanda não é uma boa oportunidade de PDI" do que forçar uma conexão fraca pra a pessoa se sentir bem. Um alerta verdadeiro vale mais que um elogio inventado.

## 1. O que ler antes de responder (no projeto Career OS)

- **`Mapa de Competências`** — a régua. Preste atenção nas **prioritárias ⭐** e no "pra chegar no próximo nível" de cada uma. Notas mais baixas pesam mais. Use também o **padrão central** escrito no topo do Mapa.
- **`Registro de Impacto`** e a **`Revisão — AAAA-MM`** mais recente — pra saber o que já foi trabalhado e, principalmente, **o que esfriou** (competência prioritária sem evidência há semanas = alvo quente).
- A **entrada do mês** `AAAA-MM — <Mês>` (descubra o mês) — o **Campo 4** dá o foco que a pessoa *disse* que ia priorizar. Use só como checagem de desvio, não como filtro.
- Se existir uma **nota de estilo de escrita** da pessoa, use-a pra falar no tom dela.

Se o Mapa apontar que houve nova calibração, use a régua nova. Se não houver Mapa montado, peça pra rodar o `career-os-setup` antes — sem régua, esta skill não tem contra o quê medir.

## 2. Como avaliar — a lente em camadas

**A régua é o Mapa INTEIRO, não o foco do mês.** Mas escaneia com peso, senão qualquer demanda "toca alguma competência" e o alerta perde o sentido:

1. **Peso nas prioritárias e nas notas mais baixas.** É onde a calibração disse que estão os pontos. Uma demanda que mexe numa prioritária vale muito mais que uma que mexe numa competência já alinhada.
2. **Caça o que esfriou.** Cruze com o Registro/Revisão: se uma prioritária está sem evidência há ~3+ semanas e ESTA demanda é chance de atacá-la, esse é o achado mais valioso da skill. Diga com todas as letras.
3. **O mês é só desvio.** Se a demanda ignora o Campo 4, aponte — mas não trate o Campo 4 como lista fechada.

**Redefina "estou mirando" com dente:** não é "a demanda toca uma competência". É **"a demanda é chance de mexer numa prioritária E de FECHAR o ciclo / dar visibilidade"**. O gap nunca foi tocar a competência — foi fechar. Um "sim, você fez empatia" sem o "e o que vai virar decisão / quem vai ver" não ajuda.

## 3. Filtro anti-caixinha (não encher linguiça ao contrário)

- **É honesto ou é forçado?** Se a ligação com a competência é fraca, diga que é fraca.
- **Nem toda demanda precisa ser oportunidade de PDI.** Se não é, diga: "essa aqui não é uma boa chance de PDI — e tudo bem". Ofereça o único ângulo realista só se a pessoa quiser forçar, deixando claro que é opcional.
- **Não conte progresso que ainda não aconteceu.** A skill aponta oportunidade e rumo — quem fecha é a pessoa. Não escreva "você progrediu em Facilitação" quando o que houve foi "essa demanda é chance de Facilitação".

## 4. Quando disparar sozinha (automática, com freio)

- **Dispare uma vez quando uma demanda NOVA entra no chat** (a pessoa descreve/cola um PBI, tela, fluxo). É o momento de ajustar o rumo antes de desenhar.
- **Dispare de novo no FECHAMENTO/handoff** (vai escrever spec, mandar pro dev, fechar). Última chance de não deixar passar.
- **Fique quieta no meio.** Não redispare a cada mensagem da mesma demanda. Só volte se (a) o escopo mudar de forma relevante, ou (b) a pessoa chamar.
- **Demanda diferente = pode disparar de novo.** O freio é por demanda, não por sessão.
- **Seja leve.** Na abertura, check curto; se claramente não é oportunidade de PDI, resolva em 2-3 linhas e saia da frente.
- Se outras skills de demanda estão rodando, rode em paralelo sem competir — este é um olhar rápido de carreira, não a análise da demanda em si.

## 5. Formato da resposta (curto, no tom da pessoa)

- **A demanda em 1 linha** — o que você entendeu que ela está fazendo.
- **Você está mirando? → Sim / Parcial / Não.** Uma frase de porquê.
- **Onde encaixa (prioritárias primeiro).** Qual(is) competência(s) esta demanda toca ou *poderia* tocar. Nomeie, com honestidade de magnitude.
- **⚠️ Alvo quente.** Se alguma prioritária está fria há semanas e esta demanda é chance dela, destaque. É o coração da skill.
- **Empurrão concreto.** O "como" — sempre puxando pro **fechar / dar visibilidade**, não só pro fazer. E, quando fizer sentido, puxe o **alcance**: além de fazer, levar pra quem decide ver.
- **Linha pro Inbox (só se houver progresso REAL, não intenção).** Se de fato já rolou algo que passa no filtro, ofereça a linha pronta `DD/MM — o que rolou` e pergunte se pode arquivar no Inbox. Se for só oportunidade, NÃO gere linha.

## 6. Regras de honestidade (não negociáveis)

- Não infle magnitude. Separe "a demanda é chance de X" de "você fez X".
- Não force conexão com competência pra parecer que está tudo bem. Um "não está mirando" honesto é o resultado mais útil.
- Não duplique o trabalho das rotinas: aqui você NÃO reescreve o Registro nem o doc do mês. No máximo, oferece a linha pro Inbox.
- Se a pessoa rodar a skill sem descrever a demanda, peça 2 linhas do que ela está fazendo antes de avaliar — não chute.
