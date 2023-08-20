---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Motores de Combustão Interna (MCI)/","created":"","updated":""}
---


# Tópicos relacionados
[[Conhecimento Técnico/Motor\|Motor]]
[[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)\|Exercícios - Motores de Combustão Interna (MCI)]]
# Conceitos

- O combustível é queimado internamente
- Utilizam os próprios gases de combustão como fluido de trabalho
	- Estes gases realizam os processos de 
		- Compressão
		- Aumento de temperatura (queima)
		- Expansão
		- Exaustão
- Conhecidos como motor a explosão (tecnicamente incorreto)
- Transforma o movimento alternativo (vai e vem) do pistão em movimento rotativo

# Definições

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

$$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2$$

$V_u$ = Cilindrada ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão

## Volume total do cilindro ($V_C$)
$$V_c = V_u + V_{cam}$$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]

## Taxa de Compressão ($TC$ ou $\epsilon$)
- Relação entre o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($v$)\|volume da câmara de combustão]] e o [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Volume total do cilindro ($V_C$)\|volume total do cilindro]] 
- Indicada por uma razão por unidade 6:1, 8:1...
	- A mistura aspirada é comprimida em 6:1, 8:1... do seu volume
$$TC = \frac{V + V_{cam}}{V_{cam}} = \frac{V_{cam}}{V_c}$$
$TC$ = Taxa de compressão (adimensional)
$V$ = Cilindrada do Motor ($cm^3$)
$v$ = Volume da Câmara de Combustão ($cm^3$)

## Cilindrada do motor ($V_m$)
- Produto da [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|cilindrada unitária]] pelo número de cilindros
$$V_m = V_u * nº \, cilindros = \frac{\pi * D^2}{4} * h_2 * nº \, cilindros$$
$V_m$ = Cilindrada do motor
$V_u$ = [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|Cilindrada unitária]] 

## Tempo
- Corresponde a um [[Conhecimento Técnico/Motores de Combustão Interna (MCI)#Curso ($h_2$)\|curso]] do embolo ou a meia volta do eixo do virabrequim

# Classificações

## Propriedade do gás na admissão
- Ar (Diesel)
- Mistura ar combustível (Otto)

## Ciclo de Trabalho
- 2 tempos
- 4 tempos

## Ignição
- Por centelha
- Por compressão

## Número de cilindros
- Monocilíndricos
- Policilíndricos

## Tipo
- Pistão
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/imagens/excalidraw/esquemas-tipos-combustao-interna/#group-qekria-nz-jw-p8-coh-qgq-s-gr" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

$<div class="markdown-embed-title">

# motor a combustao interna de pistao - image

</div>



==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Motor a combustão interna de pistão ^HYCZe1f4

Motor a combustão interna rotativo ^SIA9JwHw


# Embedded files
b00df6b347ab33ddede1335602bc18f3cb141900: [[esquema_combustao_interna_pistao.png]]
10984b08a46e9db4b6bfc9767e60fbe075ad4092: [[esquema_combustao_interna_wankel.png]]



</div></div>

- Rotativo (Wankel)
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/imagens/excalidraw/esquemas-tipos-combustao-interna/#group-k-ue-ds-iu-fue2v3r8-x-by-g" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">

$<div class="markdown-embed-title">

# motor a combustao interna rotativo - image

</div>



==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Motor a combustão interna de pistão ^HYCZe1f4

Motor a combustão interna rotativo ^SIA9JwHw


# Embedded files
b00df6b347ab33ddede1335602bc18f3cb141900: [[esquema_combustao_interna_pistao.png]]
10984b08a46e9db4b6bfc9767e60fbe075ad4092: [[esquema_combustao_interna_wankel.png]]



</div></div>

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