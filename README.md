# collect-provas

Repositório destinado à coleção de provas da UPE Surubim.

Sinta-se à vontade para enviar as provas que tiver — você estará ajudando outros alunos, de qualquer período.

## Estrutura de pastas

```
sistemas-de-informacao/
├── 1-periodo/
│   ├── computacao-etica-e-sociedade/
│   │   └── computacao-etica-e-sociedade-p1-2023.2.pdf
│   ├── geometria-analitica/
│   │   └── geometria-analitica-p1-2023.2.pdf
│   └── programacao-1/
│       └── programacao-1-p2-2023.2.pdf
├── 2-periodo/
│   ├── calculo-1/
│   │   └── calculo-1-p1-2024.1.pdf
│   └── matematica-discreta/
│       └── matematica-discreta-p1-2024.1.pdf
├── 5-periodo/
│   ├── empreendedorismo-e-inovacao/
│   │   └── empreendedorismo-e-inovacao-p1-2025.2.pdf
│   ├── inteligencia-artificial/
│   │   └── inteligencia-artificial-p1-2025.2.pdf
│   ├── interacao-humano-computador/
│   │   └── interacao-humano-computador-p1-2025.2.pdf
│   └── sistemas-operacionais/
│       └── sistemas-operacionais-p1-2025.2.pdf
└── 6-periodo/
    └── computacao-grafica/
        └── computacao-grafica-p1-2026.1.pdf
```

### Convenção de nomes

```
[disciplina-slug]-[tipo-prova]-[semestre].pdf
```

Exemplos: `calculo-1-p1-2024.1.pdf`, `programacao-1-p2-2023.2.pdf`

- **disciplina-slug** — nome da disciplina em minúsculas com hífens
- **tipo-prova** — `p1`, `p2`, `p3`, `reposição`, etc.
- **semestre** — formato `AAAA.N` (ex.: `2024.1`, `2025.2`)

## Como contribuir (via Pull Request)

1. Faça um **fork** deste repositório.
2. Crie uma branch para sua contribuição:
   - `git checkout -b minha-contribuicao`
3. Adicione o arquivo de prova na pasta correta seguindo a estrutura acima.
   - Se a pasta da disciplina ainda não existir, crie-a dentro do período correspondente.
4. Faça commit das alterações:
   - `git add .`
   - `git commit -m "Adiciona prova de <disciplina> (ex: Cálculo I P1 2024.1)"`
5. Envie a branch para seu fork:
   - `git push origin minha-contribuicao`
6. Abra um **Pull Request** para este repositório explicando brevemente o que foi adicionado.

### Boas práticas

- Siga a convenção de nomes descrita acima.
- Evite arquivos duplicados.
- Não envie conteúdo com dados pessoais sensíveis.
