# Pós-Tech AI Scientist — FIAP

Meu percurso na pós-graduação **AI Scientist** da FIAP, organizado por fase.
Cada fase reúne meus notebooks de estudo das disciplinas e o Tech Challenge,
o projeto avaliativo da fase.

> Os Tech Challenges vivem em repositórios próprios (a avaliação exige README
> na raiz) e aparecem aqui como submódulos em `fases/fase-N/tech-challenge`.
> O material didático original da FIAP não é publicado, apenas meus notebooks.

## Fases

| Fase | Disciplinas | Tech Challenge |
|------|-------------|----------------|
| [1](fases/fase-1) | Ambientes de trabalho · Análise exploratória · Estatística | [NPS Preditivo: drivers de satisfação em e-commerce](https://github.com/luiz-mota/tech-challenge-fase1) |
| [2](fases/fase-2) | Arquitetura de Big Data · Bancos relacionais · ETL · NoSQL | [Pipeline híbrido batch + streaming (Medalhão)](https://github.com/luiz-mota/tech-challenge-fase2) |
| [3](fases/fase-3) | ML supervisionado e não supervisionado · Aprendizado por reforço · Otimização e avaliação · Séries temporais | [Predição de alfabetização infantil (XGBoost + SHAP)](https://github.com/luiz-mota/tech-challenge-fase3) |
| [4](fases/fase-4) | Deep Learning · IA Generativa · LangChain · NLP | Voice of Customer com RAG *(em andamento)* |

## Estrutura

```
fases/
└── fase-N/
    ├── conteudo/        notebooks de estudo das disciplinas
    └── tech-challenge/  submódulo com o projeto da fase
```

Para clonar com os Tech Challenges:

```bash
git clone --recurse-submodules https://github.com/luiz-mota/pos-tech-ai-scientist.git
```
