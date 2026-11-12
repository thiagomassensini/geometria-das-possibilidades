# Ontologia da Presença Causal
## Geometria Relacional da Existência, da Representação e da Sobrevivência

**Versão conceitual 0.2 — coordenadas, invariantes, equivalência relacional e arquitetura revisada em Lean 4**

---

## Resumo

Este documento propõe uma ontologia relacional na qual perguntas de existência não são tomadas como primitivamente binárias. Antes de perguntar se uma entidade “existe”, deve-se especificar a geometria em que a pergunta é formulada, as relações admitidas nessa geometria, as formas de representação utilizadas e as invariantes que distinguem diferenças estruturais de simples diferenças de coordenadas.

O ponto de partida é epistemológico e geométrico: para falar de um fenômeno observado é necessário representá-lo; toda representação seleciona coordenadas. Diferentes descrições podem, portanto, atribuir propriedades distintas ao mesmo fenômeno sem que essas diferenças correspondam a diferenças relacionais no espaço estudado.

A tese central da versão 0.2 é:

> **Uma distinção ontológica possui conteúdo nesta geometria somente quando corresponde a uma distinção relacional. Se duas descrições diferem em uma afirmação, mas preservam todas as relações e invariantes relevantes, essa diferença não define dois estados distintos do espaço relacional; ela é dependente da coordenatização adotada.**

Isso permite reformular certas perguntas tradicionais. Se afirmar ou negar um referente metafísico independente não altera nenhuma relação admissível, nenhum efeito, nenhuma transmissão e nenhuma invariante da geometria considerada, então a pergunta binária “esse referente existe?” não é respondida por “sim”, “não” ou “não sabemos” dentro dessa geometria. Ela simplesmente **não é uma pergunta bem definida sobre o espaço relacional em questão**.

A teoria preserva, contudo, uma noção positiva de presença. Um padrão pode estar mental, social, corporal ou causalmente presente quando é representado, instanciado, transmitido ou participa de transformações por meio de portadores. Essa presença não prova nem refuta um referente metafísico independente.

A mesma estrutura permite analisar sobrevivência depois da morte como continuidade relacional de padrões, sem identificar automaticamente essa continuidade com sobrevivência biológica ou continuidade da mesma consciência.

A proposta continua recebendo o nome de **Ontologia da Presença Causal**. Sua arquitetura é denominada **Geometria Relacional da Existência, da Representação e da Sobrevivência**.

---

# Parte I — Por que geometria?

## 1. Geometria como espaço estruturado de possibilidades

Neste trabalho, “geometria” não significa apenas espaço físico euclidiano. Significa um espaço estruturado em que são especificados:

1. os tipos de objetos ou estados considerados;
2. as relações admissíveis entre eles;
3. as transformações permitidas;
4. as restrições do sistema;
5. as propriedades preservadas sob transformações;
6. os graus de liberdade restantes;
7. os critérios pelos quais duas descrições contam como descrições do mesmo estado relacional.

Uma geometria determina, portanto, não apenas **o que existe dentro de uma descrição**, mas **o que pode variar, o que não pode variar e quais diferenças possuem conteúdo estrutural**.

O conjunto de objetos sozinho não define a geometria. Dois sistemas podem possuir os mesmos objetos e ainda assim apresentar geometrias diferentes se suas relações, transformações admissíveis ou invariantes forem distintas.

Em forma esquemática:

$$
\mathcal G
=
(\mathcal O,\mathcal R,\mathcal T,\mathcal C,\mathcal I),
$$

onde:

- $\mathcal O$ representa os objetos ou estados relevantes;
- $\mathcal R$ representa as relações;
- $\mathcal T$ representa transformações admissíveis;
- $\mathcal C$ representa restrições;
- $\mathcal I$ representa invariantes.

Os graus de liberdade aparecem como aquilo que pode variar sem violar as restrições da geometria.

---

## 2. O fenômeno não é sua representação

Para falar de um fenômeno é necessário codificar informação sobre ele. Essa codificação exige uma forma de representação.

Podemos escrever:

$$
\Phi
\xrightarrow{\rho_C}
D_C,
$$

onde:

- $\Phi$ é o fenômeno considerado;
- $C$ é uma escolha de coordenadas ou sistema de descrição;
- $\rho_C$ é a operação de representação;
- $D_C$ é a descrição produzida nessas coordenadas.

A teoria não identifica automaticamente $D_C$ com $\Phi$.

A descrição contém informação sobre o fenômeno, mas também contém estrutura introduzida pelo sistema usado para descrevê-lo.

Essa distinção é fundamental:

$$
\text{fenômeno}
\neq
\text{representação do fenômeno}.
$$

O acesso ao fenômeno é mediado por representações. Por isso, uma ontologia que não distingue propriedades invariantes de propriedades dependentes de coordenadas corre o risco de atribuir ao fenômeno características produzidas pela própria forma de descrevê-lo.

---

## 3. Coordenadas como artefatos necessários de representação

Uma coordenada não é um erro. Ela é uma ferramenta necessária para tornar uma estrutura representável.

Diferentes coordenatizações podem enfatizar aspectos distintos de uma mesma transformação.

Uma mudança humana pode ser descrita em coordenadas:

- religiosas;
- psicológicas;
- sociais;
- neurobiológicas;
- comportamentais;
- históricas;
- rituais.

Por exemplo, uma mesma trajetória pode receber descrições como:

$$
D_1 = \text{“ação divina”},
$$

$$
D_2 = \text{“reestruturação de crenças”},
$$

$$
D_3 = \text{“efeito de ritual e comunidade”},
$$

$$
D_4 = \text{“mudança de padrões comportamentais e corporais”}.
$$

Essas expressões não são automaticamente equivalentes. Para tratá-las como coordenatizações admissíveis do mesmo fenômeno é necessário identificar uma estrutura preservada entre elas.

Portanto, a teoria não afirma:

> todas as descrições são igualmente verdadeiras.

Ela afirma:

> descrições diferentes podem representar o mesmo estado relacional quando existe uma correspondência entre elas que preserva as relações e invariantes relevantes.

---

## 4. Primazia metodológica das relações

A Ontologia da Presença Causal não precisa negar a existência de objetos. Sua mudança é metodológica: em vez de começar perguntando pela substância intrínseca de um objeto, começa perguntando pelas relações que distinguem estados possíveis.

Em vez de começar por:

$$
\text{“o que é }x\text{?”}
$$

ou:

$$
\text{“}x\text{ existe?”},
$$

começa por perguntas como:

$$
x\;R\;y?
$$

$$
\text{Que transformações ocorrem quando essa relação é realizada?}
$$

$$
\text{Que propriedades permanecem invariantes quando a descrição muda?}
$$

$$
\text{Que diferenças entre descrições correspondem a diferenças no sistema?}
$$

A tese relacional forte da teoria é:

> **Uma diferença ontológica só é identificável nesta geometria quando produz ou acompanha uma diferença relacional no espaço considerado.**

Essa afirmação é relativa à geometria. Uma distinção irrelevante em uma geometria pode tornar-se relevante em outra mais rica.

---

# Parte II — Equivalência, invariantes e graus de liberdade

## 5. Equivalência relacional entre descrições

Considere duas descrições $d_1$ e $d_2$ do mesmo domínio.

Definimos uma relação de equivalência relacional:

$$
d_1 \sim_{\mathcal G} d_2
$$

quando ambas atribuem a mesma estrutura a todas as relações ou observáveis relevantes da geometria $\mathcal G$.

Em uma formulação abstrata:

$$
d_1 \sim_{\mathcal G} d_2
\iff
\forall o\in \mathcal O_{obs},
\quad
H(d_1,o)\leftrightarrow H(d_2,o),
$$

onde $H(d,o)$ significa que o observável relacional $o$ é reconhecido na descrição $d$.

A equivalência relacional não exige que as descrições usem as mesmas palavras, entidades teóricas ou compromissos metafísicos. Exige apenas que, para a geometria estudada, elas não determinem estados relacionais distintos.

---

## 6. Invariantes

Uma propriedade $I$ é invariante quando assume o mesmo valor em descrições relacionalmente equivalentes:

$$
d_1\sim_{\mathcal G}d_2
\Rightarrow
I(d_1)=I(d_2).
$$

Para predicados:

$$
d_1\sim_{\mathcal G}d_2
\Rightarrow
\bigl(P(d_1)\leftrightarrow P(d_2)\bigr).
$$

As invariantes representam aquilo que a teoria considera estruturalmente preservado.

Exemplos possíveis, dependendo da aplicação:

- ocorrência de uma transição entre estados;
- existência de determinado vínculo entre portadores;
- transmissão de um padrão;
- participação de uma comunidade;
- persistência de uma prática;
- reprodução de uma estrutura comportamental;
- redundância de uma memória distribuída;
- determinadas relações temporais ou causais.

A teoria procura separar:

$$
\boxed{\text{propriedades invariantes}}
$$

em contraste com:

$$
\boxed{\text{propriedades dependentes de coordenadas}}.
$$

---

## 7. Propriedades dependentes de coordenadas

Uma propriedade $P$ é dependente de coordenadas quando pode mudar entre duas descrições que continuam relacionalmente equivalentes:

$$
\exists d_1,d_2,
\quad
d_1\sim_{\mathcal G}d_2
\quad\land\quad
\neg\bigl(P(d_1)\leftrightarrow P(d_2)\bigr).
$$

Nesse caso, $P$ não define uma diferença entre estados relacionais da geometria.

A propriedade continua podendo ter significado linguístico, cultural, metafísico ou interno a uma tradição. O que ela não possui é uma diferença correspondente **no espaço relacional definido por $\mathcal G$**.

Essa distinção evita dois erros:

1. declarar que toda diferença de linguagem é uma diferença do fenômeno;
2. declarar que toda diferença de linguagem é irrelevante.

A relevância é determinada pela estrutura preservada e pelas relações admitidas na geometria.

---

## 8. Graus de liberdade e liberdade representacional

Os graus de liberdade de uma geometria são variações permitidas pelas restrições do sistema.

Entretanto, nem toda variação descritiva corresponde a um grau de liberdade relacional.

É útil distinguir:

### 8.1 Grau de liberdade relacional

Uma variação que conduz a um estado não equivalente:

$$
d_1\not\sim_{\mathcal G}d_2.
$$

Há uma diferença estrutural no espaço.

### 8.2 Liberdade representacional

Uma variação que altera a descrição sem alterar o estado relacional:

$$
d_1\sim_{\mathcal G}d_2.
$$

A diferença existe na representação, mas é eliminada quando passamos ao espaço das classes de equivalência.

Essa segunda situação possui uma analogia estrutural com liberdade de gauge em física: descrições distintas podem corresponder ao mesmo estado relevante. A versão 0.2 usa essa analogia apenas como guia matemático. Ela **não afirma ainda que a teoria constitua uma teoria de gauge física em sentido técnico**.

---

## 9. O espaço quociente das descrições

Se $\sim_{\mathcal G}$ é uma relação de equivalência, então podemos considerar o espaço:

$$
\mathcal D / {\sim_{\mathcal G}},
$$

em que descrições relacionalmente equivalentes pertencem à mesma classe.

Uma classe é:

$$
[d]
=
\{d'\mid d'\sim_{\mathcal G}d\}.
$$

O objeto ontológico relevante da geometria não precisa ser cada descrição individual $d$, mas sua classe relacional $[d]$.

Uma propriedade só define uma propriedade do espaço quociente se for invariante dentro de cada classe.

Isso produz um critério rigoroso:

> **Uma pergunta binária sobre descrições é bem formulada no espaço relacional somente se sua resposta for constante em cada classe de equivalência.**

---

# Parte III — Quando uma pergunta deixa de fazer sentido

## 10. Perguntas bem formuladas

Considere uma pergunta representada por um predicado:

$$
Q:\mathcal D\to\{\text{sim},\text{não}\}.
$$

Ela é bem formulada na geometria quando:

$$
d_1\sim_{\mathcal G}d_2
\Rightarrow
Q(d_1)=Q(d_2).
$$

Ou, em linguagem lógica:

$$
d_1\sim_{\mathcal G}d_2
\Rightarrow
\bigl(Q(d_1)\leftrightarrow Q(d_2)\bigr).
$$

Nesse caso, $Q$ desce para o espaço quociente e distingue classes relacionais reais.

---

## 11. Perguntas malformadas relativamente à geometria

Uma pergunta é malformada relativamente à geometria quando sua resposta pode mudar sem que o estado relacional mude:

$$
\exists d_1,d_2,
\quad
d_1\sim_{\mathcal G}d_2
\quad\land\quad
Q(d_1)\neq Q(d_2).
$$

Isso é diferente de dizer:

> “não sabemos a resposta”.

“Não sabemos” expressa limitação epistemológica diante de uma pergunta considerada bem definida.

Aqui a afirmação é estrutural:

> **a pergunta não seleciona dois estados diferentes do espaço que está sendo estudado.**

Portanto, as respostas “sim” e “não” podem representar escolhas de coordenadas que não correspondem a graus de liberdade relacionais.

---

## 12. Princípio da Eliminação Relacional de Pseudodiferenças

Podemos formular o princípio central da versão 0.2:

> **Se duas descrições diferem apenas em propriedades que não alteram nenhuma relação ou invariante da geometria, essa diferença não define uma diferença ontológica dentro dessa geometria.**

Formalmente:

$$
d_1\sim_{\mathcal G}d_2
$$

implica que qualquer predicado ontologicamente bem definido $P$ deve satisfazer:

$$
P(d_1)\leftrightarrow P(d_2).
$$

Se isso falha, então $P$ depende da coordenatização e não é uma propriedade da classe relacional.

---

# Parte IV — O caso religioso

## 13. Reformulando “Deus existe?”

A pergunta:

$$
\operatorname{Existe}(Deus)?
$$

parece binária, mas pode comprimir questões diferentes:

- há um referente metafísico independente?
- existe uma representação mental de Deus?
- há comunidades organizadas em torno dessa representação?
- o padrão é realizado em rituais?
- ele influencia decisões e comportamentos?
- é transmitido entre gerações?
- produz consequências sociais ou corporais?

A Geometria Relacional não precisa responder todas essas perguntas com o mesmo predicado.

---

## 14. Referente metafísico como variável possivelmente não identificável

Considere duas descrições:

$$
d_{+}:\quad \text{“há um referente metafísico independente”},
$$

$$
d_{-}:\quad \text{“não há um referente metafísico independente”}.
$$

Suponha que, na geometria considerada, ambas preservem exatamente as mesmas relações observáveis:

$$
d_{+}\sim_{\mathcal G}d_{-}.
$$

Então o predicado:

$$
M(d)=\text{“há referente metafísico independente”}
$$

não é invariante, pois:

$$
M(d_{+})
\quad\land\quad
\neg M(d_{-}).
$$

Logo, $M$ não define uma propriedade da classe relacional $[d]$.

Dentro dessa geometria, a pergunta “o referente metafísico existe?” não distingue estados do espaço relacional.

Isso não prova:

$$
M
$$

nem:

$$
\neg M.
$$

Mostra apenas que, **se $M$ não se acopla a nenhuma diferença relacional admitida**, a geometria não possui um grau de liberdade capaz de identificá-lo.

---

## 15. Quando a pergunta metafísica voltaria a ser significativa

A teoria não decreta que questões metafísicas são sempre vazias.

Se uma geometria mais rica contiver uma relação $R$ tal que:

$$
M(d_1)\neq M(d_2)
\Rightarrow
R(d_1)\neq R(d_2),
$$

então as descrições deixam de ser equivalentes:

$$
d_1\not\sim_{\mathcal G}d_2.
$$

Nesse caso, a distinção metafísica passa a corresponder a uma diferença do espaço e a pergunta pode tornar-se bem formulada nessa geometria ampliada.

Portanto, a tese não é:

> “a metafísica não importa”.

É:

> **uma variável metafísica só participa desta geometria quando se relaciona com sua estrutura de diferenças.**

---

## 16. “Deus existe para quem acredita”

A frase pode ser reformulada sem decidir a metafísica última.

Para uma pessoa ou comunidade, o padrão religioso pode:

- ser representado mentalmente;
- ser instanciado em oração, culto, ritual e conduta;
- participar da formação de vínculos;
- alterar decisões;
- organizar deveres e proibições;
- modificar rotinas corporais;
- produzir instituições;
- ser transmitido entre gerações.

Nesse sentido relacional:

$$
\operatorname{PresenteRelacionalmente}(Deus,t)
$$

pode ser verdadeiro para a geometria daquela rede de portadores sem que seja necessário concluir:

$$
\operatorname{ReferenteMetafisicoIndependente}(Deus,t).
$$

Também não é necessário concluir sua negação.

Uma formulação cuidadosa é:

> **Crentes, comunidades, textos, rituais e instituições podem representar, instanciar e transmitir o padrão associado a Deus. Esse padrão pode ser causalmente ativo na rede humana independentemente de a geometria decidir a existência de um referente metafísico independente.**

Isso evita a afirmação excessiva de que “o crente cria Deus” no sentido metafísico. O que a teoria pode afirmar é que o crente participa da realização e transmissão do padrão religioso na rede.

---

# Parte V — Presença causal

## 17. Vocabulário relacional mínimo

### 17.1 Padrão

Um **padrão** é uma estrutura capaz de ser representada, instanciada, transmitida ou reconhecida através de diferentes portadores.

Pode corresponder a:

- uma divindade representada;
- uma entidade ritual;
- a memória de uma pessoa;
- uma norma;
- uma narrativa;
- um papel social;
- uma identidade coletiva;
- uma maneira de falar;
- um repertório de gestos;
- uma combinação desses elementos.

O termo é metafisicamente neutro: chamar algo de padrão não implica reduzi-lo a ficção.

### 17.2 Portador

Um **portador** é aquilo em que um padrão pode estar representado ou ser realizado:

- uma pessoa;
- um corpo;
- um grupo;
- um ritual;
- um texto;
- uma gravação;
- uma instituição;
- um objeto simbólico;
- uma prática.

### 17.3 Representação

$$
\operatorname{Representa}(c,p,t)
$$

indica que o portador $c$ mantém informação, referência ou organização associada ao padrão $p$ no tempo $t$.

### 17.4 Instanciação

$$
\operatorname{Instancia}(c,p,t)
$$

indica que o padrão é realizado em comportamento, gesto, fala, organização ou prática.

### 17.5 Mediação

$$
\operatorname{Medeia}(c,p,s_0,s_1,t)
$$

registra a hipótese de que a instanciação do padrão por um portador participa de uma transição entre estados.

---

## 18. Definição de presença causal

Um padrão está causalmente presente quando existe algum portador que o instancia e por meio do qual é registrada uma transformação não trivial:

$$
\operatorname{PresenteCausalmente}(p,t)
:\!\iff
\exists c,s_0,s_1,
\operatorname{Instancia}(c,p,t)
\land
\operatorname{Medeia}(c,p,s_0,s_1,t)
\land
s_0\neq s_1.
$$

Essa definição é deliberadamente independente de qualquer predicado de referente metafísico.

A presença causal pertence à camada relacional. A existência metafísica independente, quando formulada, pertence a outra camada descritiva.

---

## 19. Limite da palavra “causal”

A versão 0.2 torna explícito um limite já presente na versão anterior.

O predicado:

$$
\operatorname{Medeia}(c,p,s_0,s_1,t)
$$

não é produzido automaticamente pela lógica.

Ele precisa ser justificado empiricamente, operacionalmente ou por uma teoria causal adicional.

Assim, o Lean pode provar:

$$
\operatorname{Instancia}
\land
\operatorname{Medeia}
\land
s_0\neq s_1
\Rightarrow
\operatorname{PresenteCausalmente},
$$

mas não pode decidir sozinho se a relação $\operatorname{Medeia}$ ocorre no mundo.

A teoria distingue portanto:

1. **arquitetura lógica da presença causal**;
2. **justificação empírica da atribuição causal**.

Para evitar circularidade, a segunda camada deve ser capaz de distinguir causalidade de coincidência e de comparar explicações concorrentes.

---

# Parte VI — Sobrevivência, memória e identidade

## 20. Sobrevivência não é uma única coisa

A teoria distingue:

1. sobrevivência biológica;
2. continuidade da mesma consciência;
3. continuidade relacional ou estrutural de um padrão.

Uma pessoa pode deixar de estar biologicamente viva enquanto padrões derivados dela continuam presentes em outros portadores.

$$
\neg\operatorname{VivoBiologicamente}(c_0,t_1)
$$

é compatível com:

$$
\operatorname{PadraoPresente}(p,t_1).
$$

---

## 21. Sobrevivência estrutural por reinstanciação

Um padrão sobrevive estruturalmente quando:

1. era instanciado por um portador anterior;
2. é posteriormente instanciado por outro portador;
3. o portador original já não está biologicamente vivo.

$$
\begin{aligned}
\operatorname{SobreviveEstruturalmente}
&(p,c_0,c_1,t_0,t_1)
:\!\iff\\
&\operatorname{Instancia}(c_0,p,t_0)
\land
\operatorname{Instancia}(c_1,p,t_1)
\land
\neg\operatorname{VivoBiologicamente}(c_0,t_1).
\end{aligned}
$$

Isso não implica:

$$
c_0=c_1
$$

nem:

$$
\operatorname{MesmaConsciencia}(c_0,c_1).
$$

---

## 22. Identidade como preservação de invariantes

A versão 0.2 desloca a pergunta sobre identidade.

Em vez de exigir identidade literal:

$$
p_0=p_1,
$$

podemos perguntar se duas instanciações pertencem à mesma classe estrutural:

$$
p_0\sim_{\mathcal G}p_1.
$$

A relação pode ser definida por transformações admissíveis que preservam determinadas invariantes.

Assim, duas realizações concretamente diferentes podem contar como realizações do “mesmo padrão” quando as diferenças entre elas permanecem dentro dos graus de liberdade permitidos pela geometria.

A questão passa a ser:

> **o que pode mudar sem que aquilo que estamos identificando como estrutura deixe de ser preservado?**

Esse problema não é resolvido ainda pela versão 0.2. Ele se torna um programa formal explícito.

---

## 23. Deformação e fidelidade

Se um padrão é transmitido:

$$
p_0\to p_1\to p_2\to\cdots\to p_n,
$$

cada transmissão pode preservar algumas invariantes e alterar outras propriedades.

A teoria deverá distinguir:

- variação permitida;
- deformação;
- perda de invariantes;
- bifurcação de linhagens;
- convergência de linhagens;
- emergência de um novo padrão.

Uma futura métrica ou estrutura de equivalência deverá responder quando:

$$
p_i\sim_{\mathcal G}p_j
$$

e quando:

$$
p_i\not\sim_{\mathcal G}p_j.
$$

---

## 24. Memória distribuída

Um padrão mantido por um único portador é vulnerável à perda desse portador.

Quando distribuído:

$$
p\mapsto(c_1,c_2,\ldots,c_n),
$$

surge redundância.

A perda de um portador pode deixar invariantes relevantes preservadas na rede.

Ritos recorrentes podem produzir ciclos como:

$$
\text{registro}
\to
\text{realização}
\to
\text{novo registro}.
$$

A sobrevivência coletiva passa a ser propriedade da rede e não de um único corpo ou mente.

---

# Parte VII — Arquitetura formal em Lean 4

## 25. Objetivo da formalização

O Lean 4 não será usado para decidir diretamente se existem deuses, almas ou continuidade de consciência.

Ele será usado para:

1. separar a camada relacional da camada descritiva;
2. definir equivalência relacional entre descrições;
3. definir propriedades invariantes;
4. caracterizar perguntas bem formuladas;
5. mostrar quando um predicado é apenas dependente de coordenadas;
6. representar o espaço quociente de descrições equivalentes;
7. preservar a teoria anterior de presença causal e sobrevivência estrutural;
8. construir modelos testemunha que tornem explícita a diferença entre variação descritiva e variação relacional.

---

## 26. Geometria de descrições

A arquitetura formal introduz uma estrutura abstrata:

```lean
structure DescriptionGeometry where
  Description : Type uDescription
  Observable : Type uObservable
  holds : Description → Observable → Prop
```

Duas descrições são relacionalmente equivalentes quando concordam sobre todos os observáveis:

```lean
def RelationallyEquivalent
    (first second : G.Description) : Prop :=
  ∀ observable,
    G.holds first observable ↔ G.holds second observable
```

---

## 27. Invariância

Um predicado sobre descrições é invariante quando respeita a equivalência relacional:

```lean
def Invariant
    (P : G.Description → Prop) : Prop :=
  ∀ first second,
    G.RelationallyEquivalent first second →
    (P first ↔ P second)
```

Uma pergunta bem formulada é, nessa arquitetura, uma pergunta invariante.

---

## 28. Artefato de coordenadas

Um predicado é dependente de coordenadas quando pode mudar dentro de uma mesma classe relacional:

```lean
def CoordinateArtifact
    (P : G.Description → Prop) : Prop :=
  ∃ first second,
    G.RelationallyEquivalent first second ∧
    ¬ (P first ↔ P second)
```

Então podemos provar:

```lean
CoordinateArtifact P → ¬ Invariant P
```

Isso formaliza a ideia de que uma propriedade variável entre descrições equivalentes não é uma propriedade bem definida do espaço relacional.

---

## 29. Espaço quociente

A equivalência relacional é reflexiva, simétrica e transitiva. Portanto, define classes de equivalência.

O Lean pode representar o espaço:

$$
\mathcal D/{\sim_{\mathcal G}}
$$

por um `Quotient`.

Predicados invariantes podem ser transportados para esse espaço porque possuem o mesmo valor em qualquer representante da classe.

Essa operação formaliza a eliminação de diferenças puramente coordenadas.

---

## 30. Núcleo relacional da presença

A camada de presença mantém:

```lean
structure PresenceGeometry where
  Pattern : Type uPattern
  Carrier : Type uCarrier
  State : Type uState
  Time : Type uTime

  biologicallyAlive : Carrier → Time → Prop
  represents : Carrier → Pattern → Time → Prop
  instantiates : Carrier → Pattern → Time → Prop
  mediates : Carrier → Pattern → State → State → Time → Prop
```

Observe que `independentPhysicalReferent` deixa de pertencer ao núcleo relacional básico.

Isso é deliberado.

O status de um referente independente é tratado como parte de uma descrição ontológica adicional, e não como uma relação necessária para definir presença causal, representação, transmissão ou sobrevivência estrutural.

---

## 31. Modelo testemunha da pergunta metafísica

A formalização inclui duas descrições:

- `affirmReferent`;
- `denyReferent`.

Elas discordam sobre:

$$
M(d)=\text{“há referente independente”}.
$$

Mas concordam sobre todos os observáveis relacionais do pequeno modelo.

Portanto:

$$
d_{+}\sim_{\mathcal G}d_{-}
$$

e:

$$
M(d_{+})\neq M(d_{-}).
$$

Logo:

$$
\operatorname{CoordinateArtifact}(M).
$$

Isso prova apenas uma possibilidade lógica:

> existe uma geometria em que afirmar ou negar o referente independente não altera nenhuma relação do sistema e, portanto, não define uma propriedade do espaço quociente.

Não prova que a situação real da religião seja necessariamente assim.

---

# Parte VIII — O que a teoria pode e não pode afirmar

## 32. O que o Lean poderá confirmar

O kernel poderá confirmar que:

- equivalência relacional é uma relação de equivalência;
- predicados invariantes são constantes em classes equivalentes;
- um artefato de coordenadas não é invariante;
- uma pergunta invariante que recebe respostas diferentes em duas descrições prova que essas descrições não são relacionalmente equivalentes;
- o espaço quociente pode ser construído formalmente;
- presença causal não exige um predicado de referente metafísico no núcleo relacional;
- morte biológica é compatível com sobrevivência estrutural;
- o modelo finito contém duas descrições metafisicamente opostas, porém relacionalmente equivalentes.

---

## 33. O que o Lean não poderá confirmar sozinho

O kernel não poderá estabelecer, sem dados ou axiomas externos, que:

- Deus possui ou não possui um referente metafísico independente;
- as descrições religiosas e naturalistas reais são relacionalmente equivalentes em todos os aspectos relevantes;
- determinada transformação humana foi de fato causada por uma crença ou ritual;
- uma determinada rede preservou fielmente um padrão;
- a mesma consciência continua depois da morte;
- uma lista escolhida de observáveis é empiricamente completa;
- uma transformação entre descrições é cientificamente legítima;
- uma relação chamada `mediates` corresponde a causalidade real.

Essas questões pertencem à camada empírica, metodológica ou filosófica adicional.

---

## 34. Neutralidade metafísica revisada

A versão 0.1 dizia que a teoria era metafisicamente não compulsória.

A versão 0.2 torna essa posição mais precisa.

A geometria não precisa escolher uma variável metafísica quando essa variável não distingue classes relacionais.

Isso não é agnosticismo obrigatório.

Também não é ateísmo.

Também não é teísmo.

É uma regra estrutural:

> **não promover a diferença ontológica uma distinção que não corresponde a nenhuma diferença no espaço definido pela teoria.**

Se novas relações forem introduzidas e tornarem a variável identificável, a geometria deve ser ampliada e a pergunta reavaliada.

---

# Parte IX — Princípios fundamentais da versão 0.2

## Princípio I — Representação exige coordenadas

Toda descrição de um fenômeno é produzida por uma forma de representação e, portanto, contém escolhas de coordenatização.

## Princípio II — Fenômeno e descrição não são idênticos

Uma propriedade da descrição não deve ser automaticamente atribuída ao fenômeno.

## Princípio III — Primazia relacional

Uma distinção ontológica só é identificável nesta geometria quando corresponde a uma distinção relacional.

## Princípio IV — Equivalência relacional

Descrições que preservam todas as relações relevantes pertencem ao mesmo estado relacional da geometria.

## Princípio V — Invariância

Propriedades ontologicamente bem definidas no espaço relacional devem ser constantes entre descrições equivalentes.

## Princípio VI — Eliminação de artefatos de coordenadas

Uma propriedade que varia dentro de uma classe de equivalência não define uma propriedade da classe relacional.

## Princípio VII — Pergunta bem formulada

Uma pergunta binária só é bem formulada na geometria quando sua resposta é invariante sob equivalência relacional.

## Princípio VIII — Presença por transformação

Um padrão instanciado que medeia uma transformação não trivial está causalmente presente na geometria dessa transformação, desde que a relação de mediação seja adequadamente justificada.

## Princípio IX — Separação entre presença e referente

Presença relacional de um padrão não implica, por si só, a existência nem a inexistência de um referente metafísico independente.

## Princípio X — Sobrevivência por reinstanciação

Um padrão pode sobreviver estruturalmente à morte de um portador quando relações e invariantes relevantes são preservadas em outros portadores.

## Princípio XI — Não identidade automática

Continuidade estrutural não implica automaticamente identidade biológica ou continuidade da mesma consciência.

## Princípio XII — Revisabilidade geométrica

Uma distinção irrelevante em uma geometria pode tornar-se relevante em uma geometria ampliada se novas relações permitirem identificá-la.

---

# Parte X — Programa de pesquisa

## 35. Transformações admissíveis entre coordenadas

A próxima etapa deverá distinguir uma simples mudança de vocabulário de uma transformação legítima entre representações do mesmo fenômeno.

Será necessário definir:

$$
T:C_1\to C_2
$$

com critérios explícitos de preservação estrutural.

---

## 36. Conjunto gerador de invariantes

Uma geometria rica pode possuir muitas invariantes. É importante investigar se um subconjunto delas é suficiente para determinar classes relacionais.

Isso permitirá perguntar:

- quais observáveis são redundantes?
- quais são fundamentais?
- quais combinações distinguem estados?

---

## 37. Identificabilidade

Uma variável $x$ é identificável quando valores distintos de $x$ produzem classes relacionais distintas.

Em contraste, se:

$$
x_1\neq x_2
$$

mas:

$$
d(x_1)\sim_{\mathcal G}d(x_2),
$$

então $x$ não é identificável naquela geometria.

Esse conceito será central para distinguir desconhecimento de não-identificabilidade estrutural.

---

## 38. Métrica de semelhança e deformação de padrões

Será necessário modelar quanto duas instanciações diferem e quais diferenças preservam identidade estrutural.

Possibilidades incluem:

$$
d(p_1,p_2)
$$

ou relações de equivalência graduadas.

---

## 39. Redes de transmissão

A transmissão pode ser modelada como grafo:

$$
c_i\to c_j
$$

ou, futuramente, por estruturas categóricas nas quais composições de transmissões e transformações possam ser estudadas formalmente.

---

## 40. Robustez de memória distribuída

A teoria poderá medir:

- redundância;
- tolerância à perda de portadores;
- fidelidade de transmissão;
- diversidade de portadores;
- persistência temporal;
- bifurcação e convergência de linhagens.

---

## 41. Teoria causal adicional

Uma futura extensão deverá substituir a relação primitiva `mediates` por uma arquitetura que possa incorporar critérios mais fortes de causalidade, por exemplo:

- intervenções;
- contrafactuais;
- dependência temporal;
- mecanismos;
- comparação com hipóteses concorrentes.

A versão 0.2 não escolhe ainda uma teoria causal específica.

---

# Formulação canônica da versão 0.2

> **Ontologia da Presença Causal — formulação relacional.** Toda descrição de um fenômeno exige uma representação e, portanto, uma escolha de coordenadas. A geometria relevante é determinada não apenas por objetos, mas pelas relações, transformações, restrições e invariantes do espaço. Duas descrições que preservam toda a estrutura relacional relevante pertencem à mesma classe ontológica nessa geometria, ainda que discordem em propriedades dependentes de coordenadas. Consequentemente, uma pergunta ontológica só é bem formulada quando sua resposta é invariante dentro dessas classes. Se afirmar ou negar uma entidade metafísica não altera qualquer relação admissível, essa diferença não define dois estados do espaço relacional e a pergunta binária correspondente não é decidida pela geometria: ela deixa de ser uma distinção bem definida naquele domínio. Em contraste, padrões representados, instanciados, transmitidos e causalmente ativos podem possuir presença relacional independentemente dessa variável metafísica. A morte de um portador não implica a extinção de um padrão quando suas relações e invariantes continuam realizadas por outros portadores.

---

# Conclusão

A pergunta “isso existe?” não é necessariamente o ponto de partida correto de uma ontologia.

Antes dela vêm questões mais fundamentais:

- qual é o espaço considerado?
- quais relações o estruturam?
- quais transformações são admissíveis?
- como o fenômeno é representado?
- quais propriedades dependem da representação?
- quais permanecem invariantes?
- quais variações correspondem a graus de liberdade reais?
- quais são apenas liberdade de coordenadas?

Quando duas respostas aparentemente opostas não produzem nenhuma diferença relacional, a geometria não precisa escolher entre elas. A oposição pode estar localizada na representação e não no estado do espaço.

Assim, a função da teoria não é responder indiscriminadamente a todas as perguntas ontológicas tradicionais.

Parte de sua função é mais radical:

> **determinar quais perguntas chegam a definir uma diferença.**

Em sua forma mais curta:

$$
\boxed{
\text{uma diferença só entra na ontologia desta geometria}
\quad\text{quando faz diferença nas relações.}
}
$$

---

## Arquivos da versão 0.2

- `ONTOLOGIA_DA_PRESENCA_CAUSAL_v0.2.md` — documento conceitual revisado;
- `OntologyOfCausalPresence_v0_2.lean` — núcleo formal revisado e modelos testemunha.

**Nota de verificação:** o código Lean 4 desta versão foi escrito de forma conservadora, mas o executável do Lean não está disponível no ambiente atual. Portanto, a arquitetura e as provas foram revisadas estaticamente, porém ainda precisam passar pelo kernel do Lean como próximo checkpoint técnico.

