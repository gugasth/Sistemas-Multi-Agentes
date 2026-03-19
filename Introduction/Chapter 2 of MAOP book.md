

## Visão geral

O Capítulo 2 apresenta a **Programação Orientada a Multiagentes (MAOP)** como uma abordagem para desenvolver sistemas **complexos, distribuídos, abertos e autônomos**. A principal ideia do capítulo é que esses sistemas devem ser entendidos a partir de **três dimensões complementares**:

- **agente**
- **ambiente**
- **organização**

O argumento central é que pensar apenas em agentes individuais não é suficiente. Para construir sistemas robustos, é necessário considerar também o contexto onde eles atuam e as estruturas sociais que regulam seu comportamento.

---

## 1. Dimensão do agente

Essa dimensão trata os agentes como entidades autônomas, capazes de:

- perceber o ambiente;
- tomar decisões;
- executar ações;
- perseguir objetivos;
- interagir com outros agentes.

Os conceitos mais importantes são:

- **beliefs**: o que o agente sabe ou acredita;
- **goals**: os objetivos que deseja alcançar;
- **actions**: as ações que pode executar.
![[agent_image.png|323]]
### Ideia principal
O agente não é apenas um componente de software reativo. Ele possui **autonomia** e algum grau de **racionalidade prática**, escolhendo o que fazer de acordo com seus objetivos e percepções.

---

## 2. Dimensão do ambiente
![[enviroment_image.png|491]]

O capítulo destaca que o ambiente não deve ser tratado como um pano de fundo passivo. Em MAOP, ele é uma entidade de primeira classe, responsável por oferecer:

- recursos compartilhados;
- suporte à coordenação;
- mediação entre agentes;
- contexto de execução.

Os conceitos mais relevantes são:

- **workspace**: espaço lógico de interação;
- **artifacts**: recursos e ferramentas disponíveis no ambiente;
- **operations**: operações que os agentes podem executar nesses artifacts;
- **properties/signals**: propriedades observáveis e sinais/eventos emitidos pelo ambiente.

---

## 3. Dimensão da organização
![[organization_image.png|306]]

A terceira dimensão trata da estrutura social do sistema. Em sistemas multiagentes, não basta ter entidades autônomas interagindo livremente; é preciso modelar como elas são coordenadas.

Os principais conceitos são:

- **groups**: grupos de agentes;
- **roles**: papéis assumidos pelos agentes;
- **norms**: regras, obrigações e permissões;
- **organizational goals**: objetivos coletivos;
- **social schemes/plans**: formas de coordenação das atividades.

### Ideia principal
A organização fornece regras e estruturas que tornam possível o comportamento coletivo coordenado, especialmente em sistemas grandes, abertos e dinâmicos.

---

## Integração entre as três dimensões
![[3dimensions_image.png]]

O ponto mais importante do capítulo é que MAOP deve integrar:

- **agentes**, que decidem e agem;
- **ambiente**, que oferece recursos e mediação;
- **organização**, que coordena e regula o comportamento coletivo.

Essa integração permite modelar sistemas multiagentes de forma mais realista e robusta.

### Em outras palavras

- o **agente** representa a autonomia;
- o **ambiente** representa o contexto e os meios de ação;
- a **organização** representa a coordenação social.

---

## Benefícios da abordagem MAOP

Segundo o capítulo, essa visão traz vantagens importantes para o desenvolvimento de sistemas complexos:

- **autonomia explícita** dos componentes;
- **descentralização** do controle;
- **abertura** para entrada e saída de agentes;
- **heterogeneidade** de agentes e recursos;
- **adaptabilidade** a mudanças no contexto;
- **melhor modelagem da cooperação e coordenação**;
- **maior clareza conceitual** no projeto do sistema.

---

## Síntese final

A ideia central do Capítulo 2 pode ser resumida assim:

> **MAOP = Agentes + Ambiente + Organização**

Ou seja, programar sistemas multiagentes de forma adequada exige considerar simultaneamente:

1. **quem decide** → os agentes;
2. **onde e com quais recursos atua** → o ambiente;
3. **como o comportamento coletivo é estruturado** → a organização.

---

## Frase-chave para memorizar

> Um sistema multiagente robusto não é apenas um conjunto de agentes interagindo, mas uma composição integrada de **agentes autônomos**, **ambientes estruturados** e **organizações que regulam a ação coletiva**.