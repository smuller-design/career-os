# Career OS — marketplace

Catálogo de plugins do **Career OS**: um sistema que transforma o que você faz no dia a dia em evidência de impacto, quase sozinho — para PDI, avaliação e promoção. Baseado no "brag document" da Julia Evans + IA + rotinas automáticas.

## Plugins neste catálogo

- **`career-os-kit`** — monta o Career OS do zero (wizard de setup + templates + prompts das 2 rotinas) e inclui o espelho de PDI em tempo real (`pdi-demand-checker`).

## Como instalar

Há dois caminhos. Escolha pelo seu conforto:

### A) Jeito mais simples (recomendado pro time de design) — arquivo `.plugin`
Peça o arquivo `career-os-kit.plugin`, abra no Cowork e clique em instalar no card. Sem GitHub, sem comando.

### B) Via este marketplace (pra quem usa Claude Code / quer receber atualizações do catálogo)
Este repositório é **privado** — você precisa ter acesso a ele no GitHub.

```bash
claude plugin marketplace add smuller-design/<nome-do-repo>
claude plugin install career-os-kit@career-os
```

Depois de instalar, abra um projeto novo "Career OS" e rode `monte meu Career OS` pra o wizard montar tudo. Veja os 3 passos no README do plugin (`plugins/career-os-kit/README.md`).

## Atualizações

Quando um plugin deste catálogo for atualizado, quem instalou via marketplace recebe a nova versão do catálogo. **Atenção:** os docs que a pessoa já criou no projeto dela e as 2 rotinas já coladas **não se atualizam sozinhos** — pra pegar uma melhoria, rode o wizard de novo ou peça pro Claude aplicar a mudança.

---

_Mantido por Sara Muller · time de design (+A)._
