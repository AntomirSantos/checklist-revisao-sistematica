# Checklist para Revisões Sistemáticas e Meta-análises

Checklist interativo de condução de revisões sistemáticas, organizado a partir da estrutura do **Cochrane Handbook for Systematic Reviews of Interventions (v6)** e da checklist **PRISMA 2020**.

São **63 itens em 9 estágios**, do protocolo à submissão. Serve para revisões de intervenção com ou sem meta-análise.

## Como usar

Abra o `index.html` no navegador. Não precisa de servidor, instalação ou conexão: é um único arquivo estático.

- Marque os itens conforme avança. O progresso fica salvo no `localStorage` do navegador.
- O botão **limpar** zera as marcações. Use ao iniciar uma revisão nova.
- O selo laranja **ATENÇÃO** marca os pontos que revisores mais costumam cobrar.

Nenhum dado sai do navegador. Não há servidor, analytics ou requisição externa além das fontes do Google Fonts.

## Os nove estágios

| # | Estágio | Capítulos do Handbook |
|---|---------|----------------------|
| 1 | Preparação e escopo | 1–2 |
| 2 | Critérios de elegibilidade e protocolo | 3 |
| 3 | Busca | 4 |
| 4 | Seleção dos estudos | 4 |
| 5 | Coleta de dados | 5 |
| 6 | Risco de viés | 7–8, 25 |
| 7 | Preparação para a síntese | 6, 9, 23 |
| 8 | Síntese | 10, 12, 13 |
| 9 | Certeza, interpretação e relato | 14–15 |

## Erros cobertos com destaque

O checklist chama atenção para cinco falhas recorrentes:

1. **Usar desfecho como critério de elegibilidade.** Introduz viés de relato, porque a decisão de medir e publicar já é influenciada pelo resultado.
2. **Aplicar o RoB 2 uma vez por artigo.** A versão 2 avalia por resultado, não por estudo.
3. **Tratar dados de crossover como grupos independentes.** Superestima a variância e desperdiça a precisão do desenho pareado.
4. **Contar o braço compartilhado duas vezes.** Em ensaios de três braços, incluir A vs B e A vs C na mesma análise duplica os participantes de A.
5. **Concluir ausência de efeito a partir de ausência de significância.** Com amostras pequenas, o intervalo de confiança costuma abarcar benefício e dano.

## Fontes

- [Cochrane Handbook for Systematic Reviews of Interventions](https://training.cochrane.org/handbook) — Higgins JPT, Thomas J, Chandler J, Cumpston M, Li T, Page MJ, Welch VA (eds.)
- [PRISMA 2020](https://www.prisma-statement.org/) — Page MJ, et al. BMJ 2021;372:n71
- [MECIR](https://community.cochrane.org/mecir-manual) — requisitos formais de conduta e relato, item a item
- [SWiM](https://www.bmj.com/content/368/bmj.l6890) — Campbell M, et al. BMJ 2020;368:l6890, para sínteses sem meta-análise

Este repositório é um resumo da **estrutura** do método, não uma reprodução do texto do Handbook. As referências de capítulo apontam para a versão 6 e devem ser conferidas contra a edição vigente antes de serem citadas em um manuscrito.
