# Geometria das Possibilidades
## Fundamentos de uma geometria relacional da observabilidade, da identificabilidade e da ampliação da consciência

**Investigação fundacional — versão 0.1**  
**Data:** 12 de novembro de 2026  
**Idioma:** português  
**Natureza:** ensaio de investigação filosófico-matemática com resultados condicionais, exemplos construídos e programa de formalização.  
**Documento-fonte:** `ONTOLOGIA_DA_PRESENCA_CAUSAL_v0.2(2).md`, *Ontologia da Presença Causal: Geometria Relacional da Existência, da Representação e da Sobrevivência* (v0.2).  
**Proposta de repositório:** `geometria-das-possibilidades`.

> **Regra de leitura:** este documento distingue explicitamente resultados matemáticos que decorrem de definições, analogias fundamentadas na literatura, modelos construídos e hipóteses de pesquisa. Não é uma prova de uma teoria física da consciência nem de uma ontologia metafísica universal. Tampouco substitui o rascunho de origem: preserva sua genealogia e propõe uma fundação mais geral.

---

## Resumo executivo

A ideia investigada começa com uma generalização da palavra *geometria*: um espaço estruturado de **possibilidades e impossibilidades**, determinado pelos objetos considerados, suas relações, as restrições, as transformações admissíveis e os invariantes. Distância pode integrar essa estrutura, mas não é seu fundamento exclusivo.

O enunciado original, em linguagem próxima à intenção do autor, é:

> Ampliar o espaço geométrico da consciência não é aumentar distâncias nem simplesmente armazenar mais fatos. É incorporar objetos que antes não eram considerados, reconhecer relações novas entre objetos novos e antigos, e assim criar condições observacionais para distinguir possibilidades que a geometria anterior não distinguia. O alvo não são objetos isolados, mas relações — em especial as que permanecem invariantes quando mudam os objetos, medidas, fórmulas, palavras ou coordenadas.

O aprofundamento revela **quatro operações diferentes** que merecem ser separadas:

1. **Extensão de domínio:** introduzir objetos, eventos, agentes ou estados antes não modelados.
2. **Enriquecimento relacional:** tornar explícitas relações antes ausentes do modelo, inclusive entre objetos que já estavam nele.
3. **Ampliação observacional:** adicionar testes, medições, comparações ou intervenções capazes de discriminar estados.
4. **Mudança de representação:** descrever a mesma estrutura em outra linguagem, coordenatização ou câmera, sem necessariamente ganhar informação.

O resultado matemático organizador é simples e profundo. Mantendo o mesmo domínio de estados e preservando todos os observáveis anteriores, o aumento do conjunto de observáveis **refina a equivalência observacional**: estados antes indistinguíveis podem se separar; estados antes distinguíveis não se confundem. Uma pergunta é identificável exatamente quando sua resposta é constante em cada classe de indistinguibilidade; isto equivale a dizer que a pergunta *fatora pela assinatura observacional*.

Essa formalização produz um programa de pesquisa com consequências para: ontologia relacional, teoria da representação, inferência causal, observabilidade de sistemas dinâmicos, projeto de experimentos, conservação de padrões, memória distribuída e estudo da consciência como acesso a relações. **Não permite**, por si só, concluir que relações observadas são causais, que toda pergunta poderá ser identificada, ou que o acesso à informação explica a experiência subjetiva.

A principal contribuição proposta **não é reivindicar a descoberta de teoremas clássicos**, mas articulá-los em uma arquitetura que começa na ampliação relacional do campo observacional e termina na investigação dos invariantes que sobrevivem a diferentes descrições.

### Convenção de rigor

- **[FONTE]** — afirmação extraída ou fiel à v0.2 fornecida.
- **[MAT]** — resultado matemático demonstrável sob hipóteses explicitadas.
- **[LIT]** — correspondência com literatura existente.
- **[MODELO]** — exemplo matemático ou conceitual construído para testar ideias.
- **[HIPÓTESE]** — proposta nova deste documento, sem demonstração geral ou validação empírica.
- **[LIMITE]** — condição de validade, contraexemplo ou interpretação excessiva a evitar.

---

# Parte I — A questão originária e a mudança de perspectiva

## 1. Geometria não como medida isolada, mas como estrutura de diferenças

O uso etimológico de *geometria* (medida da terra) não obriga a restringir o conceito contemporâneo a distância euclidiana. A matemática já estuda geometrias topológicas, diferenciais, algébricas, projetivas, métricas e combinatórias. Em muitas delas, o essencial é saber **que estruturas são preservadas por quais transformações**.

A generalização aqui proposta é **metodológica**, não a alegação de que toda teoria matemática normalmente chamada de geometria coincide automaticamente com esta definição:

> Uma geometria investigativa especifica objetos ou estados, relações relevantes, possibilidades admitidas pelas restrições, mudanças permitidas de representação e condições de distinção entre estados.

Na v0.2 de *Ontologia da Presença Causal*, a estrutura esquemática é

\[
\mathcal G=(\mathcal O,\mathcal R,\mathcal T,\mathcal C,\mathcal I),
\]

em que \(\mathcal O\) designa objetos, \(\mathcal R\) relações, \(\mathcal T\) transformações admissíveis, \(\mathcal C\) restrições e \(\mathcal I\) invariantes. Essa é a genealogia da presente investigação. **[FONTE]**

Convém enriquecer a assinatura com o domínio das descrições, o sistema de observação e um conjunto explícito de perguntas. Propomos:

\[
\boxed{\mathfrak G=(X,\mathcal O,\mathcal R,\mathcal C,\mathcal T,\mathsf A,\mathsf H,\mathsf Q)}.
\]

- \(X\): estados, situações ou modelos candidatos a distinguir;
- \(\mathcal O\): objetos internos que podem participar das situações;
- \(\mathcal R\): relações de aridade variável entre objetos;
- \(\mathcal C\): restrições que definem quais estados são admissíveis;
- \(\mathcal T\): transformações entre descrições/câmeras que se deseja considerar;
- \(\mathsf A\): família de observáveis ou protocolos disponíveis;
- \(\mathsf H\): interpretação que atribui resultado a cada observável em cada estado;
- \(\mathsf Q\): perguntas-alvo formuladas sobre estados.

**Importante:** \(X\) não é idêntico a \(\mathcal O\). Um estado pode conter vários objetos e relações; dois estados podem conter exatamente os mesmos objetos e diferir apenas na relação entre eles. Isso evita uma confusão recorrente entre *incluir um objeto* e *adquirir uma maneira de distinguir estados*.

## 2. Possível, impossível, não observado, não identificável

Quatro noções distintas:

- **Possibilidade estrutural:** uma configuração \(x\in X\) obedece às restrições \(\mathcal C\).
- **Impossibilidade estrutural:** determinada configuração contradiz \(\mathcal C\).
- **Não observado:** não foi obtido um valor de medição, embora o valor possa estar definido.
- **Não identificável:** estados com respostas diferentes à pergunta produzem exatamente os mesmos resultados sob os observáveis admitidos.

Há ainda uma quinta situação: uma pergunta não é uma propriedade bem definida **das classes relacionais** escolhidas. Isso não é o mesmo que provar que a pergunta carece de todo significado filosófico.

Exemplo: saber que \(x+y=10\) admite infinitas soluções não significa que cada par seja fisicamente possível no sistema real; significa apenas que **essa restrição isolada** não seleciona um par único. A segunda relação \(x-y=2\) pode selecionar \((6,4)\), desde que ambas sejam válidas.

## 3. Duas direções do “aumento”

A palavra *aumento* comporta duas operações que podem apontar em sentidos opostos:

**A. Ampliação do modelo:** novas variáveis, objetos e hipóteses podem **aumentar** o conjunto de mundos candidatos e o número de possibilidades concebíveis.

**B. Ampliação da observação:** novas relações medidas podem **reduzir** o conjunto de mundos compatíveis com os dados, aumentando o poder de distinguir.

Uma pessoa pode, portanto, **conceber mais possibilidades** enquanto **elimina mais possibilidades incompatíveis** com a evidência. Não há contradição: são operações sobre conjuntos diferentes.

Representação esquemática:

```text
MUNDO / FENÔMENO (não confundido com sua descrição)
                  |
          modelos / descrições
                  |
       estados candidatos X
                  |
        observações disponíveis
                  |
      classes indistinguíveis
                  |
     pergunta Q: distinguível?
                  |
         novas relações
                  |
  refinamento / revisão do modelo
```

O fluxo não é necessariamente linear: descobertas podem obrigar a revisar \(X\), \(\mathcal C\), ou o significado de \(Q\), e não apenas adicionar sensores.

---

# Parte II — Núcleo matemático da observabilidade relacional

## 4. Assinaturas observacionais

Fixe um conjunto \(X\) de estados possíveis, uma família \(A\) de observáveis e, para cada \(a\in A\), uma função de observação

\[
h_a:X\longrightarrow V_a.
\]

\(V_a\) pode ser booleano, numérico, categórico, uma série temporal ou uma distribuição de probabilidade.

A **assinatura observacional** de um estado é

\[
\sigma_A(x)=(h_a(x))_{a\in A}\in\prod_{a\in A}V_a.
\]

Dois estados são indistinguíveis relativamente a \(A\) quando

\[
\boxed{x\sim_A y\iff\forall a\in A,\;h_a(x)=h_a(y).}
\tag{1}
\]

A relação \(\sim_A\) é reflexiva, simétrica e transitiva. Ela define uma partição de \(X\), ou equivalentemente o quociente

\[
X/{\sim_A}.
\]

**[MAT]** O quociente representa *o que a família atual de observações consegue distinguir*, não necessariamente a estrutura completa do mundo.

O documento v0.2 já introduzia esta ideia usando descrições e predicados \(H(d,o)\). A função \(h_a\) amplia essa construção de resultados booleanos a valores quaisquer e protocolos de medição. **[FONTE + PROPOSTA]**

### O alvo não é a assinatura, mas o que ela preserva

Se dois textos apresentam vocabulários diferentes, mas codificam as mesmas relações, suas assinaturas relevantes podem coincidir. Inversamente, duas descrições com palavras iguais podem codificar estruturas diferentes. Uma função de observação que apenas reconhece palavras não é automaticamente um teste legítimo da relação a que essas palavras pretendem se referir.

## 5. Teorema I — Refinamento por ampliação observacional

**Enunciado [MAT].** Seja \(A_0\subseteq A_1\) e sejam mantidos o mesmo domínio \(X\) e os mesmos resultados \(h_a\) para os observáveis antigos. Então

\[
\boxed{x\sim_{A_1}y\;\Longrightarrow\;x\sim_{A_0}y.}
\tag{2}
\]

**Prova.** Se \(x\) e \(y\) concordam para todo \(a\in A_1\), concordam em particular para todo \(a\in A_0\), pois \(A_0\subseteq A_1\). \(\square\)

**Interpretação:** uma observação adicional pode dividir uma classe de equivalência preexistente; nunca funde classes distintas, sob as hipóteses do teorema.

Segue uma aplicação natural entre os quocientes:

\[
\pi_{10}: X/{\sim_{A_1}}\longrightarrow X/{\sim_{A_0}},
\qquad[x]_{A_1}\mapsto[x]_{A_0}.
\tag{3}
\]

Essa aplicação é bem definida e sobrejetora. Para \(X\) finito:

\[
\boxed{|X/{\sim_{A_0}}|\le |X/{\sim_{A_1}}|\le |X|.}
\tag{4}
\]

**Atenção:** o crescimento pode ser igual a zero: adicionar um observável redundante não melhora a discriminação. A inclusão estrita \(A_0\subsetneq A_1\) **não** implica aumento estrito do número de classes.

### Quando o teorema deixa de se aplicar?

Se a geometria ampliada altera o próprio conjunto de estados, redefine medições antigas ou revisa as condições de equivalência, uma comparação direta entre partições pode deixar de fazer sentido. Nesse caso, é necessário explicitar mapas de tradução entre modelos, preservação dos observáveis antigos e quais conclusões são relativas à geometria anterior.

## 6. Teorema II — Identificabilidade = fatoração pelas observações

Seja \(Q:X\to W\) uma pergunta, entendida como função de resposta (\(W=\{\mathrm{sim},\mathrm{não}\}\) no caso binário).

Dizemos que \(Q\) é **identificável por \(A\)** quando

\[
\boxed{\forall x,y\in X,\quad x\sim_A y\Longrightarrow Q(x)=Q(y).}
\tag{5}
\]

**Teorema [MAT].** As seguintes condições são equivalentes:

1. \(Q\) é identificável por \(A\).
2. Existe uma função única \(\overline Q:X/{\sim_A}\to W\) com \(Q=\overline Q\circ q_A\), em que \(q_A\) é o mapa quociente.
3. Existe uma função \(f:\sigma_A(X)\to W\) com \(Q=f\circ\sigma_A\).

**Demonstração resumida.** Se (1) vale, defina \(\overline Q([x]_A):=Q(x)\). A hipótese garante que o valor independe do representante. Unicidade decorre de \(q_A\) ser sobrejetora. A passagem entre (2) e (3) usa a correspondência natural entre classes de \(\sim_A\) e assinaturas observacionais efetivamente realizadas. As implicações inversas são imediatas. \(\square\)

Em linguagem simples:

> Uma pergunta é observacionalmente decidível em princípio quando sua resposta depende apenas da informação contida na assinatura observacional completa.

**“Em princípio” não significa “na prática”.** É preciso distinguir identificabilidade estrutural de coleta de dados, exatidão dos sensores, custo de cálculo e capacidade humana de interpretar as relações.

## 7. Corolário — Uma pergunta já identificável continua identificável

**[MAT]** Se \(A_0\subseteq A_1\) e \(Q\) é identificável por \(A_0\), então \(Q\) é identificável por \(A_1\).

**Prova:** aplique (2) para obter equivalência antiga a partir da nova e depois (5). \(\square\)

Esse corolário é uma versão rigorosa da intuição: aumentar o repertório de observações não destrói uma distinção que já era possível, **desde que o sistema anterior não tenha sido redefinido**.

## 8. Teorema III — Critério por pares discriminantes

\(Q\) é identificável por \(A\) se, e somente se, para cada par de estados com respostas diferentes existir ao menos um observável que os distinga:

\[
\boxed{
Q(x)\ne Q(y)
\;\Longrightarrow\;
\exists a\in A:\;h_a(x)\ne h_a(y).
}
\tag{6}
\]

**[MAT]** Isso é a contrapositiva de (5) com a negação da igualdade de assinaturas. É uma ferramenta direta para selecionar novas relações: não basta encontrar uma relação interessante; ela precisa separar **algum par relevante à pergunta**.

### Separar estados não é a mesma coisa que responder a uma pergunta

Um novo observável pode distinguir \(x\) de \(y\) sem ajudar a decidir \(Q\), caso \(Q(x)=Q(y)\). Por isso, aumentar a resolução global do espaço pode não melhorar a identificabilidade do problema que motivou a investigação.

## 9. O que significa “geometria mínima para uma pergunta”?

Fixe uma família máxima admissível \(A_{\max}\) e uma pergunta \(Q\). Procure

\[
A_*\subseteq A_{\max}
\quad\text{tal que}\quad
Q\text{ seja identificável por }A_*.
\tag{7}
\]

Pode-se exigir minimalidade por inclusão ou custo mínimo:

\[
\min_{A_*}\sum_{a\in A_*}c(a)
\quad\text{sujeito à identificabilidade de }Q.
\tag{8}
\]

**[MAT]** Para \(X\) finito, se \(Q\) é identificável pela família completa \(A_{\max}\), então existe um **subconjunto finito** de observáveis que já identifica \(Q\). Basta escolher um discriminante para cada par \((x,y)\) com \(Q(x)\ne Q(y)\). O conjunto de pares é finito.

Isso fornece uma cota grosseira para o número de observáveis escolhidos: no máximo o número de pares com respostas diferentes. A cota pode ser reduzida porque um único teste distingue muitos pares.

**[LIMITE]** Uma família mínima pode não ser única. Se dois sensores diferentes medem igualmente o valor de \(Q\), qualquer um deles pode formar uma solução mínima. Não existe, em geral, um “sensor metafisicamente privilegiado”.

**[LIMITE]** Em espaços infinitos, a identificabilidade pode exigir infinitas observações: considere sequências binárias infinitas \(x\in\{0,1\}^{\mathbb N}\), observáveis de cada coordenada e a pergunta “há alguma coordenada igual a 1?”. A família de todas as coordenadas identifica a pergunta; nenhuma seleção finita de coordenadas o faz.

**[LIMITE]** Se \(Q\) não for identificável nem por \(A_{\max}\), nenhuma seleção de observáveis *dessa mesma família* resolverá a questão. Isso é um impedimento **relativo à família admitida**, não uma impossibilidade metafísica universal.

## 10. Reticulado de observações e classes

As famílias de observáveis ordenadas por inclusão formam uma estrutura de ordem (um reticulado de conjuntos). A cada família corresponde uma partição de \(X\) em classes de indistinguibilidade. Unir duas famílias de observáveis produz a **interseção das equivalências**:

\[
\boxed{\sim_{A\cup B}\;=\;(\sim_A)\cap(\sim_B).}
\tag{9}
\]

Ou seja, a geometria observacional conjunta distingue exatamente aquilo que pode ser discriminado por ao menos uma das duas famílias.

Não se deve confundir esse fato com a afirmação de que as *estatísticas marginais* de duas medições determinam sua *distribuição conjunta*: podem não determinar, e veremos um exemplo disso adiante.

O espaço de perguntas \(Q\) identificáveis por \(A\) é o espaço de funções constantes nas classes de \(\sim_A\). A inclusão de observáveis amplia o conjunto de perguntas identificáveis, possivelmente sem torná-lo estritamente maior.

### Grau de liberdade: separar três conceitos

1. **Grau de liberdade do estado:** número de parâmetros independentes que podem variar sem violar as restrições.
2. **Dimensão da informação observável:** número de direções independentemente mensuráveis ou de classes discriminadas.
3. **Grau de liberdade representacional:** mudanças de descrição que preservam o estado relacional considerado.

A expressão *grau de liberdade observacional* é útil para o projeto, mas deve ser definida conforme o modelo; ela não é automaticamente igual à dimensão de um espaço físico.

## 11. Caso linear — Um cálculo explícito de posto

Considere \(\theta=(x,y)^\top\in\mathbb R^2\). A observação inicial é

\[
y_0=C_0\theta,\qquad C_0=\begin{bmatrix}1&1\end{bmatrix}.
\]

\(\operatorname{rank}C_0=1\), logo o núcleo inclui a direção \((1,-1)^\top\). Estados distintos ao longo dessa direção produzem a mesma observação.

Adicionamos uma segunda relação:

\[
C_1=\begin{bmatrix}1&1\\1&-1\end{bmatrix},
\qquad \det C_1=-2\ne0.
\]

Agora \(\operatorname{rank}C_1=2\), o núcleo é trivial, e \(\theta\) é recuperável a partir de \(y=(10,2)^\top\):

\[
\theta=C_1^{-1}y=(6,4)^\top.
\]

**[MODELO]** A relação adicional *não criou* novos graus de liberdade físicos. Ela tornou observável a direção que anteriormente pertencia ao núcleo da observação.

**[LIT]** Há aqui uma ligação direta com a observabilidade de sistemas lineares, em que o posto de uma matriz de observabilidade determina a recuperabilidade do estado. Para sistemas dinâmicos discretos \(x_{t+1}=Ax_t\), \(y_t=Cx_t\), a matriz clássica é

\[
\mathcal O_K=\begin{bmatrix}C\\CA\\\vdots\\CA^{n-1}\end{bmatrix}.
\]

O sistema LTI é observável se \(\operatorname{rank}\mathcal O_K=n\). Nossa arquitetura é mais geral; não se deve identificar automaticamente toda geometria relacional com um sistema linear de controle.

---
# Parte III — Exemplos que testam a proposta

## 12. Exemplo decisivo: os objetos não mudam, a relação muda

Considere dois objetos binários \(A,B\), ambos individualmente observáveis. Há duas hipóteses para a distribuição conjunta de seus resultados:

| Par \((A,B)\) | Hipótese \(H_1\): iguais | Hipótese \(H_2\): opostos |
|:--|--:|--:|
| \((0,0)\) | \(1/2\) | \(0\) |
| \((0,1)\) | \(0\) | \(1/2\) |
| \((1,0)\) | \(0\) | \(1/2\) |
| \((1,1)\) | \(1/2\) | \(0\) |

Sob ambas as hipóteses:

\[
P(A=0)=P(A=1)=P(B=0)=P(B=1)=\tfrac12.
\]

Qualquer teste limitado **à distribuição de \(A\) sozinho** ou **à de \(B\) sozinho** é incapaz de distinguir \(H_1\) de \(H_2\).

Mas a relação \(R(A,B):=[A=B]\) distingue perfeitamente:

\[
P(A=B\mid H_1)=1,
\qquad P(A=B\mid H_2)=0.
\]

**[MODELO] Conclusão:** nenhum objeto novo foi introduzido. Nenhuma marginal individual mudou. **A diferença está integralmente na relação**. Isto é uma realização formal muito próxima da intuição original de que não basta olhar para objetos isolados.

**Sutileza:** conhecer as distribuições marginais não equivale a observar os dois valores conjuntamente. Se forem medidos pares \((A,B)\) em cada tentativa, a informação relacional já estará na distribuição conjunta, ainda que não tenha sido analisada. Uma ampliação pode, portanto, ser analítica e não instrumental.

### Três formas de ampliação presentes no exemplo

1. **Nova relação:** calcular \(A=B\), não apenas o valor individual.
2. **Nova organização do dado:** preservar qual medição de \(A\) corresponde a qual medição de \(B\).
3. **Nova pergunta:** “os resultados se coordenam?” em lugar de “quanto vale cada objeto, isoladamente?”.

Isso demonstra por que a investigação precisa de uma teoria de **relações de múltiplas entradas** e não apenas de uma lista ampliada de atributos individuais.

## 13. O exemplo da Ontologia da Presença Causal — religião e referente metafísico

O documento v0.2 parte de uma pergunta binária tradicional, “Deus existe?”, e desagrega perguntas sobre referente independente, representação mental, comunidade, ritual, comportamento e transmissão de padrões. **[FONTE]**

Defina duas descrições:

- \(d_+\): há um referente metafísico independente;
- \(d_-\): não há esse referente.

É possível **construir** uma geometria cujos observáveis registram somente crenças, rituais, comportamentos e relações sociais e em que as duas descrições concordam integralmente sobre eles:

\[
d_+\sim_A d_-.
\]

A pergunta \(M\), referente à existência independente, assume valores diferentes nas duas descrições; nesse modelo, \(M\) **não é uma função bem definida de** \(X/\sim_A\).

Daí não segue que Deus exista, que não exista, ou que a questão esteja condenada à ausência eterna de resposta. Segue apenas que os observáveis escolhidos **não determinam** aquela distinção. Essa neutralidade condicional é expressamente defendida pelo rascunho de origem. **[FONTE]**

### O que a geometria ampliada permite afirmar positivamente?

Pode haver um padrão representado, transmitido e instanciado por portadores humanos. Em certas condições, uma crença pode participar de uma mudança de comportamento, relação social ou organização institucional. O rascunho chama de *presença causal* a instanciação de um padrão que medeia transformação não trivial. A ideia é separar:

\[
\text{presença do padrão em relações humanas}
\not\Rightarrow
\text{referente independente}.
\]

E igualmente:

\[
\text{presença do padrão em relações humanas}
\not\Rightarrow
\text{ausência de referente independente}.
\]

**[LIMITE]** O predicado `Medeia` da v0.2 é primitivo: sua ocorrência no mundo exige justificação empírica ou uma teoria causal adicional. Uma mudança após um ritual não prova, por si só, que o ritual a causou. A versão 0.2 reconhece explicitamente esse limite.

### O ponto de investigação que vai além do rascunho

A pergunta mais útil passa a ser: **que observável adicional, se admissível e verificável, faria a distinção entre \(d_+\) e \(d_-\) deixar de ser puramente descritiva no modelo?**

Isso é uma questão de projeto de discriminação entre hipóteses. Não pressupõe que tal observável exista nem que seria empiricamente acessível.

## 14. Exemplo de identidade: mesmo padrão, outros portadores

O documento de origem separa sobrevivência biológica, continuidade da mesma consciência e continuidade estrutural de um padrão. **[FONTE]**

Considere a transmissão

\[
p_0\xrightarrow{c_0\to c_1}p_1\xrightarrow{c_1\to c_2}p_2.
\]

A identidade literal \(p_0=p_2\) pode não ser o critério apropriado, porque diferentes portadores, palavras ou práticas podem conservar uma organização comum.

Fixe uma família de invariantes \(\mathcal I=\{I_1,\ldots,I_k\}\) e uma família de transformações admissíveis \(\mathcal T\). Uma definição **possível**, que exige cuidado, seria:

\[
p\approx_{\mathcal I}q
\iff
\forall I\in\mathcal I,\ I(p)=I(q).
\]

Outra, geralmente mais forte, requer uma transformação admissível entre os padrões, ou uma cadeia dessas transformações. Coincidência de alguns invariantes pode ser insuficiente para garantir equivalência estrutural plena.

Perguntas distintas:

- Que características do padrão passam de um portador ao outro?
- Quais deformações são toleradas?
- Quais diferenças produzem linhagens diferentes?
- A transmissão conserva relações apenas **descritivamente**, ou há conexão causal comprovável?
- A preservação do padrão implica preservação do sujeito que o viveu? **Não, sem hipóteses adicionais.**

A geometria permite investigar sobrevivência **estrutural** sem decretar sobrevivência pessoal ou metafísica.

## 15. Exemplo da investigação científica: duas teorias, a mesma predição

Duas teorias \(T_1\) e \(T_2\) podem concordar sobre as medições feitas até hoje, mas discordar sobre um caso ainda não medido. Então a equivalência é relativa à família atual de experimentos:

\[
T_1\sim_{A_0}T_2,
\qquad
T_1\not\sim_{A_1}T_2
\quad (A_0\subseteq A_1).
\]

Isso não prova qual teoria é verdadeira. Revela um **experimento discriminante**. É um caso canônico de subdeterminação por evidência, estudado na filosofia da ciência. **[LIT]**

Importante: a nova experiência pode também mostrar que **ambas** as teorias estavam erradas, exigindo ampliação do próprio conjunto \(X\). Aqui, a operação não é apenas refinamento de partição: é revisão de modelo.

## 16. Exemplo de ciência de dados: variável latente e confusão causal

Suponha que observamos associação entre \(X\) e \(Y\). Duas estruturas podem explicá-la:

```text
Hipótese A: X ----> Y

Hipótese B: X <---- Z ----> Y
```

Mesmo que produzam uma distribuição observacional semelhante para \(X,Y\), elas podem diferir na resposta a uma intervenção \(do(X=x)\). Nesse caso, adicionar \(Z\), definir uma intervenção ou adotar restrições causais adicionais **pode** tornar identificável a questão do efeito de \(X\) sobre \(Y\).

Mas há casos nos quais apenas observar \(Z\) não basta; a identificabilidade depende do modelo causal, das hipóteses e da estrutura de confundimento. **[LIT]**

Esta é uma correção importante para a frase “através das relações observamos causa e consequência”: relações observadas podem indicar caminhos causais, mas não identificam automaticamente a direção da causalidade.

## 17. Exemplo multibase e câmeras — analogia metodológica cuidadosamente limitada

Existe uma afinidade metodológica entre esta investigação e a busca de invariantes entre diferentes câmeras de representação: em ambos os casos, uma fórmula ou coordenada particular não é tomada automaticamente como a essência da estrutura.

Entretanto, **não se deduz** daqui nenhum teorema sobre a geometria posicional C2, as somas `Genuine`, a característica completada ou os momentos do operador de alturas. Esses são objetos matemáticos específicos, com definições e provas próprias. A aproximação é de método:

1. identificar o objeto ou relação de interesse;
2. explicitar a representação/câmera;
3. transportar entre representações por mapas bem definidos;
4. buscar aquilo que permanece preservado;
5. não substituir a genealogia de uma construção por uma identidade posterior.

O projeto filosófico pode aprender com essa disciplina de proveniência, sem absorver indevidamente resultados de outra teoria.

---

# Parte IV — Invariantes, mudanças de câmera e estrutura entre espaços

## 18. A pergunta central: o que permanece quando tudo muda?

A expressão “o que não muda quando tudo muda?” só se torna matemática depois de especificar **o que pode mudar**. Não existe invariante sem uma classe de transformações.

Se um grupo \(G\) atua num espaço \(X\), uma propriedade \(I:X\to V\) é invariante quando

\[
I(g\cdot x)=I(x),\qquad\forall g\in G,\ x\in X.
\]

Mais geralmente, quando transformações relacionam estruturas distintas, usa-se uma família de mapas \(T_{ij}:X_i\to X_j\) e funções de leitura \(I_i\), requerendo comutatividade:

\[
\boxed{I_j\circ T_{ij}=I_i.}
\tag{10}
\]

É uma forma precisa de dizer que uma leitura estrutural sobrevive à troca de câmera.

**[LIMITE]** Não há garantia de que duas representações admitam transporte reversível. Uma projeção pode perder informação; uma reconstrução pode depender de escolhas. Nem todo mapa é uma equivalência ou isomorfismo.

## 19. Invariância não é identidade literal

Um triângulo rotacionado tem coordenadas diferentes, mas as distâncias internas se preservam. Um grafo com vértices renomeados pode preservar incidência e adjacência. Uma frase traduzida pode conservar parte de seu conteúdo e perder outras propriedades.

Esses exemplos usam **grupos diferentes de transformações** e **noções diferentes de preservação**. Por isso, a tese “a relação continua a mesma” precisa responder:

- qual relação?
- entre quais objetos e estados?
- por qual transformação?
- até qual equivalência?
- como testar a preservação?

Não basta dizer que duas expressões “parecem comunicar a mesma ideia”. É preciso indicar quais inferências, vínculos ou operações são conservados.

## 20. Estruturalismo e a objeção da estrutura vazia

Há antecedentes diretos na filosofia da ciência: **realismo estrutural**, discussão entre estrutura e objetos, preservação de relações sob mudança de teoria; **representação científica**, em que modelos não são espelhos passivos dos fenômenos; **subdeterminação**, quando os mesmos dados suportam descrições rivais. **[LIT]**

Há também uma crítica clássica importante ligada ao problema de Newman: se uma teoria diz apenas que “existe alguma relação abstrata com tal estrutura” sem fixar como ela se liga ao mundo, a alegação estrutural pode tornar-se demasiadamente fácil de satisfazer.

Consequência para este projeto:

> Não basta declarar que uma relação é invariante; é preciso explicitar o domínio, os protocolos ou morfismos que identificam a relação, e por que sua preservação é informativa em vez de uma renomeação arbitrária.

Esse cuidado separa uma geometria relacional empiricamente ou logicamente restritiva de uma linguagem em que qualquer padrão pode ser encontrado por redefinição das relações.

## 21. A analogia com liberdade de gauge

A v0.2 já compara diferenças entre descrições da mesma classe relacional com liberdade de gauge, **explicitamente como analogia, não como teoria física de gauge**. **[FONTE]**

A analogia tem valor: duas expressões matemáticas distintas podem corresponder a um mesmo estado relevante sob uma relação de equivalência. Entretanto:

- uma teoria física de gauge requer estrutura matemática específica;
- identificar redundância descritiva exige critério justificado, não mera escolha retórica;
- propriedades não invariantes ainda podem desempenhar papéis operacionais ou auxiliares importantes.

**[LIT]** A literatura filosófica de teorias de gauge registra debates substantivos sobre qual conteúdo é excedente, útil ou fisicamente significativo. Portanto, seria incorreto apresentar a equivalência relacional do rascunho como se resolvesse a interpretação de gauge em geral.

## 22. Um caminho categórico: objetos conhecidos pelas relações que participam

A teoria das categorias oferece uma linguagem potencial: objetos, morfismos, composições e propriedades preservadas por funtores. O lema de Yoneda, em sua forma clássica, mostra que um objeto de uma categoria localmente pequena é determinado, até isomorfismo, pelo funtor representável que registra suas relações (morfismos) com os demais objetos, desde que a naturalidade seja respeitada.

Essa afirmação é uma aproximação matemática **muito próxima** do projeto de valorizar relações em vez de rótulos.

Mas sua força depende de usar a **coleção completa de sondagens categóricas adequada**. Um conjunto parcial de relações pode não distinguir objetos não isomorfos; o princípio de Yoneda não transforma observações limitadas em conhecimento ilimitado.

**Programa [HIPÓTESE]:** representar cada câmera por uma categoria \(\mathcal C_i\), os transportes entre câmeras por funtores e os invariantes compartilhados por observáveis naturais em diagramas de transporte. Não é necessário adotar essa generalização antes de demonstrar que ela acrescenta algo além do modelo elementar de partições.

## 23. Contextos, dependência de relações e colagem

Há duas ferramentas adicionais potencialmente relevantes:

**Análise Formal de Conceitos:** um contexto \((G,M,I)\) relaciona objetos, atributos e incidência, permitindo construir hierarquias de conceitos por uma conexão de Galois. Isso oferece um modelo rigoroso de como relações compartilhadas geram classes conceituais. **[LIT]**

**Feixes e contextualidade:** em cenários com observações disponíveis apenas em determinados contextos, uma coleção de dados locais pode ou não admitir uma descrição global conjunta. A literatura de Abramsky–Brandenburger apresenta um formalismo de feixes para contextualidade, ligado à existência de seções globais. **[LIT]**

Essa segunda ligação é promissora porque a ideia original diz que diferentes conjuntos de objetos e relações podem oferecer graus diferentes de observação. Porém **não** se deve inferir contextualidade quântica da mera incompletude de uma descrição. A aplicação de feixes seria uma extensão técnica condicionada à construção de cenários de medição apropriados.

## 24. Uma categoria de relações entre geometrias

**[HIPÓTESE]** Pode-se definir uma estrutura de comparação entre geometrias, com:

- objetos: geometrias observacionais \((X,A,h)\);
- setas: traduções \(F:X\to X'\) associadas a mapas de observáveis que preservam os resultados antigos;
- composição: composição das traduções que satisfazem essas condições;
- equivalência: mapas invertíveis que preservam a estrutura relevante.

A investigação central seria identificar **invariantes de transporte**: perguntas \(Q\) e \(Q'\) compatíveis com o mapa, isto é, \(Q'=Q\circ F^{-1}\) quando o mapa é uma equivalência adequada, ou a condição geral \(Q'\circ F=Q\) quando há apenas um mapa de ida.

A advertência é essencial: sem uma definição exata de morfismo e das propriedades conservadas, essa construção permanece somente um projeto.

---

# Parte V — Causalidade e presença

## 25. Por que uma relação observada não determina, por si só, uma causa?

Considere duas variáveis estatisticamente associadas. A distribuição pode ser compatível com \(X\to Y\), \(Y\to X\) ou \(X\leftarrow Z\to Y\), dependendo das hipóteses. Observar correlação descreve uma relação; atribuir causalidade exige distinguir mecanismos e o que ocorreria sob intervenções ou contrafactuais.

Uma maneira clássica de formular o salto causal é trabalhar com modelos estruturais, por exemplo:

\[
Y=f_Y(X,U_Y),
\qquad
X=f_X(U_X),
\]

em que uma intervenção \(do(X=x)\) substitui a equação estrutural de \(X\) por um valor imposto. A distribuição \(P(Y\mid do(X=x))\) não é, em geral, igual a \(P(Y\mid X=x)\). **[LIT]**

Logo, uma *geometria causal* deve incluir uma família de intervenções ou hipóteses causais adicionais, e não meramente rebatizar a família de correlações existentes.

## 26. Proposta de arquitetura causal em três camadas

**Camada R — Relações:** quem está ligado a quem, que padrões ocorrem juntos, que transformações foram registradas.

**Camada T — Dinâmica temporal:** ordenação de eventos, persistência, feedback, condições iniciais e transições.

**Camada C — Causalidade:** intervenções, contrafactuais, mecanismos ou hipóteses justificadas que selecionam explicações causais entre as observacionalmente possíveis.

A presença causal do rascunho pode ser conservada nessa arquitetura como um predicado **condicional à validade da relação de mediação**:

\[
\operatorname{PresenteCausalmente}(p,t)
\iff
\exists c,s_0,s_1:\ 
\operatorname{Instancia}(c,p,t)
\land\operatorname{Medeia}(c,p,s_0,s_1,t)
\land s_0\ne s_1.
\]

Não se conclui \(\operatorname{Medeia}\) apenas de \(s_0\ne s_1\). Essa distinção preserva o núcleo do documento de origem e reduz o risco de confundir transformação com causa.

## 27. Uma consequência: ampliar relações pode invalidar uma explicação causal anterior

O teorema de refinamento garante monotonicidade **da discriminação** sob inclusão de testes estáveis. Ele **não** garante monotonicidade da verdade das hipóteses, da confiança em explicações ou da inferência causal.

Um novo fator de confusão, uma medição mal calibrada ou uma hipótese rival podem mudar radicalmente a explicação preferida. Isso não contradiz o teorema; apenas mostra que *ser capaz de distinguir mais* não é sinônimo de *já conhecer a causa correta*.

---
# Parte VI — Consciência como expansão do campo relacional

## 28. Três sentidos de “consciência” que não devem ser confundidos

A frase fundadora deste trabalho é **“ampliar o espaço geométrico da minha consciência”**. Para investigá-la seriamente, é preciso desambiguar *consciência*:

1. **Consciência como acesso cognitivo:** informação disponível para raciocinar, relatar, relacionar e orientar ações.
2. **Metacognição e autorrepresentação:** capacidade de reconhecer limites dos próprios modelos, formular perguntas sobre o próprio conhecimento e revisar critérios de observação.
3. **Experiência fenomenal:** o caráter subjetivo de *como é* vivenciar alguma coisa.

**[LIT]** A pesquisa contemporânea distingue acesso, experiência subjetiva e autorreflexão; não há consenso em reduzi-los a uma única variável. A abordagem da presente investigação modela principalmente os sentidos **1 e 2**. Nada no teorema de refinamento deduz a experiência fenomenal nem resolve o problema mente-corpo.

## 29. Modelo mínimo de estado cognitivo relacional

Considere um agente com:

\[
\mathcal K_t=(X_t,A_t,B_t,L_t,\mathcal Q_t),
\]

em que:

- \(X_t\): hipóteses ou estados que o agente consegue representar no tempo \(t\);
- \(A_t\): observáveis, conceitos ou testes de que dispõe;
- \(B_t\): crenças ou pesos atribuídos às hipóteses;
- \(L_t\): repertório de relações, inferências e traduções;
- \(\mathcal Q_t\): perguntas que consegue formular.

A **expansão do espaço geométrico da consciência**, nessa proposta operacional, pode modificar qualquer um desses elementos:

\[
\mathcal K_t\longrightarrow\mathcal K_{t+1}.
\]

Nem toda modificação é melhoria. Um conceito inadequado pode acrescentar falsas conexões; uma crença dogmática pode tornar um espaço aparentemente mais organizado, mas menos responsivo à evidência. Assim, o projeto necessita de critérios de **correção**, **calibração**, **coerência**, **capacidade discriminativa** e **revisabilidade**.

## 30. Quatro operações cognitivas distintas

### 30.1 Descobrir um objeto antes ignorado

O observador passa a representar um terceiro evento \(C\), embora antes só considerasse \(A\) e \(B\). A ampliação pode revelar \(A\leftrightarrow C\leftrightarrow B\) e reformular a interpretação da relação \(A\leftrightarrow B\).

### 30.2 Descobrir uma relação entre objetos já conhecidos

O observador já conhecia os objetos \(A\) e \(B\), mas não havia perguntado se suas variações eram sincronizadas. Não há inclusão de um objeto novo: há **mudança do esquema relacional**.

### 30.3 Descobrir que duas formulações são equivalentes

O observador aprende a transformar descrições diferentes numa estrutura comum e deixa de tratar redundância verbal como diferença do fenômeno. A expansão acontece por **compressão estrutural**: menos distinções espúrias, mais estabilidade de invariantes.

### 30.4 Descobrir um limite de identificabilidade

O observador reconhece que uma pergunta não pode ser respondida a partir da família de observações atual, por mais engenhosa que seja a interpretação. Isso orienta a procura de novas relações e evita inferências não justificadas.

**Síntese:** ampliar a consciência pode significar **adicionar**, **distinguir**, **relacionar**, **reclassificar** ou **reconhecer limites**. O crescimento não deve ser medido apenas pela quantidade de objetos ou proposições acumulados.

## 31. Profundidade, extensão, resolução e invariância

É possível construir indicadores separados, sem fingir que existe uma métrica universal de consciência:

- **Extensão representacional:** quantos tipos de fenômenos e perspectivas cabem no modelo.
- **Resolução discriminativa:** quantas classes de estado a família de testes consegue distinguir.
- **Capacidade relacional:** quantas estruturas relevantes podem ser formuladas e comparadas, descontada a redundância.
- **Profundidade inferencial:** quantas etapas justificadas de inferência podem ser encadeadas.
- **Robustez invariante:** quais resultados sobrevivem a mudanças de representação e revisão legítima dos dados.
- **Calibração epistêmica:** quão bem crenças e graus de confiança acompanham resultados verificáveis.

**[HIPÓTESE]** Uma investigação empírica poderia operacionalizar alguns desses indicadores em tarefas controladas de aprendizagem, classificação e inferência. Nenhum deles é, isoladamente, medidor validado de consciência fenomenal.

## 32. A expansão observacional nem sempre exige mais informação externa

O exemplo das distribuições marginais mostra que uma relação pode estar codificada em dados já disponíveis, mas não ter sido computada. Isso sugere distinguir:

\[
\text{dados disponíveis}
\quad\ne\quad
\text{relações extraídas desses dados}
\quad\ne\quad
\text{relações justificadas}.
\]

Em termos cognitivos, uma pessoa pode adquirir uma perspectiva nova sem receber um novo dado sensorial, por reorganização de representações preexistentes. Mas essa reorganização só adquire conteúdo sobre o mundo se preservar e respeitar as condições pelas quais os dados foram produzidos.

Essa observação se aproxima de discussões sobre acesso global a informação e integração de conteúdos nas teorias da consciência, sem implicar identidade com qualquer teoria neurocientífica específica. **[LIT]**

## 33. Proposta de protocolo experimental simples

**[HIPÓTESE / desenho experimental]** Construir tarefas com pares de hipóteses indistinguíveis em um primeiro conjunto de pistas e distinguíveis depois de uma relação adicional.

Exemplo:

1. mostrar a participantes dois sistemas com marginais individuais iguais;
2. solicitar previsões ou julgamentos de equivalência;
3. disponibilizar dados conjuntos e ensinar a noção de correlação;
4. pedir reclassificação dos sistemas e explicação do motivo;
5. testar transferência para um caso novo, com rótulos e objetos trocados;
6. verificar se o participante preserva a **relação** sem confundi-la com a aparência dos objetos.

**Predição testável:** pessoas que compreenderem a estrutura relacional deverão conseguir distinguir sistemas novos sob renomeação e mudanças superficiais de representação melhor do que pessoas que decoraram apenas exemplos particulares.

A predição é plausível, mas não foi testada por este documento; requer controles adequados, amostra, análise estatística e avaliação de explicações alternativas.

---

# Parte VII — Informação, incerteza e qualidade das observações

## 34. Quando observáveis têm ruído

A teoria elementar usou funções determinísticas \(h_a(x)\). Na prática, um observável pode produzir resultados estocásticos \(Y_a\) com distribuição condicional \(P(Y_a\mid X=x)\).

Uma equivalência mais apropriada é

\[
x\sim_A^{\mathrm{est}}y
\iff
P(Y_A\mid X=x)=P(Y_A\mid X=y),
\]

em que \(Y_A\) denota a **observação conjunta** dos protocolos da família \(A\). A comparação das distribuições conjuntas evita o erro de inferir igualdade de relações a partir de marginais idênticas.

Diferenciar distribuições não significa poder determinar sem erro a hipótese a partir de uma única amostra. Isso depende de sobreposição de distribuições, número de repetições e condições experimentais.

## 35. Monotonicidade da informação condicional

Se \(Q\), \(Y_0\) e \(Y_1\) são variáveis aleatórias discretas numa mesma distribuição conjunta, então

\[
\boxed{H(Q\mid Y_0,Y_1)\le H(Q\mid Y_0).}
\tag{11}
\]

**[MAT]** A desigualdade vem da não negatividade de informação mútua condicional:

\[
H(Q\mid Y_0)-H(Q\mid Y_0,Y_1)=I(Q;Y_1\mid Y_0)\ge0.
\]

Isso formaliza que observar \(Y_1\) além de \(Y_0\), considerando o mesmo modelo probabilístico, não aumenta a incerteza condicional **média** sobre \(Q\). O ganho pode ser nulo.

**[LIMITE]** Para uma realização particular, a surpresa ou a incerteza subjetiva posterior podem aumentar; a desigualdade envolve entropias esperadas de um modelo probabilístico bem definido, não a experiência psicológica universal de “aprender algo”.

## 36. Informação existente, informação acessível e informação inventada

Uma mudança de representação reversível não cria informação nova sobre o estado. Uma transformação com perda de informação não pode, por si só, permitir recuperação de distinções apagadas. Uma nova medição pode acrescentar evidência; uma nova inferência pode tornar acessível informação implícita no registro.

Este ponto se relaciona ao princípio de processamento de dados e à teoria da decisão estatística. **[LIT]**

Propomos distinguir os efeitos de uma expansão:

- **Descoberta externa:** dados adicionais efetivamente obtidos.
- **Extração interna:** cálculo de relações já codificadas em observações conjuntas.
- **Mudança de linguagem:** equivalência de representação sem ganho observacional.
- **Hipótese não verificada:** possibilidade concebida mas não justificada.

Cada uma merece uma anotação diferente no histórico do projeto.

---

# Parte VIII — Limites condicionais, contraexemplos e auditoria conceitual

## 37. Sete exageros a evitar

### Exagero 1 — “Toda relação é uma relação causal”

**Não.** Relações podem ser lógicas, estatísticas, geométricas, temporais ou descritivas sem direção causal demonstrada.

### Exagero 2 — “Toda ampliação melhora a resposta a qualquer pergunta”

**Não.** Observáveis redundantes ou irrelevantes a \(Q\) podem não aumentar a identificabilidade de \(Q\).

### Exagero 3 — “Se a geometria atual não distingue, nada pode distinguir”

**Não.** A indistinção é relativa ao conjunto de observáveis e hipóteses atualmente admitidos. Outro experimento ou modelo pode separar estados.

### Exagero 4 — “Se duas descrições são equivalentes, são metafisicamente idênticas”

**Não.** Equivalência observacional é definida relativamente a um espaço e a uma família de testes. Identidade metafísica é uma afirmação adicional.

### Exagero 5 — “Mudar palavras sempre preserva o mesmo fenômeno”

**Não.** Uma tradução pode apagar distinções; duas narrativas semelhantes podem ter implicações diferentes. O mapa de transformação precisa ser justificado.

### Exagero 6 — “A teoria matemática explica consciência fenomenal”

**Não.** Os resultados demonstram propriedades de partições, observações e perguntas. A passagem à experiência subjetiva exige teoria e evidência adicionais.

### Exagero 7 — “A teoria elimina a necessidade de objetos”

**Não.** Ela dá primazia *metodológica* às relações. A própria definição usa objetos, estados, portadores e domínios. O realismo estrutural é debatido e não obriga à eliminação das entidades.

## 38. Três contraexemplos construtivos

**A. Objeto novo sem relação nova.** Acrescentar um símbolo \(z\) completamente desconectado e nunca observado não altera a assinatura dos estados originais. A expansão ontológica nominal não implica aumento observacional.

**B. Observável novo redundante.** Medir \(x+y\) e acrescentar apenas \(2(x+y)\) não elimina a direção de indeterminação \((1,-1)\). Um teste numericamente diferente pode não ser relacionalmente independente.

**C. Invariante insuficiente.** Dois grafos podem ter o mesmo número de vértices e arestas e não ser isomorfos. Preservar algumas grandezas não basta para identificar a estrutura completa. É necessário verificar a suficiência do conjunto de invariantes para o objetivo.

## 39. Critério de honestidade intelectual para enunciados

Um enunciado do projeto deve ser classificado em uma das categorias:

| Categoria | O que é permitido afirmar | Que evidência se exige |
|:--|:--|:--|
| Definição | O significado formal atribuído a um termo | Assinatura sem ambiguidades |
| Teorema condicional | Conclusão sob hipóteses explícitas | Demonstração, idealmente prova formal |
| Exemplo testemunha | Um comportamento é matematicamente possível | Construção e verificação |
| Observação empírica | Algo ocorreu em determinado sistema | Dados, protocolo e incerteza |
| Interpretação | Uma leitura é coerente com o material | Argumento e alternativas |
| Hipótese | Uma extensão poderia explicar um fenômeno | Critérios de falsificação/teste |
| Questão aberta | O problema está formulado, sem decisão | Delimitação e motivação |

**Uma demonstração formal confirma consequências dos axiomas e definições; ela não garante a verdade física dos próprios axiomas.** Essa separação é particularmente importante em aplicações filosóficas.

---

# Parte IX — Programa matemático de aprofundamento

## 40. Resultados elementares a formalizar primeiro

A ordem proposta não depende de avanços filosóficos difíceis:

1. equivalência observacional \(\sim_A\) é uma relação de equivalência;
2. ampliação \(A_0\subseteq A_1\) implica refinamento de partição;
3. existência do mapa canônico entre quocientes e sua sobrejetividade;
4. identificabilidade de \(Q\) equivale à fatoração pelo quociente;
5. identificabilidade é monótona com o aumento de observáveis;
6. critérios de discriminação por pares;
7. caracterização de observáveis redundantes;
8. igualdade \(\sim_{A\cup B}=\sim_A\cap\sim_B\);
9. resultados de seleção finita para conjuntos de estados finitos;
10. contraexemplos para unicidade de famílias mínimas.

São enunciados com demonstrações matemáticas diretas. A formalização Lean será uma **verificação de implementação**, não descoberta automática de conteúdo metafísico.

## 41. Protótipo Lean 4 proposto — não compilado nesta investigação

O código abaixo é um **esboço de arquitetura e provas**, deliberadamente pequeno. O ambiente usado para esta pesquisa não dispõe de executável Lean para testar a compilação. Portanto, nenhuma declaração abaixo deve ser citada como “verificada pelo kernel”.

```lean
import Mathlib.Data.Set.Basic

universe u v

namespace GeometriaPossibilidades

variable {Estado : Type u} {Prova : Type v}

-- A interpretação de cada protocolo num estado.
variable (observa : Prova → Estado → Bool)

-- A família A de provas define indistinguibilidade.
def Indistinguivel (A : Set Prova) (x y : Estado) : Prop :=
  ∀ a, a ∈ A → observa a x = observa a y

-- Uma pergunta é identificável se não discorda dentro das fibras.
def Identificavel (A : Set Prova)
    (Q : Estado → Prop) : Prop :=
  ∀ x y, Indistinguivel observa A x y → (Q x ↔ Q y)

-- Mais provas preservam toda discriminação já disponível.
theorem refinamento
    {A₀ A₁ : Set Prova}
    (hinc : A₀ ⊆ A₁)
    {x y : Estado}
    (hxy : Indistinguivel observa A₁ x y) :
    Indistinguivel observa A₀ x y := by
  intro a ha
  exact hxy a (hinc ha)

-- Uma pergunta identificável permanece assim após ampliação.
theorem identificavel_mono
    {A₀ A₁ : Set Prova}
    (hinc : A₀ ⊆ A₁)
    {Q : Estado → Prop}
    (hQ : Identificavel observa A₀ Q) :
    Identificavel observa A₁ Q := by
  intro x y hxy
  exact hQ x y (refinamento observa hinc hxy)

end GeometriaPossibilidades
```

### Arquitetura de arquivos para o Lean

```text
Formal/
  Observabilidade/
    Definicoes.lean
    Equivalencia.lean
    Refinamento.lean
    Identificabilidade.lean
    PerguntasEQuocientes.lean
    DiscriminantesFinitos.lean
  Invariantes/
    TransformacoesAdmissiveis.lean
    TransporteEntreCameras.lean
  Exemplos/
    DuasVariaveis.lean
    CorrelacaoSemMudancaMarginal.lean
    ReferenteNaoIdentificavel.lean
  Causalidade/
    PresencaCondicional.lean
```

**Critério de aceitação formal:** prova compilada num projeto com versão Lean e dependências fixadas, sem axiomas introduzidos inadvertidamente, sem `sorry`/`admit`, com testes de modelos testemunha. Não declarar mais do que a assinatura do teorema efetivamente estabelece.

## 42. Generalização probabilística

A etapa seguinte substituirá os resultados booleanos por distribuições condicionais, com questões como:

- quando duas hipóteses geram a mesma lei conjunta de medições?
- quais protocolos maximizam a distância estatística entre hipóteses?
- qual a relação entre refinamento de experimentos e o conceito de experimento mais informativo na ordem de Blackwell?
- quando uma pergunta se torna estimável com erro controlado, em lugar de apenas identificável no limite ideal?
- como combinar observações custosas e escolher a próxima prova?

Essas questões conectam a geometria à teoria de informação, projeto de experimentos e inferência estatística. **[LIT + HIPÓTESE]**

## 43. Generalização dinâmica e relacional

Em sistemas que evoluem no tempo, a assinatura pode ser uma trajetória \(\bigl(h_a(x_t)\bigr)_{t=0}^T\), não uma observação estática. Novas relações temporais podem distinguir estados iniciais que uma medição instantânea não distingue.

Relações entre *vários* objetos pedem estruturas de aridade \(k\), hipergrafos ou modelos relacionais; relações entre observações de contextos diferentes pedem regras de compatibilidade. Essas generalizações não devem ser acrescentadas todas de uma vez: cada uma precisa resolver um exemplo que o núcleo anterior não modela adequadamente.

## 44. A “geometria mínima” como problema computacional

O critério (6) transforma a seleção de observáveis em um problema de cobertura: cada observável separa determinado subconjunto de pares de estados com respostas diferentes, e buscamos cobrir todos esses pares com menor custo possível.

Em instâncias finitas, pode-se implementar:

1. enumeração das hipóteses \(X\);
2. geração dos pares \((x,y)\) com \(Q(x)\ne Q(y)\);
3. cálculo de quais pares cada prova \(a\) separa;
4. escolha de um conjunto discriminante;
5. verificação de minimalidade e busca de alternativas;
6. emissão de certificado dos pares cobertos.

Se a família de observáveis admissíveis não cobre algum par relevante, o algoritmo deve reportar **não identificabilidade relativa à família**, e não a falsidade ou ausência da realidade a que a pergunta se refere.

---
# Parte X — Tese consolidada e agenda de investigação

## 45. Formulação canônica proposta

> **Geometria das Possibilidades — formulação fundacional (v0.1).** Uma geometria investigativa é uma estrutura de objetos ou estados, relações, restrições, transformações e observáveis que determina quais configurações são admitidas e quais diferenças podem ser distinguidas. A informação de um objeto isolado não esgota o conteúdo das relações em que ele participa. Ampliar o espaço geométrico de observação significa incorporar objetos, relações ou protocolos antes ausentes, preservando explicitamente aquilo que continua válido da estrutura anterior. Sob a inclusão de observáveis com domínio e interpretações fixos, a equivalência observacional só pode ser refinada: estados antes indistinguíveis podem tornar-se distinguíveis. Uma pergunta é identificável nesse espaço exatamente quando sua resposta é constante nas classes de indistinguibilidade. Invariantes exprimem propriedades preservadas por transformações admissíveis de representação; a determinação de quais transformações e observáveis correspondem ao fenômeno exige justificação própria. Aplicada à consciência em sentido cognitivo, a ampliação geométrica descreve o alargamento das relações concebíveis, discrimináveis e justificáveis, sem pretender, por isso só, explicar a experiência subjetiva.

A formulação preserva cinco intuições de origem:

1. geometria é mais ampla que a noção de distância;
2. o objeto isolado não é a unidade suficiente da investigação;
3. o desconhecimento de uma relação pode limitar a resposta a uma pergunta;
4. ampliar a geometria pode oferecer capacidade de distinção antes ausente;
5. o alvo mais profundo é reconhecer estruturas invariantes entre representações.
Acrescenta cinco distinções para aumentar o rigor:

1. ampliar objetos \(\ne\) ampliar relações \(\ne\) ampliar medições;
2. possibilidade física \(\ne\) compatibilidade com observações;
3. identificabilidade \(\ne\) certeza empírica obtida;
4. correlação \(\ne\) causalidade;
5. equivalência observacional \(\ne\) identidade metafísica.

## 46. Onde está a contribuição intelectual possível?

O material matemático elementar — partições, quocientes, fatoração de funções, observabilidade linear, informação condicional — possui antecedentes bem estabelecidos. A tese de que relações e invariantes importam também tem antecedentes importantes no estruturalismo e na filosofia da representação.

Portanto, a originalidade, se desenvolvida, deve ser procurada em **uma arquitetura integradora com definições e resultados próprios**, não na reivindicação de que a importância das relações ou o conceito de observabilidade foram descobertos aqui.

Possíveis contribuições de pesquisa que ainda precisariam ser demonstradas:

**P1 — Geometria mínima relativa a uma pergunta.** Desenvolver critérios e algoritmos que encontram famílias mínimas ou economicamente ótimas de relações discriminantes em diferentes tipos de domínios.

**P2 — Transporte de identificabilidade entre câmeras.** Caracterizar quando uma pergunta identificável numa representação continua identificável em outra, inclusive com traduções não inversíveis.

**P3 — Gramática da expansão relacional.** Classificar formalmente operações de inclusão de objetos, inclusão de relações, inclusão de protocolos e revisão de restrições, distinguindo seus efeitos no conjunto de hipóteses e nos quocientes.

**P4 — Presença causal sem excesso metafísico.** Formalizar padrões, portadores, transformação, transmissão e intervenções sem confundir presença relacional com referente independente.

**P5 — Aprendizagem por invariância.** Investigar se ensinar estruturas que sobrevivem a renomeações melhora a capacidade de transferência a problemas novos.

**P6 — Limites relativos de observação.** Construir certificados explícitos de não identificabilidade para uma determinada família de observáveis, sem extrapolar a conclusão para qualquer futura ampliação do modelo.

## 47. Perguntas de pesquisa prioritárias

1. Quando a adição de um **objeto** gera inevitavelmente relações novas, e quando ela é apenas expansão nominal?
2. Como definir a relação de “ser a mesma estrutura” entre câmeras sem assumir previamente a conclusão desejada?
3. É possível identificar uma base mínima de relações para cada pergunta? Como tratar custos e múltiplas bases mínimas?
4. Qual a diferença operacional entre **uma nova medição** e **uma nova análise dos mesmos dados**?
5. Como a noção de identidade por invariantes lida com padrões transmitidos, deformados ou bifurcados?
6. Que observáveis distinguem presença causal efetiva de mera presença simbólica?
7. Quando o fracasso de uma pergunta é de formulação, identificabilidade, qualidade dos dados ou restrição do próprio espaço de estados?
8. Como comunicar dois modelos incompatíveis com resultados observacionais idênticos sem atribuir indevidamente falsidade ou verdade metafísica?
9. Em quais casos categorias e feixes oferecem ganho sobre quocientes e partições?
10. Como medir transferibilidade de uma relação entre problemas com objetos superficialmente diferentes?
11. Há formas de ampliar observabilidade **sem** aumentar o número de sensores, apenas pela combinação de relações já medidas?
12. Qual seria um contraexemplo conclusivo para uma afirmação forte desta teoria, e que condições deveriam ser explicitadas antes de publicá-la?

## 48. Metodologia recomendada

Para cada linha do projeto, manter uma ficha:

```text
PERGUNTA:                 formulação precisa
DOMÍNIO:                  quais estados e objetos são admitidos
OBSERVÁVEIS:              o que se pode de fato medir/comparar
RELAÇÕES:                 quais vínculos são propostos
RESTRIÇÕES:               hipóteses explícitas
TRANSFORMAÇÕES:           mudanças admissíveis de descrição
EQUIVALÊNCIA:             quando dois estados são indistinguíveis
INVARIANTES:              quais propriedades devem sobreviver
RESULTADO:                demonstração, exemplo ou teste
FORÇA DA CONCLUSÃO:       exatamente o que foi estabelecido
EXPANSÃO POSSÍVEL:        nova relação que mudaria a análise
PROVENIÊNCIA:             arquivo, linhas, referências e versão
```

Esta ficha tem um papel prático importante: evita que uma interpretação atual seja tratada como barreira absoluta a investigações futuras, ao mesmo tempo que evita converter hipóteses em teoremas.

## 49. Organização editorial por níveis

Uma sugestão de estrutura:

```text
geometria-das-possibilidades/
├── README.md
├── LICENCA.md                  # após escolha explícita de licença
├── fundamentos/
│   ├── 00-genealogia-e-definicoes.md
│   ├── 01-geometria-relacional.md
│   ├── 02-observabilidade-e-equivalencia.md
│   ├── 03-identificabilidade-e-perguntas.md
│   ├── 04-invariantes-e-mudancas-de-camera.md
│   └── 05-ampliacao-geométrica.md
├── investigacoes/
│   ├── geometria-minima-por-pergunta.md
│   ├── informacao-e-observacao.md
│   ├── causalidade-e-intervencao.md
│   ├── consciencia-e-cognicao.md
│   └── estrutura-entre-geometrias.md
├── exemplos/
│   ├── duas-equacoes.md
│   ├── relacao-sem-alterar-objetos.md
│   ├── objeto-novo-sem-ganho-observacional.md
│   ├── causalidade-e-confundimento.md
│   └── perguntas-metafisicas.md
├── ontologia-da-presenca-causal/
│   ├── README.md
│   └── referencias-da-versao-0.2.md
├── formal/
│   ├── lakefile.toml
│   └── Formal/
├── referencias/
│   └── bibliografia-comentada.md
└── documentos/
    └── GEOMETRIA_DAS_POSSIBILIDADES_INVESTIGACAO_FUNDACIONAL_v0.1.md
```

**Nota:** os nomes de arquivos acima são uma proposta de organização, não arquivos já existentes. A presença de `lakefile.toml` ou `LICENCA.md` no desenho não significa que dependências ou licenciamento tenham sido definidos.

## 50. Nome e descrição do repositório

### Recomendação principal

**Nome público:** Geometria das Possibilidades  
**Identificador sugerido:** `geometria-das-possibilidades`

**Descrição curta sugerida para GitHub:**

> Investigação em português sobre a geometria relacional das possibilidades e impossibilidades: objetos, relações, observabilidade, identificabilidade, invariantes, causalidade e ampliação da consciência.

**Motivo da escolha:** o nome apresenta o princípio mais amplo em vez de confundi-lo com uma aplicação particular. O estudo da consciência pertence ao projeto, mas a construção matemática também se aplica a ciência, representação, causalidade, sistemas dinâmicos e ontologia.

### Alternativas, caso se prefira maior tecnicidade

- `geometria-relacional` — curto, mas genérico e sem destacar a identificabilidade.
- `geometria-da-observabilidade` — tecnicamente preciso, porém faz a teoria parecer restrita a medição.
- `espacos-de-possibilidades` — amplo, mas enfraquece a centralidade das relações e invariantes.

**Recomendação editorial:** adotar `Geometria das Possibilidades` como projeto e `Geometria Relacional da Observabilidade` como nome do núcleo matemático.

## 51. Sequência de desenvolvimento proposta

**Etapa A — fixar a linguagem.** Separar objetos, estados, relações, observáveis, perguntas, transformações, equivalências e invariantes. Estabelecer um glossário normativo.

**Etapa B — certificar o núcleo matemático.** Implementar e verificar os teoremas da Parte II em Lean, mantendo registros de hipóteses e exemplos finitos.

**Etapa C — construir um catálogo de testemunhas.** Exemplos em que a ampliação distingue, não distingue, é redundante, revisa o modelo ou preserva invariantes.

**Etapa D — desenvolver identificabilidade aplicada.** Ligar seleção de observáveis a projeto de experimentos, modelos dinâmicos e observações estatísticas.

**Etapa E — aplicar à ontologia e à consciência.** Retomar a v0.2 como um caso concreto, preservando presença causal, transmissão de padrões, neutralidade metafísica condicional e distinções sobre identidade.

**Etapa F — teoria entre geometrias.** Somente depois de dispor de exemplos que exijam transportes entre diferentes espaços, estudar linguagem categórica e estruturas de colagem.

Nada nessa ordem pretende impor que a pesquisa pare quando uma etapa ainda não estiver completa; ela apenas reduz dependências conceituais ocultas.

---

# Parte XI — Bibliografia comentada e proveniência

As referências externas abaixo são **pontos de comparação** e não provas de originalidade. São selecionadas por proximidade conceitual ou matemática. A bibliografia não afirma que todos os textos adotem a presente proposta; pelo contrário, a distinção entre aproximação e identidade é parte do método.

## 52. Fonte primária deste projeto

**[S0]** *Ontologia da Presença Causal — Geometria Relacional da Existência, da Representação e da Sobrevivência*, v0.2, arquivo fornecido pelo autor: `ONTOLOGIA_DA_PRESENCA_CAUSAL_v0.2(2).md`.

Partes especialmente relevantes: I (definição relacional de geometria), II (equivalência e invariantes), III (perguntas bem formuladas), IV (caso religioso), V–VI (presença causal e sobrevivência), VII (arquitetura Lean), X (programa de pesquisa). O presente documento **não verifica a compilação** do código Lean mencionado no rascunho de origem; a própria v0.2 informa que naquele ambiente o kernel não estava disponível.

## 53. Filosofia da ciência e representação

**[S1] Structural Realism — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/structural-realism/  
Apoia a comparação com realismo estrutural, invariantes e debates entre prioridade ontológica de objetos e relações. Inclui a crítica ligada ao problema de Newman: estrutura abstrata, sem amarração suficiente, pode ser pouco informativa.

**[S2] Scientific Representation — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/scientific-representation/  
Diferencia fenômeno e representação; explica a diversidade de modelos e o problema da adequação representacional. **Revisão substantiva indicada pela fonte: 20/05/2026.**

**[S3] Underdetermination of Scientific Theory — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/scientific-underdetermination/  
Contextualiza a possibilidade de teorias ou hipóteses concordarem sobre evidência disponível sem possuírem o mesmo conteúdo, e a importância de novos experimentos discriminantes.

**[S4] Gauge Theories in Physics — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/gauge-theories/  
Apoia o uso cauteloso da analogia com redundância de descrição e registra controvérsias filosóficas sobre excedente representacional. **Primeira publicação indicada pela fonte: 28/07/2025.**

## 54. Matemática da observação, distinção e informação

**[S5] Games, Full Abstraction and Full Completeness — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/games-abstraction/  
Discute equivalência observacional em semântica de programas: expressões não distinguidas por contextos de teste são tomadas como equivalentes nesse critério. É um antecedente formal particularmente próximo.

**[S6] Observability — IEEE Technology Navigator.**  
https://technav.ieee.org/topic/observability/  
Introduz observabilidade de sistemas, recuperabilidade do estado e o teste de posto da matriz de observabilidade em sistemas lineares.

**[S7] Feedback Systems, capítulo de estimação — Murray e colaboradores (Caltech).**  
https://www.cds.caltech.edu/~murray/books/AM05/pdf/lst-estimation_30Oct2020.pdf  
Referência técnica para testes de observabilidade e ferramentas de reconstrução de estado em sistemas lineares.

**[S8] Formal Concept Analysis in knowledge processing: A survey on models and techniques.**  
https://www.sciencedirect.com/science/article/pii/S0957417413002935  
Relaciona objetos, atributos, incidência e reticulados de conceitos. Útil para enriquecer o vocabulário de relações sem depender inicialmente de categorias abstratas.

**[S9] Yoneda lemma — nLab.**  
https://ncatlab.org/nlab/show/Yoneda%20lemma  
Formaliza como objetos categóricos são caracterizados, até isomorfismo, por uma família completa de morfismos, sob as hipóteses corretas. Não equivale a dizer que qualquer amostra parcial de relações determina um objeto.

**[S10] The Sheaf-Theoretic Structure of Non-Locality and Contextuality — Abramsky e Brandenburger.**  
https://arxiv.org/abs/1102.0264  
Exemplo rigoroso de análise de observações por contextos e dificuldade de compor modelos locais em um modelo global. Uma referência possível para extensões futuras, não para atribuir contextualidade quântica à ontologia relacional.

**[S11] Information Theoretic Inequalities — Dembo, Cover e Thomas.**  
https://isl.stanford.edu/~cover/papers/dembo_cover_thomas_91.pdf  
Fundamenta o emprego de desigualdades informacionais e ferramentas de entropia com hipóteses probabilísticas explícitas.

**[S12] Comparison of Statistical Experiments — Torgersen (prefácio, Cambridge).**  
https://www.cambridge.org/core/books/abs/comparison-of-statistical-experiments/preface/96468C12284FF301F64B262B15DF62CE  
Apresenta a tradição de comparação de experimentos mais e menos informativos, de Blackwell e outros autores.

## 55. Causalidade e consciência

**[S13] An Introduction to Causal Inference — Judea Pearl.**  
https://pmc.ncbi.nlm.nih.gov/articles/PMC2836213/  
Introduz modelos causais, intervenções, identificação de efeitos e distinção entre correlação observada e quantidades intervencionais.

**[S14] Causal Models — Stanford Encyclopedia of Philosophy (edição arquivada).**  
https://plato.stanford.edu/archives/fall2022/entries/causal-models/index.html  
Discussão sobre modelos causais e identificação de estrutura sob hipóteses explícitas. Serve de comparação, não de prova de uma teoria causal própria deste projeto.

**[S15] Consciousness — Stanford Encyclopedia of Philosophy.**  
https://plato.stanford.edu/entries/consciousness/  
Distingue integração representacional, acesso informacional e diferentes sentidos de consciência. Útil para limitar corretamente o alcance cognitivo da proposta.

**[S16] Theories of Consciousness — Anil Seth e Tim Bayne, Nature Reviews Neuroscience (2022).**  
https://www.nature.com/articles/s41583-022-00587-4  
Revisão das teorias neurocientíficas contemporâneas e dos problemas de comparação empírica entre teorias.

**[S17] Active Data Selection and Information Seeking — Parr, Friston e Zeidman (2024).**  
https://www.mdpi.com/1999-4893/17/3/118  
Discute seleção ativa de dados, informação esperada e desenho experimental; aproxima-se da pergunta prática “qual relação devo investigar a seguir?”.

## 56. Mapa de proveniência das afirmações principais

| Afirmação | Natureza | Fundamentação |
|:--|:--|:--|
| Geometria como objetos, relações, restrições, transformações e invariantes | [FONTE] | Documento v0.2 [S0], Partes I–II |
| Perguntas bem formuladas devem respeitar equivalência relacional | [FONTE]/[MAT] | [S0], Partes II–III; fatoração na seção 6 deste documento |
| Ampliação estável de observáveis refina classes | [MAT] | Prova explícita na seção 5 |
| Identificabilidade equivale à fatoração pela assinatura | [MAT] | Prova explícita na seção 6 |
| Família finita suficiente em domínio finito, sob identificabilidade | [MAT] | Demonstração construtiva na seção 9 |
| Mesmas marginais podem ocultar relações conjuntas distintas | [MODELO] | Tabela construída na seção 12 |
| Estruturalismo é antecedente filosófico relevante | [LIT] | [S1]–[S3] |
| Gauge é uma analogia, não uma identificação automática | [FONTE]/[LIT] | [S0] e [S4] |
| Observação não determina automaticamente causalidade | [LIT] | [S13]–[S14] |
| O modelo explica diretamente consciência fenomenal | **Não sustentado** | Limite explicitado nas seções 28–33; [S15]–[S16] |
| Uma geometria mínima de custo ótimo é única | **Falso em geral** | Contraexemplo conceitual na seção 9 |
| Investigar padrões e presença sem decidir referente metafísico | [FONTE] | [S0], Partes IV–VI |
| Testar aprendizagem por invariância como prática cognitiva | [HIPÓTESE] | Proposta nas seções 33 e 46 |

---

# Conclusão geral

A pesquisa partiu da ideia de que **uma geometria é o campo estruturado das possibilidades e impossibilidades, e que a consciência cresce ao conseguir considerar novos objetos e descobrir as relações que eles tornam visíveis**.

O aprofundamento mostrou que essa intuição contém um núcleo matemático preciso:

\[
\boxed{
\text{novos observáveis}
\ \Longrightarrow\ 
\text{refinamento das classes indistinguíveis}
}
\]

sob as condições declaradas. E mostrou que a pergunta mais fértil não é apenas *“quantas coisas consigo observar?”*, mas:

\[
\boxed{
\text{quais relações são suficientes para distinguir}
\atop
\text{as respostas que minha pergunta exige?}
}
\]

Por trás disso aparece uma segunda pergunta, sobre invariância:

> Quando mudo os objetos, as palavras, as coordenadas, os instrumentos ou a descrição, **qual estrutura relacional continua sendo a mesma — e que critério me permite demonstrar essa preservação?**

A primeira pergunta constrói a **geometria da identificabilidade**. A segunda constrói a **teoria dos invariantes entre geometrias**. A Ontologia da Presença Causal oferece um caso filosófico rico para ambas; o estudo da consciência oferece a interpretação motivadora que originou o projeto.

O objetivo não é decretar que todas as perguntas têm resposta, nem retirar significado de perguntas que um modelo limitado não consegue decidir. É construir instrumentos para **distinguir perguntas resolúveis, perguntas não identificáveis na geometria atual, diferenças apenas representacionais e possibilidades legítimas de ampliar a investigação**.

**Formulação curta para orientar o repositório:**

> **Não são os objetos isolados que definem o alcance de uma geometria, mas as relações que podemos estabelecer, distinguir e preservar entre eles.**

---

**Fim do documento — versão 0.1.**
