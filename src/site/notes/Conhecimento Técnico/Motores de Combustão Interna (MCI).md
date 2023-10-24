---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Motores de Combustão Interna (MCI)/","created":"","updated":""}
---


# Tópicos relacionados
[[Conhecimento Técnico/Motor\|Motor]]
[[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)\|Exercícios - Motores de Combustão Interna (MCI)]]

# Conceitos
- Endotérmico - Combustão interna
- O combustível é queimado internamente
- Utilizam os próprios gases de combustão como fluido de trabalho
	- Estes gases realizam os processos de 
		- Compressão
		- Aumento de temperatura (queima)
		- Expansão
		- Exaustão
- Conhecidos como motor a explosão (tecnicamente incorreto)
- Transforma o movimento alternativo (vai e vem) do pistão em movimento rotativo

# Classificações

## Propriedade do gás na admissão
- Ar (Diesel)
- Mistura ar combustível (Otto)

## Ciclo de Trabalho
- 2 tempos
	- Ciclo realizado em em 2 deslocamentos completos do pistão, em 1 inda e vinda do pistão do ponto morto superior (pms) ao ponto morto inferior (pmi)
- 4 tempos
	- Realizado em 4 deslocamentos completos, 2 indas e vindas do ponto morto superior (pms) ao ponto morto inferior (pmi)

## Ignição
- Por centelha (Otto)
- Por compressão (Diesel)
  
## Número de cilindros
- Monocilíndricos
- Policilíndricos

## Tipo
- Pistão
 ![esquemas_tipos_combustao_interna_pistao.png](/img/user/Imagens/Excalidraw/esquemas_tipos_combustao_interna_pistao.png)
- Rotativo (Wankel)
![esquemas_tipos_combustao_interna_rotativo.png](/img/user/Imagens/Excalidraw/esquemas_tipos_combustao_interna_rotativo.png)
- Jato
- Turbos
## Disposição dos cilindros
- Em linha
- Em V
- Opostos
- Radiais

## Utilização
### Estacionários
- Aciona máquinas estacionárias
- Exemplos:
	- Geradores
	- Bombas

### Industriais
- Aciona máquinas
- Exemplos:
	- Máquinas de mineração
	- Tratores
	- Máquinas de construção civil

### Veiculares
- Aciona veículos de transporte
- Exemplos:
	- Caminhões
	- Ônibus
	- Carros

### Marítimos
- Aciona máquinas de uso naval e barcos

# Definições
## Tempo
- Corresponde a um [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Curso ($h_2$)\|curso]] do embolo ou a meia volta do eixo do virabrequim

## Ponto morto superior (pms)
 - Ponto onde o pistão atinge o final do curso na parte superior do bloco

## Ponto morto inferior (pmi)
- Ponto onde o pistão atinge o final do curso na parte inferior do bloco

## Ciclo
- Conjunto de transformações dos fluídos desde a admissão até a exaustão
- Exemplos:
	- Ciclo Otto
	- Ciclo diesel
	- Ciclo Brayton

## Superfície útil do êmbolo
- Seção do cilindro diminuida pela seção da haste quando a haste se prolonga para ambos os lados do cilíndro onde atua o fluído sob pressão

## Área do motor de simples efeito ($A_c$)
$$A_c = \frac{\pi}{4}*D^2=0,7858*D^2$$

## Área do motor de duplo efeito ($A_{c1}$ e $A_{c2}$)

$$A_{c1} = \frac{\pi}{4}*D^2$$

$$A_{c2} = \frac{\pi}{4}*(D^2*d^2)$$

## Área do motor de duplo efeito com haste em ambos

$$A_{c} = \frac{\pi}{4}*(D^2*d^2)$$

## Áreas simplificadas

$$A_c = \frac{\pi}{4}*D^2 = f*D^2$$
$f=0,785$, motores de simples efeito
$f=0,75$, motores de duplo efeito haste de um lado
$f=0,69$, motores duplo efeito haste prolongada em ambos os lados

$$N_{cilindrada}=\frac{A_c*P_m*C_m*n_{cilindros}}{75*x}=\frac{A_c*P_m*2*h_2*n_{rotação}*n_{cilindros}}{60*75*x}=\frac{A_c*P_m*h_2*n_{rotação}*n_{cilindros}}{2.250*x}$$

## Cilindros
### Máquina de vapor
#### Monocilíndrica de simples efeito
$x=2$
$n_c=1$

$$N_{indc}=\frac{A_c*P_m*h_2*n_{rotação}}{4.500}$$

#### Monocilíndrica de duplo efeito
$x=2$
$n_c=1$
$$N_{indic}=N_{indic_{lado1}}*N_{indic_{lado2}}$$

#### Policilíndrica de duplo efeito
- Potência total é a soma das potências para cada cilindro e de cada lado do êmbolo

# Motores de commbustão interna
## 4 tempo monocilíndrico, simples efeito
$x=4$
$$N_c=\frac{A_c*P_m*h_2*n_{rotação}}{2*60*75}$$
## 4 tempos, duplo efeito, monocilindrico
$x=2$
$$\frac{A_c*P_m*h_2*n_{rotaçõa}}{4.500}$$
## 2 tempos, simples efeito, monocilíndrico
$x=2$
$$\frac{A_c*P_m*h_2*n_{rotação}}{4.500}$$
## 4 tempos, simples efeito, policindrico
$x=4$
$$\frac{A_c*P_m*h_2*n_{cilindros}*n_{rotação}}{9.000}$$
## 4 tempos, duplo efeito, policilindrica
$x=4$
$$\frac{A_c*P_m*h_2*n_{cilindros}*n_{rotação}}{4.500}$$

## Fórmula geral
$$A_c = f*D^2$$
$$\beta=\frac{h_2}{D}$$
$$h_2 = \beta*D$$

$$N_{indic}=\frac{f*D^2*P_m*betta*D*n_{rotação}*N_c}{60*75*x}=\frac{f*D^3*P_m*Betta*n_{rotação}*n_c}{4.500*x}$$

### Velocidade média do êmbolo
#### Máquina a vapor
1. Com escape livre
$$C_m=4,2 \sqrt{h_2}$$
2. Com condensador
$$C_m=3 \sqrt{h_2}$$

#### MCI
- Motores fixos
- Grandes potências
- Lento
$$C_m=3,5$$
---
- Potência média
$$C_m=3,5 \, a \, 4 ms$$
----
- Velozes, potência média
4 a 5 ms

- Veozes, pequena potência
5 a 7 ms

- Muito velozes de pequena potência
10 ms

- Automóveis
15 ms

- Caminhões
12 ms

#### Valores de $\beta$
a. Máquinasa vapor 
	1,8 a 2 (horizontais)
	1 a 1,5 (verticais)

#### MCI
1 - 1,25 -> Aviões
1 - 1,6 -> Automóveis
0,9 - 1,3 -> Motocicletas
1,6 - 1,3 -> Pequenos motores N < 15 < CV
1,36 - 1,16 -> Motores N < 100 CV
1 - 1,25 -> Grandes motores fixos

## Potência
- Movimento retilíneo produzido pelo vai e vem do êmbolo pela amplitude do [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Curso ($h_2$)\|#Curso ($h_2$)]]

### Potência útil do êmbolo


## Curso ($h_2$)
- Distância entre o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto inferior (pmi)\|ponto morto inferior (pmi)]] 
- Geralmente equivale ao diâmetro do eixo excêntrico do virabrequim 

## Câmara de combustão ou Volume morto ($V_{cam}$)
- Volume do cilindro quando o pistão está no [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]]
-  Volume restante necessário para abertura da válvula (entre o pistão e o cilindro)
$$V_{cam{}} = A_{pistão} * h_1 = \frac{\pi * D^2}{4} * h_1=\frac{V}{TC-1}$$

$V_{cam}$ = Volume da câmara de combustão ou volume morto ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$D$ = Diâmetro da cabeça do pistão ($cm$)
$h_1$ = Altura entre o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o cilindro ($cm$)
$V$ = Cilindrada ($cm^3$)
$TC$ = Taxa de compressão ()

## Cilindrada unitária ($V_u$)
- Volume  entre o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Ponto morto inferior (pmi)\|ponto morto inferior (pmi)]] 

$$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2=f*D^2*h_2$$

$V_u$ = Cilindrada ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão

## Volume total do cilindro ($V_C$)
$$V_c = V_u + V_{cam}=\frac{V_{cam}}{TC-1}$$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]

## Taxa de Compressão ($TC$ ou $\epsilon$)
- Relação entre o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($v$)\|volume da câmara de combustão]] e o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Volume total do cilindro ($V_C$)\|volume total do cilindro]] 
- Indicada por uma razão por unidade 6:1, 8:1...
	- A mistura aspirada é comprimida em 6:1, 8:1... do seu volume
$$TC = \frac{V_u + V_{cam}}{V_{cam}} = \frac{V_{cam}}{V_c}$$
$TC$ = Taxa de compressão (adimensional)
$V_u$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$v$ = Volume da Câmara de Combustão ($cm^3$)

## Cilindrada do motor ($V_m$)
- Produto da [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|cilindrada unitária]] pelo número de cilindros
$$V_m = V_u * nº \, cilindros = \frac{\pi * D^2}{4} * h_2 * nº \, cilindros$$
$V_m$ = Cilindrada do motor
$V_u$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|Cilindrada unitária]] 

## Número de rotações ($n_{rotalção}$)
$$n_{rotação}=\frac{A_c*P*h_2*n_{rotação}}{30}=A_c*P_m*C_m$$
$n_{rotação}$ = Número de rotação em $m s$
$P_m$ = Pressão média sobre o êmbolo ($Kgf$ $cm^2$)

## Velocidade média do êmbolo ($C_m$)
$$C_m = \frac{2*h_2*n_{rotação}}{60}=\frac{h_2*n_{rotação}}{30}$$

## Cilindrada ($C_v$)
$$C_v = \frac{A_c*P_m*C_m*n_{cilindros}}{45*x}$$

$C_m$ = $ms$
1CV = 75 Kgf ms

$x=4$, motores simples de 4 tempos
$x=2$, motores duplo efeito de 4 tempos
$x=2$, motores simples efeito 2 tempos
$x=2$, motores a vopor e simples efeito
$x=1$, motor a vapor de duplo efeito
$x=1$, motores a combustão, duplo efeito e 2 tempos

## Rendimento térmico ou termodinâmico ou ciclo ideal ($n_f$)

$$n_t=\frac{\Sigma Q_{ciclo}}{\Sigma Q_{consumidos}}=\frac
{\Sigma N_{ciclo}}{\Sigma Q_{consumidos}}$$

## Rendimento térmico indicado ($n_{ind}$)
- [[Leis da Termodinâmica copy#2ª Lei da Termodinâmica ($t_0 ne t_1$)\|2 lei da termodinâmica]]
- O calor utilizado segundo o ciclo ideal não se transforma em trabalho
- Se no aparelho indicador determinamos o trabalho representado em um diagrama real encontra-se:

$$W_{ind}<W_{ideal}$$
$$n_{ind}=\frac{W_{ind}}{\Sigma Q_{cons}}=\frac{N_{disponível \, mecânico}}{\Sigma Q_{consumidos}}=\frac{632,3}{B1*PCs}$$

1 $Cvh$ = $m$ -> Combustível por Cv hora
m = B1
$PCs$ = Poder Calorífico Superior

$$1 Cvh = B1 *PCs * n_{ind}$$
$$75 \frac{Kgf}{s} * 3.600 s=B1\frac{Kg}{Cvh}*PCs\frac{Kcal}{Kg}*n_{ind}$$
$n_{ind}$ = 0,28 -> motores a gás
$n_{ind}$ = 0,28 -> motores de benzina
$n_{ind}$ = 0,29 -> motores a gás alto forno
$n_{ind}$ = 0,40 -> Diesel com compressor
$n_{ind}$ = 0,42 -> Diesel sem compressor

## Coeficiente de qualidade do motor ($n_g$)
$$n_g = \frac{n_{ind}}{n_{ideal}}=\frac{W_{ind}}{W_{c \, ideal}}=\frac{P_{ind \, ideal}}{P_{m \, ind \, real}}$$

## Rendimento mecânico ou orgânico ($n_{mec}$) 
- Valor não constante
- Quanto maior a carga normal, maior o rendimento mecânico
- Menor quando trabalha sobrecarregado ou com carga menor que a nominal

$$N_{mec}=\frac{n_{ef}}{N_{ind}}$$
$$n_{atrito}=n_{efit.}-n_{ind}$$


### Valores experimentais
#### Motores a gás
$n_m$ = 0,89 -> máquinas de vapor
$n_m$ = 0,72 a 0,74 -> motores pequenos de gás
$n_m$ = 0,74 -> motores de simples efeito, monocilindricos, 4 tempos
$n_m$ = 0,78 -> duplo efeito, monocilíndrico, 4 tempos
$n_m$ = 0,80 -> motores de simples efeito, policilindrico, 4 tempos
$n_m$ = 0,82 -> duplo efeito, policilídrico, 4 tempos
$n_m$ = 0,82 -> duplo efeito, policíndrico 4 tempos
$n_m$ = 0,82 -> motores 2 tempos ou *segundo Schuultz*

#### Motores de 2 tempos
- Corrigir $n_m$ pelos seguites fatores:

 a. Com bomba de deslocamento
	 0,85 a 0,95

 b. Com deslocamento do Carter
	 0,70 a 0,80

 c. Rendimento econômico
	 $$n_{econ}=n_{ind}*n_g*n_{mec}=\frac{632,3}{B2*PCs}$$
	 B2 = Consumo de cobustível por cada Cv efetivo horas, disponível no eixo do motor
	 PCs = Poder calorífico superior

$$B2=\frac{m_{combustível}}{N_{efetiva}}$$
$$\Delta_{e \, mec. \, eixo \, motor}=\Sigma Q_{consumidos}$$

 d. Rendimento volumétrico
 $$n_{vol}=\frac{V_a}{V_{h2}}$$

 e. Pressão média em função de PCs
 $$P_m = PCs*427*n_{vol}*n_{mec}$$
## Volume da Câmara de compressão
Pa -> Pressão do fluído no início da compressão ou pressão de aspiração
Pc -> Pressão de compressão

$$Pa=V_t^k=P_c*V_c^r=V_t^n=P_c*V_c^n$$
$n$ -> 1,25 a 1,42

$$P_c=P_a*TC^n$$
$$V_c=\frac{V_s}{TC-1}$$
$$V_s=f*D^2*h_2$$