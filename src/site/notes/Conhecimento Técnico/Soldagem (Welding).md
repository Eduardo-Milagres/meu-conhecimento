---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Soldagem (Welding)/","created":"","updated":""}
---


- União permanente
- União de peças usando [[Conhecimento Técnico/Conceitos da Termodinâmica (conflict 2023-08-15-18-59-51)#Calor\|calor]] e/ou [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|pressão]]
- Pode haver um material aditivo que será acrescentado entre os materiais unidos
- Método mais barato em relação ao material e método de fabricação
- A maioria das operações são manuais
	- Exige mão de obra especializada
- A solda pode alterar as propriedades do material ao redor da solda
- Pode conter defeitos internos dificeis de identificar
- As peças soldas devem ter um espaço mínimo entre elas para garantir a resistência
- Padronizados pela AWS (American Welding Society)

## Material aditivo ou consumível
- Material que será adicionado entre as peças soldadas
- Exemplos:
	- Eletrodo
	- Vareta
## Chanfros
- Abertura na peça para aumentar a área de soldagem
- Reduz a reação da solda no material

### Tipos
- V
- Meio V
- Duplo V
- U
- J
- Duplo U
- Duplo J
- K

## Junta
- Região onde a solda foi inserida

## Soldagem por fusão
 - Usa [[Conhecimento Técnico/Conceitos da Termodinâmica#Calor\|calor]] para fundir os materiais
 - Processo por adição também chamado de autógena
 - Tipos:
	 - [[Conhecimento Técnico/Soldagem (Welding)#Soldagem à arco elétrico\|Solda por arco]]
		 - Realizado por um arco elétrico (AW - Arc Welding)
		 - Pode haver aplicação de [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|pressão]]
		 - Utiliza o metal de adição
	 - Solda por resistência (RW - Resistance Welding)
		 - Usa [[Conhecimento Técnico/Conceitos da Termodinâmica (conflict 2023-08-15-18-59-51)#Calor\|calor]] gerado pela resistência elétrica com a aplicação de uma [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|pressão]]
		 - Solda ponto
	 - Solda oxigás (OFW - Oxiful Gás Welding)
		 - Usa-se um gás combustível
		 - Oxigênio e Acetileno
	 - Solda no estado sólido
		 - Usa-se calor e [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|pressão]]
		 - Solda por fricção (FRW - Friction Welding)
			 - Causada pelo atrito entre duas superfícies
		 - Solda por difusão ou atrito (DW - Diffusion Welding)
			 - Elevada [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|pressão]] e temperatura
		 - Solda por ultrassom (USW - Ultrasonic Welding)
			 - Onda ultrassônica aplicada paralela a superfície de contado
			 - Aquece o material  pela agitação das moléculas

# Simbologia

## Soldagem à arco elétrico
- Arco elétrico é uma descarga de corrente elétrica causada pela abertura de um circuito
- O arco pode chegar a 5.500 C, suficiente para fundir o metal

### SMAW (Shielded Metal Arc Welding)
- Solda à arco elétrico por eletrodo revestido
- Tem-se um gás que protege a solda

### SAW (Submerged Arc Welding)
- Solda à arco submerso
- Eletrodo nu e um tubo de fluxo com material granulado que funciona como isolante
	- O fluxo granulado funde-se parcialmente
	- Forma uma escória líquida que depois é solidificada
- Automática ou semiautomática

### GMAW (Gas Metal Arc Welding)
- Solda à arco elétrico com proteção
- No caso de solda ao ar livre é necessária proteção contra o vento. Usa-se o CO2
- Mig
- Mag
- Tig

### FCAW (Flux Cored Arc Welding)
- Solda à arco elétrico com fluxo no núcleo
- Semalhante ao [[Conhecimento Técnico/Soldagem (Welding)#GMAW (Gas Metal Arc Welding)\|GMAW]] porém o gás vem internamente do eletrodo
- Também chamado de processo com arame tubular 

## Consumíveis
- Todo material empregado na deposição ou proteção da solda
- Eletrodos revestidos
- Varetas
- Arames sólidos
- [[Conhecimento Técnico/Soldagem (Welding)#Fluxo\|Fluxos]]
- Gases
- Aneis consumíveis

### Determinação dos consumíveis
- Limitações: disponibilidade dos equipamentos, mão de obra
- Econômico: produtividade, eficiência da deposição
- Material base: composição química, espessura, posição da junta 
- Fatores para seleção do consumível:
	- Metal base
	- Geometria e tipo de junta
	- Espessura da peça a ser soldada
	- Posição da soldagem
	- Tipo de fonte de energia
	- Produtividade
	- Habilidade do soldador

### Eletrodos
- Usados nos processos AW (Arc Welding)

#### Consumíveis

#### Não consumíveis

#### Codificação
EXX(X)-YZ
	E - Eletrodo
	XX(X) - Resistência a tração (por 1.000 psi)
	Y - Posição de soldagem
	Z - Corrente e polaridade para soldagem, tipo de arco, penetração e quantidade de pó de ferro
	
E (Eletroctode): refere-se ao eletrodo para solda à arco elétrico
R (Rod): vareta para soldagem oxigás
ER: fluxo nu (arame) ou vareta de soldagem a arco elétrico
F (Flux): fluxo de soldagem
...

#### Revestimento
- Material [[Conhecimento Técnico/Materiais de Construção Mecânica#Compósitos\|compósito]]
	- Elementos de liga
	- Desoxidantes
	- Estabilizadores de arco
	- Fundentes
	- Materiais da camada protetora (dextrina, carbonato, etc)
- Pode alterar a resistência mecânica da região soldada

### Fluxo
- Previne a formação de oxidos e outros contaminantes
- Durante a soldagem funde-se e torna uma poça líquida cobrindo a operação e protegendo a solda
- Após o endurecimento da escória deve-se retira-la
- Compostos granulares
- Mineral fusível
- Purifica a poça de fusão

## Fontes de energia
- Gera a corrente para o arco elétrico
- A corrente gerada é transformada em calor
- Opera em baixas tensões (10 a 50 V) e altas correntes (40 a 500 A)