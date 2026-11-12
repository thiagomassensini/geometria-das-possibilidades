# Geometria das Possibilidades

**Geometria relacional da observabilidade, da identificabilidade e dos invariantes**

Este projeto investiga uma ideia: a geometria pode ser estudada como uma estrutura de possibilidades e impossibilidades determinada por objetos, relações, restrições, transformações e invariantes — não exclusivamente por distâncias.

Ampliar uma geometria pode significar incorporar objetos antes não considerados, descobrir relações entre objetos já conhecidos ou aumentar a capacidade de distinguir estados por observações. O objetivo não é acumular descrições, mas identificar **quais relações tornam uma pergunta respondível** e **quais estruturas permanecem quando muda a representação**.

## Formulação inicial

Fixe um conjunto de estados $X$, uma família de observáveis $A$ e funções $h_a:X\to V_a$. Definimos a indistinguibilidade observacional por:

$$
x\sim_A y\iff\forall a\in A,\; h_a(x)=h_a(y).
$$

Uma pergunta $Q:X\to W$ é identificável relativamente a $A$ quando:

$$
x\sim_A y\Longrightarrow Q(x)=Q(y).
$$

Sob um domínio fixo, com os observáveis antigos preservados, $A_0\subseteq A_1$ implica $\sim_{A_1}\subseteq\sim_{A_0}$: ampliar a observação pode refinar classes de estados indistinguíveis.

Essas afirmações são **matemáticas e condicionais**. Identificabilidade não significa que os dados já foram obtidos, e observar uma relação não demonstra automaticamente causalidade.

## Origem

O ponto de partida conceitual é o rascunho **[Ontologia da Presença Causal v0.2](documentos/origens/ONTOLOGIA_DA_PRESENCA_CAUSAL_v0.2.md)**, que distingue fenômeno e representação, define equivalência relacional entre descrições, estuda invariantes e separa a presença social e causal de padrões da questão de referentes metafísicos independentes.

A investigação atual amplia esse ponto de partida para um núcleo matemático mais geral. Consulte o documento completo: **[Investigação Fundacional v0.1](documentos/GEOMETRIA_DAS_POSSIBILIDADES_INVESTIGACAO_FUNDACIONAL_v0.1.md)**.

## Campos de investigação

- Estruturas relacionais de objetos, estados e possibilidades.
- Observabilidade, equivalência e identificabilidade de perguntas.
- Invariantes sob transformações e entre câmeras.
- Seleção de observáveis e geometrias mínimas relativas a perguntas.
- Relações estatísticas, temporalidade, intervenções e causalidade.
- Presença causal, transmissão e continuidade de padrões.
- Ampliação do campo relacional da consciência, no sentido cognitivo e metacognitivo.

## Princípio de rigor

Distinguir sempre definições, teoremas condicionais, exemplos, dados empíricos, hipóteses e interpretações. Nenhuma limitação observacional de uma geometria deve ser convertida, sem prova adicional, em impossibilidade universal. Do mesmo modo, uma ampliação conceitual não é por si só uma confirmação empírica.

## Idioma

**Português** — texto, exemplos, discussões e documentação. Nomes técnicos em outro idioma podem ser citados quando necessários, acompanhados de explicação em português.
