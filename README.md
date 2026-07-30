# 🤖 Especificação da Arquitetura da Marvid

## 📖 Sobre o projeto

Olá!

Antes de tudo, há uma coisa que deves saber: a Marvid é um protótipo de IA multiplataforma e multitarefa. Na pior das hipóteses, também pode ser considerada um projeto académico e um exercício de programação, mas isso está longe de resumir aquilo que ela representa para mim.

Este repositório reúne a implementação e a especificação oficial da arquitetura da Marvid. Esta documentação descreve a implementação, as decisões arquiteturais e as motivações por trás de cada uma delas. O objetivo é servir como a principal referência para o desenvolvimento da Marvid, respondendo tanto ao **como** quanto ao **porquê** de cada decisão.

A especificação é um documento progressivo. À medida que a Marvid evolui, esta documentação evolui com ela. Algumas ideias serão refinadas, outras serão substituídas e muitas ainda nem existem. E, por mim, está tudo bem. Evoluir é o principal objetivo deste projeto e o meu.

Se estás aqui por curiosidade, espero que encontres algo interessante ou, no mínimo, uma leitura agradável. Se pretendes compreender ou contribuir para a Marvid, espero que este manual te sirva como uma referência clara, consistente e útil.


## 🎯 Objetivos

A documentação da Marvid tem como principal objetivo servir de referência durante todo o ciclo de vida do projeto. Segundo os meus cálculos, isso vai levar o seu tempo... (muito tempo 😅).

Ao documentar a arquitetura, as decisões e as motivações por trás delas, pretende-se reduzir ambiguidades, preservar conhecimento e facilitar a evolução do sistema sem perder a visão original do projeto.

Este manual também procura tornar o desenvolvimento mais organizado. Antes de implementar novas funcionalidades, estas devem ser pensadas, discutidas e, sempre que fizer sentido, especificadas.

Por fim, esta documentação pretende tornar a Marvid compreensível para qualquer pessoa interessada no projeto, independentemente de ter acompanhado ou não a sua evolução desde o início.


## 🧭 Como utilizar esta documentação

Como já foi mencionado, esta documentação foi organizada para acompanhar a evolução da Marvid desde a sua conceção até à sua implementação.

O conteúdo principal foi dividido em **missões**. Na prática, as missões são os capítulos desta documentação, mas decidi chamá-las assim porque sim... e também porque representam etapas concretas da evolução da Marvid. Cada missão possui um objetivo próprio e contribui para a construção do projeto como um todo.

As missões podem ser encontradas no diretório `Docs/` deste repositório ou através da página web oficial do projeto. A organização do repositório e a função de cada diretório são apresentadas na secção **🏗️ Estrutura da documentação**.

As missões seguem uma estrutura comum composta por secções como **Resumo**, **Motivação**, **Especificação**, **Observações**, **Pendências** e **Diário de Bordo**. Nesta secção é apresentada apenas uma visão geral. A descrição completa da estrutura de cada missão encontra-se em **📝 Estrutura das missões**.

Embora exista uma ordem recomendada de leitura, cada missão pode ser consultada individualmente, dependendo do assunto de interesse.


## 🏗️ Estrutura da documentação

Se estiveres aqui uns meses ou até alguns anos depois de eu ter começado este projeto, é possível que encontres dezenas de missões distribuídas por vários ficheiros. Não te assustes. A documentação foi organizada para crescer juntamente com a Marvid.

Para facilitar a navegação, o repositório separa a especificação técnica, a apresentação do projeto e os recursos utilizados pela documentação online. Além disso, os ficheiros e diretórios seguem uma convenção de nomenclatura simples e consistente, tornando mais fácil localizar qualquer conteúdo e acompanhar a sequência das missões.

Atualmente, o repositório encontra-se organizado da seguinte forma:

```text
/
├── Docs/         # Missões da especificação
├── site/         # Recursos da documentação online
├── index.html    # Página principal da documentação
└── README.md     # Introdução e guia de utilização
```

### README.md

É a porta de entrada do projeto. Apresenta a Marvid, explica os objetivos desta documentação e serve como guia para novos leitores e colaboradores.

📍 É aqui que estás agora.

### Docs/

Contém todas as missões da especificação. Cada missão documenta um tema específico da arquitetura da Marvid e constitui um registo permanente da evolução desse tema ao longo do projeto.

Os ficheiros seguem uma convenção de nomenclatura comum, apresentada mais adiante neste documento.

### site/

Contém os recursos utilizados pela versão online da documentação, como folhas de estilo, scripts, imagens e outros ficheiros auxiliares.

### index.html

É o ponto de entrada da documentação online. A sua principal função é apresentar o conteúdo das missões de forma organizada e proporcionar uma experiência de leitura mais agradável do que a simples navegação pelos ficheiros Markdown.


## 📝 Estrutura das missões

Todas as missões da documentação seguem a mesma estrutura. O objetivo é manter a documentação consistente, facilitar a navegação e permitir que qualquer missão possa ser compreendida sem depender das restantes.

Cada missão é composta pelas seguintes secções:

### Resumo

Apresenta uma visão geral da missão. Idealmente, deves conseguir compreender a arquitetura geral da Marvid lendo apenas os resumos de todas as missões. Se achares que algum resumo não cumpre esse objetivo, agradeço que mo digas. Afinal, se a documentação pode evoluir, ela também pode ser melhorada.

E, já agora, se há uma coisa que gosto tanto quanto construir a Marvid, é falar sobre ela com pessoas interessadas.

### Motivação

Explica por que a missão existe. Esta secção descreve o problema, a necessidade ou a ideia que motivou a sua criação, sem entrar em detalhes da implementação.

### Especificação

É a parte principal da missão. Contém a definição oficial da arquitetura, do comportamento ou do componente documentado. Sempre que existir alguma divergência entre a especificação e outras secções da missão, a especificação representa o estado atual da Marvid.

### Observações

Reúne notas, exemplos, recomendações e outras informações que complementam a especificação, mas que não fazem parte da definição oficial.

### Pendências

Lista assuntos ainda em aberto. O objetivo desta secção é permitir que a documentação evolua naturalmente, sem obrigar que todas as decisões sejam tomadas antes do desenvolvimento.

### Diário de Bordo

Regista a evolução da missão sob a minha perspetiva pessoal. É o espaço onde ficam documentadas as minhas experiências, dificuldades, descobertas, mudanças de opinião, ideias abandonadas, pequenos desabafos e tudo aquilo que fez parte da jornada, mas que não pertence à especificação técnica.

Podes sempre saltar esta secção. Afinal, nem toda a gente gosta de ler os lamentos de um programador.

Resumindo, a **Especificação** documenta a arquitetura da Marvid. O **Diário de Bordo** documenta a minha experiência de a construir.


## 📏 Convenções

Para manter a documentação organizada e consistente, foram definidas algumas convenções para os seus ficheiros e conteúdos.

### Nomenclatura dos ficheiros

Os ficheiros seguem o formato:

```text
<número>-<nome-da-missão>.md
```

Exemplo:

```text
01-filosofia.md
02-visao-geral.md
03-hierarquia.md
```

A numeração representa a ordem recomendada de leitura das missões, não uma relação de dependência entre elas.

### Atualização

A especificação representa sempre o estado atual do projeto. Alterações relevantes devem ser acompanhadas pelo respetivo registo no Diário de Bordo.

### Estrutura

Todas as missões seguem a estrutura definida na secção anterior. Esta organização permite separar a definição técnica dos registos pessoais associados ao desenvolvimento.

### Princípio geral

A documentação é escrita de forma clara, direta e suficientemente detalhada para preservar conhecimento sem criar complexidade desnecessária.

As convenções existem para manter a organização do projeto e podem ser revistas sempre que deixarem de cumprir esse objetivo.


## 🌱 Versionamento

Esta documentação é um conjunto de documentos em evolução. À medida que o projeto cresce, novas ideias surgem, decisões são revistas e algumas abordagens podem deixar de fazer sentido.

Para acompanhar estas mudanças, a documentação utiliza o bom e velho versionamento, permitindo identificar diferentes estados do projeto ao longo da sua história.

As alterações importantes devem preservar o contexto da decisão tomada, indicando o que mudou, por que mudou e qual o impacto dessa alteração.

O versionamento da documentação acompanha as mudanças de código, funcionalidades, ideias, arquitetura e compreensão do próprio projeto.

Cada versão representa uma fase da Marvid, permitindo compreender onde o projeto está e o caminho que levou até esse ponto.



## 📂 Organização do repositório