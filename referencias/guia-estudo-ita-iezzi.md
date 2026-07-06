# Guia de estudo ITA usando Fundamentos de Matemática Elementar — Iezzi

Este é um mapa de território, não uma fila única. A ideia é o aluno avançar por ilhas de domínio: estudar teoria no Iezzi, resolver exercícios do livro, depois validar com questões reais do ITA.

Base usada: `banco_questoes.jsonl` de matemática do repo, 495 questões catalogadas de 2008 a 2026.

Referências de capítulos: edições atualizadas (2013) da coleção FME.

## Como usar

Para cada território:

1. Ler o capítulo/bloco indicado no Iezzi.
2. Fazer exercícios básicos até ganhar fluência mecânica.
3. Fazer exercícios intermediários/desafiadores do próprio volume.
4. Resolver as questões ITA indicadas sem consulta.
5. Marcar como conhecido só se conseguir explicar a solução em voz alta.

Critério prático:

- **Conhecido**: acerta questões ITA do bloco em tempo razoável.
- **Fronteira**: sabe a teoria, mas trava em combinações de ideias.
- **Desconhecido**: ainda depende de fórmula/receita.

---

# Mapa macro da coleção vs ITA

## Núcleo pesado do ITA

- **FME 6 — Complexos, Polinômios e Equações**: 99 questões no banco.
- **FME 4 — Sequências, Matrizes, Determinantes e Sistemas**: 70 questões.
- **FME 1 — Conjuntos e Funções**: 60 questões.
- **FME 5 — Combinatória e Probabilidade**: 59 questões.
- **FME 7 — Geometria Analítica**: 53 questões.
- **FME 3 — Trigonometria**: 50 questões.
- **FME 10 — Geometria Espacial**: 49 questões.
- **FME 9 — Geometria Plana**: 48 questões.

## Baixa incidência como assunto principal

- **FME 2 — Logaritmos**: aparece muito dentro de Funções, mas raramente como território isolado.
- **FME 8 — Limites, Derivadas e Integral**: quase não é eixo principal do ITA nesse banco.
- **FME 11 — Financeira, Estatística**: não é prioridade para ITA matemática tradicional.

---

# Jornada recomendada

## Fase 0 — Ferramentas de base

Objetivo: parar de perder questão por álgebra, notação ou manipulação.

### Estudar

- **FME 1 Cap. 1-2**: noções de lógica, conjuntos, operações com conjuntos.
- **FME 1 Cap. 3-4**: conjuntos numéricos, intervalos reais, módulo, inequações.
- **FME 1 Cap. 5-7**: relações, funções, composição, inversa.
- **FME 1 Cap. 8-11**: função modular, funções do 1º e 2º grau, equações e inequações.
- **FME 2 Cap. 1-3**: potenciação, radiciação, função exponencial.
- **FME 2 Cap. 4-9**: logaritmos, propriedades, mudança de base, equações e inequações logarítmicas.
- Revisar álgebra: fatoração, produtos notáveis, radicais, módulo, inequações.

### Questões ITA para validar

Conjuntos e lógica:
`mat-2008-f1-q19`, `mat-2010-f1-q01`, `mat-2013-f1-q01`, `mat-2024-f1-q37`

Números reais/inequações:
`mat-2008-f1-q21`, `mat-2012-f1-q05`, `mat-2014-f1-q01`, `mat-2015-f1-q01`, `mat-2017-f1-q07`, `mat-2020-f1-q52`

Funções (domínio, imagem, composição, inversa):
`mat-2008-f1-q15`, `mat-2009-f1-q03`, `mat-2009-f1-q23`, `mat-2010-f1-q02`, `mat-2010-f1-q06`, `mat-2010-f1-q23`, `mat-2010-f1-q24`, `mat-2012-f1-q28`, `mat-2013-f1-q06`, `mat-2013-f1-q07`, `mat-2014-f1-q02`, `mat-2017-f1-q01`, `mat-2018-f1-q04`, `mat-2025-f1-q04`

Logaritmos e exponenciais:
`mat-2008-f1-q14`, `mat-2008-f1-q23`, `mat-2009-f1-q21`, `mat-2011-f1-q24`, `mat-2014-f1-q03`, `mat-2014-f1-q22`, `mat-2017-f1-q10`, `mat-2017-f1-q22`, `mat-2018-f1-q09`, `mat-2018-f1-q22`, `mat-2022-f1-q41`, `mat-2026-f1-q02`

### Marco de domínio

O aluno deve conseguir descobrir domínio/imagem, inverter função, compor funções, resolver inequações e reconhecer quando uma questão de logaritmo é só uma questão de função disfarçada.

---

## Fase 1 — Álgebra forte: o coração da prova

## Território A — Complexos

### Estudar

- **FME 6 Cap. 1**: forma algébrica — operações, conjugado, módulo, igualdade.
- **FME 6 Cap. 2**: representação geométrica no plano complexo — módulo como distância, argumento.
- **FME 6 Cap. 3**: forma trigonométrica/polar — conversão, multiplicação como rotação.
- **FME 6 Cap. 4**: potências, raízes da unidade, fórmula de De Moivre.

### Questões ITA

Forma algébrica e conjugado:
`mat-2008-f1-q02`, `mat-2010-f1-q03`, `mat-2011-f1-q02`, `mat-2014-f1-q04`, `mat-2014-f1-q05`, `mat-2017-f1-q15`

Forma trigonométrica, polar e De Moivre:
`mat-2008-f1-q22`, `mat-2009-f1-q04`, `mat-2010-f1-q04`, `mat-2011-f1-q01`, `mat-2012-f1-q03`, `mat-2013-f1-q03`, `mat-2013-f1-q21`, `mat-2016-f1-q12`, `mat-2018-f1-q08`, `mat-2018-f1-q24`, `mat-2020-f2-q06`, `mat-2021-f2-q06`

Plano complexo e lugar geométrico:
`mat-2009-f1-q22`, `mat-2011-f1-q22`, `mat-2014-f1-q23`, `mat-2015-f1-q24`, `mat-2019-f2-q03`, `mat-2025-f1-q01`

Raízes e potências:
`mat-2012-f1-q04`, `mat-2015-f1-q02`, `mat-2015-f1-q03`, `mat-2020-f2-q07`, `mat-2024-f1-q46`, `mat-2026-f1-q01`

### Marco de domínio

Complexos deixam de ser "conta" e viram geometria: módulo como distância, argumento como ângulo, raiz como rotação.

## Território B — Polinômios e equações

### Estudar

- **FME 6 Cap. 5**: polinômios — grau, operações, divisão, resto, identidade, fatoração.
- **FME 6 Cap. 6**: equações polinomiais — raízes, multiplicidade, raízes reais e complexas conjugadas.
- **FME 6 Cap. 7**: relações de Girard, raízes inteiras e racionais, equações recíprocas.

### Questões ITA

Relações de Girard e raízes:
`mat-2008-f1-q09`, `mat-2008-f1-q10`, `mat-2009-f1-q05`, `mat-2009-f1-q06`, `mat-2009-f1-q07`, `mat-2009-f1-q08`, `mat-2009-f1-q24`, `mat-2010-f1-q08`, `mat-2010-f1-q09`, `mat-2010-f1-q10`, `mat-2018-f1-q15`, `mat-2023-f1-q37`

Fatoração e divisão polinomial:
`mat-2008-f1-q24`, `mat-2016-f1-q22`, `mat-2020-f2-q03`, `mat-2020-f2-q05`, `mat-2024-f1-q37`, `mat-2024-f1-q39`, `mat-2025-f1-q03`

Raízes complexas e conjugação:
`mat-2008-f1-q26`, `mat-2018-f1-q10`, `mat-2020-f1-q43`, `mat-2020-f2-q06`

Equações e parâmetros:
`mat-2013-f1-q09`, `mat-2014-f1-q06`, `mat-2017-f1-q09`, `mat-2022-f2-q03`, `mat-2023-f2-q02`

### Marco de domínio

O aluno precisa enxergar fatoração, simetria de raízes, Girard e divisibilidade polinomial como uma caixa de ferramentas única.

---

## Fase 2 — Matrizes, sistemas e sequências

## Território C — Matrizes, determinantes e sistemas

### Estudar

- **FME 4 Cap. 5**: matrizes — definição, operações, produto, transposta, inversa.
- **FME 4 Cap. 6**: determinantes — propriedades, cálculo, expansão de Laplace.
- **FME 4 Cap. 7**: sistemas lineares — escalonamento, discussão com parâmetros, regra de Cramer.

### Questões ITA

Matrizes e operações:
`mat-2008-f1-q04`, `mat-2008-f1-q25`, `mat-2009-f1-q26`, `mat-2011-f1-q25`, `mat-2014-f1-q09`, `mat-2015-f1-q13`, `mat-2016-f1-q11`, `mat-2016-f1-q24`, `mat-2021-f1-q41`, `mat-2022-f1-q46`, `mat-2023-f1-q37`, `mat-2026-f1-q03`, `mat-2026-f1-q07`

Determinantes:
`mat-2008-f1-q03`, `mat-2010-f1-q13`, `mat-2010-f1-q14`, `mat-2011-f1-q06`, `mat-2012-f1-q23`, `mat-2013-f1-q13`, `mat-2014-f1-q08`, `mat-2014-f1-q10`, `mat-2017-f1-q11`, `mat-2018-f1-q15`, `mat-2021-f2-q02`

Sistemas lineares:
`mat-2009-f1-q09`, `mat-2009-f1-q10`, `mat-2010-f1-q27`, `mat-2011-f1-q07`, `mat-2014-f1-q26`, `mat-2016-f1-q08`, `mat-2017-f1-q27`, `mat-2019-f1-q41`, `mat-2022-f1-q43`, `mat-2023-f2-q01`, `mat-2025-f1-q07`

### Marco de domínio

Saber calcular determinante não basta. O aluno precisa usar determinante como linguagem para dependência linear, inversibilidade e discussão de sistemas.

## Território D — Sequências e progressões

### Estudar

- **FME 4 Cap. 1**: sequências — definição, classificação, representação.
- **FME 4 Cap. 2**: progressão aritmética — termo geral, soma, propriedades.
- **FME 4 Cap. 3**: progressão geométrica — termo geral, soma, PG infinita.
- **FME 4 Cap. 4**: somatórios — manipulação, mudança de índice, fórmulas.

### Questões ITA

PA e PG:
`mat-2008-f1-q05`, `mat-2010-f1-q05`, `mat-2010-f1-q22`, `mat-2012-f1-q07`, `mat-2015-f1-q05`, `mat-2015-f1-q23`, `mat-2016-f1-q05`, `mat-2017-f1-q03`, `mat-2017-f1-q25`, `mat-2018-f1-q03`, `mat-2018-f1-q18`, `mat-2019-f1-q43`

Somatórios e recorrências:
`mat-2008-f1-q16`, `mat-2022-f2-q03`, `mat-2025-f2-q08`

### Marco de domínio

Reconhecer PA/PG escondida em geometria, polinômios, contagem e problemas de recorrência.

---

## Fase 3 — Contagem e probabilidade

## Território E — Combinatória

### Estudar

- **FME 5 Cap. 1**: princípio fundamental da contagem, princípio aditivo e multiplicativo.
- **FME 5 Cap. 2**: permutações simples e com repetição, arranjos, combinações, permutações circulares.
- **FME 5 Cap. 3**: binômio de Newton, triângulo de Pascal, identidades binomiais.
- **FME 5 Cap. 2-3 (exercícios avançados)**: inclusão-exclusão, contagem por casos, simetria, números de Stirling.

### Questões ITA

Contagem:
`mat-2008-f1-q17`, `mat-2009-f1-q01`, `mat-2009-f1-q02`, `mat-2011-f1-q05`, `mat-2011-f1-q23`, `mat-2012-f1-q14`, `mat-2014-f1-q25`, `mat-2016-f1-q19`, `mat-2017-f1-q08`, `mat-2017-f1-q24`, `mat-2021-f2-q07`, `mat-2024-f1-q40`, `mat-2024-f1-q41`, `mat-2026-f1-q11`

Binômio de Newton e combinações:
`mat-2010-f1-q11`, `mat-2010-f1-q12`, `mat-2010-f1-q21`, `mat-2012-f1-q21`, `mat-2013-f1-q24`, `mat-2014-f1-q07`, `mat-2016-f1-q03`, `mat-2018-f1-q06`, `mat-2018-f1-q26`, `mat-2023-f2-q10`

## Território F — Probabilidade

### Estudar

- **FME 5 Cap. 4**: probabilidade — espaço amostral, eventos, probabilidade clássica, complementar.
- **FME 5 Cap. 5**: probabilidade condicional, eventos independentes, teorema de Bayes, distribuição binomial.

### Questões ITA

Probabilidade clássica e condicional:
`mat-2008-f1-q01`, `mat-2008-f1-q27`, `mat-2009-f1-q12`, `mat-2009-f1-q25`, `mat-2010-f1-q12`, `mat-2010-f1-q26`, `mat-2011-f1-q04`, `mat-2012-f1-q02`, `mat-2013-f1-q11`, `mat-2013-f1-q12`, `mat-2014-f1-q24`, `mat-2015-f1-q26`, `mat-2017-f1-q19`, `mat-2018-f1-q19`, `mat-2020-f2-q02`

Distribuições e esperança:
`mat-2012-f1-q02`, `mat-2016-f1-q25`, `mat-2021-f2-q10`, `mat-2025-f2-q06`

### Marco de domínio

O aluno deve separar "contar casos" de "calcular probabilidade". Em ITA, o erro comum é escolher o espaço amostral errado.

---

## Fase 4 — Trigonometria como linguagem

## Território G — Trigonometria

### Estudar

- **FME 3 Cap. 1-2**: razões trigonométricas, arcos e ângulos, ciclo trigonométrico.
- **FME 3 Cap. 4-5**: identidades fundamentais, prova e simplificação.
- **FME 3 Cap. 6-7**: soma e diferença de arcos, arco duplo, arco metade, transformações.
- **FME 3 Cap. 8**: equações trigonométricas.
- **FME 3 Cap. 9 + FME 9 Cap. 6**: lei dos senos, lei dos cossenos, área trigonométrica.

### Questões ITA

Identidades e equações:
`mat-2008-f1-q11`, `mat-2008-f1-q13`, `mat-2008-f1-q16`, `mat-2009-f1-q13`, `mat-2009-f1-q27`, `mat-2010-f1-q15`, `mat-2010-f1-q16`, `mat-2010-f1-q28`, `mat-2011-f1-q14`, `mat-2012-f1-q20`, `mat-2013-f1-q05`, `mat-2013-f1-q14`, `mat-2014-f1-q15`, `mat-2014-f1-q23`, `mat-2016-f1-q04`, `mat-2016-f1-q15`, `mat-2016-f1-q18`, `mat-2017-f1-q04`, `mat-2019-f1-q38`, `mat-2019-f1-q46`, `mat-2023-f1-q46`, `mat-2024-f1-q49`

Lei dos senos/cossenos e triângulos:
`mat-2009-f1-q17`, `mat-2010-f1-q07`, `mat-2011-f1-q17`, `mat-2011-f1-q25`, `mat-2016-f1-q07`, `mat-2017-f1-q20`, `mat-2022-f2-q08`, `mat-2023-f1-q42`, `mat-2023-f1-q46`

### Marco de domínio

Trigonometria não é decorar fórmula; é converter ângulo, comprimento, área e equação para a forma mais manipulável.

---

## Fase 5 — Geometria em três mapas

## Território H — Geometria plana

### Estudar

- **FME 9 Cap. 1**: ângulos — classificação, ângulos complementares e suplementares.
- **FME 9 Cap. 2**: triângulos — classificação, congruência, pontos notáveis.
- **FME 9 Cap. 3**: quadriláteros e polígonos — propriedades, diagonais, ângulos internos.
- **FME 9 Cap. 4**: circunferência — arcos, cordas, tangentes, ângulos inscritos, potência de ponto.
- **FME 9 Cap. 5**: semelhança de triângulos — critérios, poligonais.
- **FME 9 Cap. 6**: relações métricas nos triângulos — Pitágoras, projeções, bissetriz.
- **FME 9 Cap. 7**: áreas de figuras planas.

### Questões ITA

Triângulos e relações métricas:
`mat-2008-f1-q07`, `mat-2008-f1-q18`, `mat-2008-f1-q20`, `mat-2008-f1-q28`, `mat-2009-f1-q15`, `mat-2011-f1-q15`, `mat-2011-f1-q16`, `mat-2014-f1-q14`, `mat-2014-f1-q16`, `mat-2014-f1-q17`, `mat-2015-f1-q18`, `mat-2016-f1-q20`, `mat-2017-f1-q16`, `mat-2017-f1-q20`

Circunferência e polígonos:
`mat-2008-f1-q07`, `mat-2009-f1-q15`, `mat-2011-f1-q29`, `mat-2011-f1-q30`, `mat-2012-f1-q09`, `mat-2012-f1-q30`, `mat-2016-f1-q06`, `mat-2016-f1-q23`, `mat-2018-f1-q01`, `mat-2020-f1-q46`, `mat-2023-f1-q39`

Áreas:
`mat-2017-f1-q09`, `mat-2021-f1-q50`, `mat-2024-f1-q45`

## Território I — Geometria analítica

### Estudar

- **FME 7 Cap. 1-2**: coordenadas no plano, distância entre pontos, ponto médio.
- **FME 7 Cap. 3**: reta — equações, inclinação, paralelismo, perpendicularismo, distância ponto-reta, feixe de retas.
- **FME 7 Cap. 4**: circunferência — equação geral e reduzida, posições relativas, tangência.
- **FME 7 Cap. 5**: parábola — vértice, foco, diretriz.
- **FME 7 Cap. 6**: elipse — elementos, equações.
- **FME 7 Cap. 7**: hipérbole — elementos, equações, assíntotas.
- **FME 7 Cap. 8**: lugares geométricos.

### Questões ITA

Reta e distância:
`mat-2008-f1-q30`, `mat-2009-f1-q14`, `mat-2009-f1-q18`, `mat-2009-f1-q29`, `mat-2012-f1-q11`, `mat-2012-f1-q12`, `mat-2014-f1-q19`, `mat-2015-f1-q14`, `mat-2015-f1-q15`, `mat-2017-f1-q05`, `mat-2017-f1-q21`, `mat-2022-f1-q42`, `mat-2024-f1-q47`, `mat-2026-f1-q09`

Circunferência:
`mat-2009-f1-q28`, `mat-2010-f1-q17`, `mat-2010-f1-q29`, `mat-2011-f1-q13`, `mat-2012-f1-q10`, `mat-2016-f1-q28`, `mat-2018-f1-q07`, `mat-2018-f1-q23`, `mat-2022-f2-q09`

Cônicas:
`mat-2008-f1-q12`, `mat-2009-f1-q16`, `mat-2010-f1-q19`, `mat-2013-f1-q17`, `mat-2015-f1-q29`, `mat-2019-f2-q05`, `mat-2021-f1-q44`, `mat-2023-f2-q07`, `mat-2025-f1-q11`, `mat-2025-f2-q02`

Lugares geométricos:
`mat-2016-f1-q26`, `mat-2022-f1-q48`

## Território J — Geometria espacial

### Estudar

- **FME 10 Cap. 1**: posições relativas entre retas e planos — paralelismo, perpendicularidade, diedros, triedros.
- **FME 10 Cap. 2**: prismas — classificação, áreas, volumes.
- **FME 10 Cap. 3**: pirâmides — regulares, troncos, áreas, volumes.
- **FME 10 Cap. 4**: cilindros — equilátero, áreas, volume.
- **FME 10 Cap. 5**: cones — retos, troncos, áreas, volume, relação de semelhança.
- **FME 10 Cap. 6**: esfera — posição relativa, esferas inscritas/circunscritas, calota, zona.
- **FME 10 Cap. 7**: poliedros — Euler, regulares, relação com sólidos inscritos/circunscritos.
- **FME 9 Cap. 5 + FME 3 Cap. 9**: seções planas e trigonometria dentro do sólido.

### Questões ITA

Prismas, pirâmides e sólidos de revolução:
`mat-2008-f1-q06`, `mat-2008-f1-q29`, `mat-2009-f1-q19`, `mat-2009-f1-q20`, `mat-2010-f1-q18`, `mat-2010-f1-q20`, `mat-2012-f1-q19`, `mat-2012-f1-q20`, `mat-2012-f1-q25`, `mat-2014-f1-q18`, `mat-2014-f1-q20`, `mat-2014-f1-q30`

Esferas e poliedros:
`mat-2010-f1-q30`, `mat-2011-f1-q19`, `mat-2011-f1-q20`, `mat-2011-f1-q27`, `mat-2018-f1-q21`, `mat-2020-f2-q10`, `mat-2022-f2-q10`

Sólidos inscritos/circunscritos e seções:
`mat-2009-f1-q30`, `mat-2016-f1-q17`, `mat-2016-f1-q30`, `mat-2019-f2-q08`, `mat-2021-f1-q51`, `mat-2022-f1-q49`, `mat-2022-f1-q50`, `mat-2023-f2-q08`, `mat-2024-f1-q43`, `mat-2024-f1-q44`, `mat-2025-f2-q10`

### Marco de domínio

Geometria espacial do ITA costuma exigir reduzir o sólido a triângulos bons, seções planas e relações métricas conhecidas.

---

## Fase 6 — Territórios complementares

## Teoria dos números

Não há um volume dedicado na coleção FME clássica, mas aparece em problemas de divisibilidade, paridade, congruência e fatoração.

### Estudar por fora/complementar

- Divisibilidade.
- MDC/MMC.
- Congruências modulares.
- Paridade.
- Fatoração única.
- Expoente de primo em fatorial.
- Equações diofantinas simples.

### Questões ITA

`mat-2013-f1-q08`, `mat-2017-f1-q13`, `mat-2019-f2-q07`, `mat-2020-f1-q49`, `mat-2020-f2-q03`, `mat-2025-f1-q12`

## Cálculo / FME 8 (Cap. 1-6)

Baixa prioridade como eixo principal para ITA, mas útil como maturidade matemática.

### Estudar se houver tempo

- **FME 8 Cap. 1-3**: limite intuitivo, algébrico, continuidade.
- **FME 8 Cap. 4-5**: derivada como taxa/otimização, reta tangente.
- **FME 8 Cap. 6**: noções de integral.

### Uso real

Serve mais para fortalecer raciocínio e algumas soluções alternativas do que como frente central de prova.

## Financeira/Estatística / FME 11

Baixa prioridade para ITA matemática. Estudar depois do núcleo, se a preparação estiver folgada.

---

# Ordem sugerida para um aluno começando sério

## Ciclo 1 — Base algébrica

1. FME 1 Cap. 1-4 — conjuntos, reais, intervalos.
2. FME 1 Cap. 5-11 — funções, composição, inversa, modular, 1º e 2º grau, inequações.
3. FME 2 — logaritmos e exponenciais como extensão de funções.
4. FME 6 Cap. 1-4 — complexos.
5. FME 6 Cap. 5-7 — polinômios, raízes, Girard, fatoração.

## Ciclo 2 — Estrutura e contagem

6. FME 4 Cap. 5-7 — matrizes, determinantes, sistemas.
7. FME 4 Cap. 1-4 — sequências, PA, PG, somatórios.
8. FME 5 Cap. 1-3 — combinatória e binômio.
9. FME 5 Cap. 4-5 — probabilidade.

## Ciclo 3 — Geometria e trigonometria

10. FME 3 — trigonometria.
11. FME 9 — geometria plana.
12. FME 7 — geometria analítica.
13. FME 10 — geometria espacial.

## Ciclo 4 — Revisão ITA

14. Refazer questões erradas por assunto.
15. Misturar assuntos em simulados.
16. Criar caderno de padrões: "quando vejo X, tento Y".
17. Voltar ao Iezzi só nos buracos detectados.

---

# Checklist de conquista por território

- [ ] FME 1 Cap. 1-2 — conjuntos e lógica básica.
- [ ] FME 1 Cap. 3-4 — conjuntos numéricos, intervalos, módulo.
- [ ] FME 1 Cap. 5-11 — funções, composição, inversa, domínio/imagem, inequações.
- [ ] FME 2 — logaritmos e exponenciais.
- [ ] FME 6 Cap. 1-4 — complexos algébricos e geométricos.
- [ ] FME 6 Cap. 5-7 — polinômios, raízes, Girard, fatoração.
- [ ] FME 4 Cap. 5-7 — matrizes, determinantes, sistemas.
- [ ] FME 4 Cap. 1-4 — PA, PG, somas, recorrências.
- [ ] FME 5 Cap. 1-3 — contagem e binômio.
- [ ] FME 5 Cap. 4-5 — probabilidade, condicional, Bayes.
- [ ] FME 3 — identidades e equações trigonométricas.
- [ ] FME 9 — geometria plana.
- [ ] FME 7 — geometria analítica.
- [ ] FME 10 — geometria espacial.
- [ ] Teoria dos números complementar.
- [ ] Simulados mistos com questões ITA.

---

# Receita semanal simples

Para cada semana de estudo:

1. Escolher um território.
2. Ler teoria e exemplos do Iezzi.
3. Fazer 30–60 exercícios do livro, começando fáceis e subindo.
4. Resolver 8–12 questões ITA do mesmo território.
5. Registrar erros em três categorias:
   - não sabia teoria;
   - sabia, mas não viu o caminho;
   - erro algébrico/atenção.
6. Reestudar só o que apareceu como buraco real.

---

# Observação importante

O Iezzi é ótimo para construir musculatura. Mas a prova do ITA cobra mistura: uma questão catalogada como geometria pode usar trigonometria; uma de combinatória pode usar polinômio; uma de espacial pode virar geometria plana. Por isso o mapa deve ser usado como exploração de territórios, não como lista rígida de capítulos.