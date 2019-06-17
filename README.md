# Engenharia de Software I

## 1 - O que é Engenharia de Software ?

	É uma área da computação que estuda técnicas e modelos de Desenvolvimento de Software. 
	Com base em uma análise	do escopo de um software, propõe melhores técnicas 
	e o melhor modelo de desenvolvimento, especificação e manutenção de sistemas,
	visando organização, produtividade e qualidade.
	
## 2 - Explique como que funciona os modelos tradicionais abaixo e cite as vantagens e desvantagens de cada uma:

### a) Cascata

	Um dos mais antigos e mais usados, as atividades são executadas de forma *sistémica e sequencial*.

*Vantagens*

* Simples e Fácil.

*Desvantagens*

* Atrasa a reducão de riscos.

### b) Iterativo

	É o modelo cascata, sendo aplicado de forma Iterativa, as iterações iniciais atacam os maiores riscos.

*Vantagens*

* Os testes e integração são realizados desde o inicio, reduzindo riscos e corrigindo erros no início.
* Permite feedback de usuários desde cedo.

*Desvantagens*

### c) Programação Exploratória

	Foca em desenvolver a primeira versão do sistema o mais rápido possível, 
	após o fim de cada versão o sistema é testado pelos usuários.
	Ideal para sistemas onde não seja possível fazer especificações detalhadas.

*Vantagens*

* Foco no desenvolvimento.
* Feedback e testes desde o início.

*Desvantagens*

* Ausência da noção de programa correto.
* Ferramentas de alto nível e maquinas poderosas.
* Raramente usado em sistemas de grande porte.
* Alto custo.

### d) Prototipação Descartável

	O objetivo é entender os objetivos do sistema, inicia com requisitos vagamente entendidos.
	Como na exploratória, a primeira versão é para o usuário experimentar/experimentar.

*Vantagens*

* Protótipos ajudam na qualidade da especificação no futuro.
* Menor gasto com manutenção.
* O treinamento dos usuários pode ser feito antes do produto ser concluído.

*Desvantagens*

* A construção do protótipo atrasa a implementação.
* Demorado.
* Alto Custo.
* Cliente vê o protótipo e não entende que precisa ser reconstruído.


### e) Transformação Formal

	Uma especificação formal(Definição matemática) do software é desenvolvida e 
	depois transformada em um programa que preserve as regras(refinamento).

*Vantagens*

* Programas que são corretos por construção. 

*Desvantagens*

* Não recomendado para o desenvolvimento de sistemas de grande porta (atualmente).
* Provar teoremas é lento.


### f) Incremental	

	O modelo incremental, combina elementos do modelo sequencial com a filosfia iterativa da prototipagem.
	Cada sequencial produz um entregável.

*Vantagens*

* A cada incrementa o usuário pode fazer uma revisão ou utilizar o produto.
* Sempre operacional.

*Desvantagens*

* Cada incremento, deve implementar as solicitações do usuário e mais as funcionalidades planejadas anteriormente.

### g) Espiral

	Foi criado para absorver as melhores características do modelo clássico e 
	da protótipagem, com aspectos gerenciais.

*Vantagens*

* A cada ciclo da espiral, versões mais completas do software são construídas.
* Qualidade.
* Integra desenvolvimento e manutenção.

*Desvantagens*

* Dificíl convencer gerentes, de que o processo é controlável.
* Requer experiência em avaliação de riscos.

### h) RUP

	É um modelo de desenvolvimento de software, descreve um conjunto de atividades para 
	transformar requisitos em software.	Baseado em componentes, interconectados.
	Utiliza várias ferramentas, como UML, Casos de uso etc.

*Vantagens*

* Acelera o desenvolvimento, com tarefas curtas e controladas.
* Reduz o risco, por descobrir erros no inicío.

*Desvantagens*

* Muita documentação.

## 3 - Explique como que funciona os modelos ágeis abaixo e cite as vantagens e desvantagens de cada uma:

### a) Agile Modelling
### b) Adaptive Software Development
### c) Agile Unified Process
### d) Crystal
### e) Dynamic Solutions Delivery Method
### f) Extreme Programming
### g) Feature Driven Development
### h) Kanban
### i) Lean Software Development

## 4 - Quando usar o método ágil e quando usar o método tradicional de desenvolvimento?

	A escolha de qual método usar, parte de algumas variáveis como: equipe, cliente, prazo e custo do projeto.

	Caso a equipe de desenvolvimento seja multidisciplinar, o cliente terá tempo e disposição para participar
	de decisões e tenha um determinado valor e prazo fixo para desenvolver um projeto então a escolha estaria
	dentro dos métodos ágeis.
  
	Caso contrário, a equipe não é multidisplinar, o cliente é mais reservado, já tem todo um projeto pensado
	e não deseja mudanças e prazo e custo não são problemas, então seria aconselhavél utilizar os 
	métodos tradicionais.
  
## 5 - O que é um requisito funcional, requisito não funcional e requisito de domínio?
  
* Funcional

	Descreve funcionalidades e serviços do sistema.

* Não-Funcional

	Define propriedades e restrições do sistema (tempo, espaço, etc).
	Normalmente são mais críticos.

* Domínio

	Derivados do domínio da aplicação e	descrevem características do sistema e
	qualidades que refletem o domínio. Podem ser restrições sob requisitos.


## 6 - Identifique os requisitos funcionais, não funcionais e de domínio no caso abaixo:
 
### a) Clínica Odontológica
![Clínica Odontológica](https://raw.githubusercontent.com/vifelisberto/EngenhariaSoftware/master/ClinicaOdontologica.PNG)

## 7 - Faça o diagrama de caso de uso, diagrama de atividades, diagrama de classes, diagrama de sequência e de estados do caso abaixo.

### a) Clínica Veterinária
	O cliente se dirige a clínica onde marca uma consulta com a secretária levando seu
	animal. Caso não sejam cadastrados, a secretaria deve cadastrá-los.
	Em cada sessão, o cliente deve informar os sintomas. O animal pode ter que passar por
	várias seções, dependendo do diagnóstico
	Durante a sessão, o veterinário pode solicitar exames a serem tragos na próxima seção.
	A cada sessão gera-se um histórico e uma conta
	A secretária tem a responsabilidade de manter atualizado os cadastros dos clientes,
	médico e animais

## 8) Explique como as arquiteturas de software abaixo funcionam e cite quando usar cada um deles.

### a) Arquitetura cliente-servidor;
### b) Arquitetura em camadas;
### c) Arquitetura de repositório;
### d) Arquitetura pipe-and-filter;
### e) Model View Control.

## 9) Qual a diferença entre inspeção e testes?

	Inspeção se preocupa com a análise da representação do sistema estático para descobrir problemas.
	Testes se preocupa com o comportamento do produto, com dados etc. 

## 10) Quais são os tipos de testes existentes?
	
* Teste de software.
* Teste de validação.
* Teste de Defeitos.

## 11) Qual a diferença entre user experience e user interface?

	Ambos trabalham juntos e são essenciais, UX refere-se ao Design de Experiência (Analítico e Técnico).
	UI significa Design de Interface (Gráfico).


## 12) Qual a diferença entre manutenção e evolução? Quando usamos manutenção e quando usamos evolução?

	Manutenção é uma fase onde somente correções para manter o software operacional são feitas.
	
	Evolução é a fase de vida de um software que está em uso operacional e está evoluindo com 
	novos requisitos.

## 13) Quais são os tipos de manutenção?

* Manutenção para reparar falhas de software.
* Manutenção para adaptar o software a um ambiente operacional diferente.
* Manutenção para adicionar ou modificar a funcionalidade do sistema.

## 14) Quando utilizamos reengenharia e quando utilizamos refatoração?

	A reengenharia é utilizada quando um software foi utilizado por um tempo e os custos de manutenção 
	estão aumentando.

	A refatoração é utilizada é sempre utilizada para melhoria e evolução do software.