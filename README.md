# Busca de candidatos no LinkedIn comum (para quem não tem o recruiter)

Skill em português para Claude. Cole o briefing de uma vaga e receba três buscas prontas para copiar, os filtros de localização e um ajuste para quando aparecerem poucos perfis ou perfis fora do escopo.

## Instalação no Claude

Baixe o arquivo [busca-linkedin.zip](./busca-linkedin.zip). Em Claude, abra **Customize → Skills → + → Create skill → Upload a skill**, envie esse ZIP e ative a skill.

Para editar as instruções, abra [SKILL.md](./busca-linkedin/SKILL.md). Após editar, compacte novamente a pasta busca-linkedin para atualizar o arquivo de instalação.

## Teste com uma vaga fictícia

> Monte uma busca para analista de e-commerce presencial em Uberlândia. Precisa ter operado marketplace. Shopify é diferencial. Quero começar com precisão.

| Rodada | Consulta sugerida |
| --- | --- |
| Precisa | `"analista de e-commerce" AND marketplace AND Shopify` |
| Equilibrada | `("analista de e-commerce" OR "analista de marketplace") AND marketplace` |
| Ampla | `marketplace` |

Cole uma linha por vez na pesquisa, selecione **Pessoas** e aplique **Uberlândia** em **Localizações**. Comece pela precisa. Se o volume for baixo, a equilibrada retira o diferencial Shopify. Na ampla, confira se a pessoa operou um canal de vendas. O termo também pode aparecer em perfis de tecnologia ou atendimento.

## Referências

- [Pesquisa booleana no LinkedIn](https://www.linkedin.com/help/linkedin/answer/a524335)
- [Filtro de localização do LinkedIn](https://www.linkedin.com/help/linkedin/answer/a522593)
- [Uso de skills no Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

## Para candidatos · Treine sua entrevista pelo método STAR

[Baixe a skill para Claude](./treino-entrevista-star.zip) e importe o ZIP em **Customize → Skills → + → Create skill → Upload a skill**. As [instruções da skill](./treino-entrevista-star/SKILL.md) também estão disponíveis para leitura.

Para começar, escreva: “Vou entrevistar para uma vaga de suporte técnico. Quero treinar três histórias reais pelo método STAR. Faça uma pergunta por vez.” Você também pode colar a descrição da vaga. A cada rodada, conte sua experiência, receba feedback e tente de novo usando quatro lembretes.
