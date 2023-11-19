---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)/","created":"","updated":""}
---


[[Conhecimento Técnico/Motor\|Motor]]
[[Conhecimento Técnico/Motores de Combustão Interna (MCI)\|Motores de Combustão Interna (MCI)]]
# Exercício 1
> [!info]
> Motor Transversal MPFI Gasolina
> Cilindradas: 1.6 - 1.600 $cm^3$
> Número de Cilindros: 4
> Diâmetro do Cilindro: 79 mm
> Curso do Pistão: 81,5 mm
> Taxa de Compressão: 9,4:1


> [!question] Calcule:
> $m^3$ por Cilindro: 400$cm^3$
> Volume por Cilindro ($V$): 399,48$cm^3$
> Volume Morto ($v$): 47,619$cm^3$
> Altura da Haste ($h$): 0,97 cm -> 9,7 mm

## $m^3$ por Cilindro
$$m^3/cilindro=\frac{1.600}{4}=400cm^3$$

## Cilindrada pela Taxa de Compressão
- Volume total da câmara de combustão
$$V=\frac{\pi*D^2}{4}*Curso$$
$$V=\frac{\pi*7,9^2}{4}*8,15$$
$$V=\frac{\pi*62,41}{4}*8,15$$
$$V=49,016*8,15$$
$$V=399,48cm^3$$


## Volume morto
- Volume restante necessário para abertura da válvula (entre o pistão e o cilindro)
$$v=\frac{V}{TC-1}$$
$$v=\frac{400}{9,4-1}=47,619cm^3$$
## Altura da Haste
$$h=\frac{4*v}{\pi*D^2}$$
$$h=\frac{4*47,619}{\pi*7,9^2}$$
$$h=\frac{190,476}{\pi*62,41}$$
$$h=\frac{190,476}{196,06}$$
$$h=0,97cm$$

# Exercício 1.1
Imagine que a altura $(h)$ do cilindro que compõe o volume morto tenha sido rebaixado em 0,6 mm.
Qual a nova taxa de compressão (TC) do motor?

> [!question]
> $h_{novo}$: 0,91cm
> $v$:44,6 $cm^3$
> TC: 9,97

## Nova altura da Haste
$$h_{novo}=h-0,6$$
$$h_{novo}=9,7-0,6$$
$$h_{novo}=9,1 mm \rightarrow 0,91cm$$

## Novo Volume Morto
$$v=\frac{\pi*D^2}{4}*h$$
$$v=\frac{\pi*62,41}{4}*0,91$$
$$v=49*0,91$$
$$v=44,6cm^3$$
## Taxa de Compressão
$$TC = \frac{V + v}{v}$$
$$TC = \frac{399,48+44,6}{44,6}$$
$$TC = \frac{444,08}{44,6}$$
$$TC=9,95$$ 

# Exercício 2
Calcule as dimensões principais de um motor Diesel
- 4 tempos
- 4 Cilindros
- Sem compressor
- Simples efeito
- Injeção de combustível sob pressão
- Redução de potência média lento de 150 Cv a 275 rpm
- $P_m = 6Kgf/cm^2$
- $f=0,785$ (simples efeito)
- $\beta$ = 1

D=4,95
h_2=

$$N=\frac{f*D^3*P_m*\beta*n_{rotação}*n_c}{4.500*x}$$
$$150=\frac{0,785*D^3*6*1,4*275*4}{4.500*4}=\frac{14.506,8*D^3}{18.000}$$
$$D^3=\frac{14.506,8*150}{18.000}=\frac{2.176.020}{18.000}=120,9$$
$$D=\sqrt[3]{120,9}=4,95$$

---

$$N_{cilindrada}=\frac{A_c*P_m*C_m*n_{cilindros}}{75*x}$$
$$\frac{\pi*D^2}{4}*h_2*n_{cilindros}=\frac{(f*D^2)*P_m*(\frac{h_2*n_{rotação}}{30})*n_{cilindros}}{75*x}$$
$$\frac{\pi*D^2}{4}*h_2*n_{cilindros}*75*x=(f*D^2)*P_m*(\frac{h_2*n_{rotação}}{30})*n_{cilindros}$$
$$\frac{\pi*4,95^2}{4}*h_2*4*75*2=(0,785*4,95^2)*6*(\frac{h_2*275}{30})*4$$
$$\frac{\pi*24,503}{4}*h_2*600=(0,785*24,503)*6*(\frac{h_2*275}{30})*4$$
$$\frac{76,978}{4}*h_2*600=19,235*6*(\frac{h_2*275}{30})*4$$
$$19,245*h_2*600=461,64*(\frac{h_2*275}{30})$$
$$11.547*h_2=461,64*9,167*h_2$$



# Exercício 3
Calcule as principais dimensões dos cilindo de um motor a gás dealto forno horizontal
>[!info]
>- 2 cilindros
>- Duplo efeito
>- 4 tempos
>- Haste saliente em ambos os lados
>- 480 Cv
>- $f$ = 0,96
>- $P_m = 3,8 Kgf/cm^2$
>- (3,8 - 4) para gás alto forno $C_m = 3,5 m/s$
>- (3 - 4 m\s) motor fixo, grande potência, lento 
>- $x$: 2 
>- $\beta$ = 1
>- $D$=280 mm

>[!question] Calcule
>Volume cilindrada = 
>Volume da câmara de compressão = 
>Relação = 



---
$$V_u=f*D^2*h_2$$
$$V_u=0,69*$$

# Exercício 4
>[!info] Dados
>Motor Diesel
>4 tempos
>Simples efeito
>Sem compressão
>Injeção de pressão
>Curso de 400 mm
>Diâmetro do cilindro = 280 mm


>[!question] Calcule:
>Volume da cilindrada = 
>Volume da câmara de compressão = 
>Relação SD = 

$$V_u=f*D^2*h_2$$
$$V_u=0,69*280^2*400$$
$$V_u=21.638.400mm^3$$

---

$$P_a=P_c*V_c^n$$
$$P_a=26*(0,09*V_u)^n$$
$$P_a=26*(0,09*21.638.400)^{0,2}=470,8$$
---
$$\beta=\frac{h_2}{D}=\frac{400}{280}=1,42$$

# Exercício 5
> [!info] Dados
> Motor a gás
> Pobre
> Horizontal
> Bicilindrico
> 4 tempos
> Simples efeito
> Diâmetro do cilindro ($D$) = 30 cm -> 300 mm
> Curso ($h2$) = 50 cm -> 500 mm
> $V_c$ -> 6,2 litros
> $P_a$ = 0,9 Kgf \ $cm^2$
> $n$ = 1,3


>[!question] Calcule
>Razão de compressão volumétrica = 
>Pressão de compressão real = 

$$TC=\frac{V_u+V_{cam}}{V_{cam}}=\frac{V_{cam}}{V_c}$$
$$TC=\frac{\frac{\pi*30^2}{4}*50}{6,2}=\frac{706,85*50}{6,2}=\frac{35.342,9}{6,2}=5.700,4$$

---
Pressão comp.

$$P_c=P_a*TC^n$$
$$P_c=0,9*5.700,4^{1,3}=0,9*76.328=68.695,2$$

# Exercício 6
>[!info] Dados
>Motor de gás
>Mistura combustível gás-ar 450 Kcal \ $mˆ3$
>$n_{vol}$ = 0,85
>$n_{mec}$ = 0,2

>[!question] Calcule
>$P_m$ = 

$$P_m=PCs*427*n_{vol}*n_{mec}$$
$$P_m=450*427*0,85*0,2=32,665$$

# Exercício 7
>[!info] Dados
>Motor Diesel
>4 tempos
>4 cilindros
>Simples efeito
>Gás oil como combustível
>PCs = 9.700 Kcal \ Kg
>Potência efetiva = 150 Cv
>$n_{econ}$ = 0,38

>[!question] Calcule
>Consumo de combustível (B2) = 

$$n_{econ}=\frac{632,3}{B2*PCs}$$
$$0,38=\frac{632,3}{B2*9.700}$$
$$B2=\frac{632,3}{0,38*9.700}$$
$$B2=\frac{632,3}{3.686}$$
$$B2=0,172$$


# Exercício 8
Num motor a gás a potência indicada de acordo com o diagrama, $N_{ind}=47Cv$. A potência medida no eixo do motor $N_{eixo}=35Cv$. O consumo de gás por cada $C_{v\,efetivo} \ h$ é de 0,90 m3 \ h e o PC é 1290. Determine n_mec e n_eco

$$n_{mec}=\frac{n_{efetivo}}{n_{ind}}=\frac{35}{47}=0,745$$
$$n_{eco}=\frac{632,3}{B2*PCs}=\frac{632,3}{0,90*1290}=0,545$$


# Exercício 9

>[!info] Dados
>Motor a querozene
>$PCs$ = 9.900 Kcal \ kg
> Potência indicada = 24,3 Cv
> $n_{mec}$ = 0,79
> B2 = 12,44 kg em 2 horas

>[!question] Calcule:
>Potência efetiva
>$n_{cft}$
>$B2$ = (kg .. cvh)

$$n_{mec}=\frac{n_{efetivo}}{n_{ind}}$$
$$0,79*24,3=n_{efetivo}$$
$$n_{efetivo}=19,197$$
---
$$B2=\frac{m_{combustível}}{N_{efetiva}}=\frac{\frac{12,44}{2}}{19,197}=\frac{6,22}{19,197}=0,324$$


# Exercício 10
>[!info] Dados
>Motor Diesel
>2 tempos
>6 cilindros de dimensão (108 mm x 127 mm)
>Potência máxima = 170 cv a 1.900 rpm

> [!question] Calcule:
> Cilindrada
> Pme
> Momento torçor no eixo do motor

$$V_u=\frac{\pi*D^2}{4}*h_2$$
$$V_u=\frac{\pi*108^2}{4}*127$$
$$V_u=\frac{\pi*11.664}{4}*127$$
$$V_u=\frac{36.643,5}{4}*127$$
$$V_u=9.160,8*127$$
$$V_u=1.163.432,3mm^3 \rightarrow 1.163,4cm^3$$
$$V_u*n_{cilindros}=1.163,4*6=6.980,4cm^3$$
---
P_indicada = $$\frac{A*}{}$$
$$M_t=716,2*\frac{N_{cf}*cv}{n_{rot}*rpm}$$

# Exercício 10
Calcule o Pme de potência que se pode obter ao substituir o cabeçote por outro de igual forma  porém diminuindo o espaço neutro proporcional a $TC = 7$ e supondo um máximo regime de potência a 4.600 rpm.
>[!question] Calcule também:
>Novo $V_{cam}$
>$n_1$ = 
>$n_2$
>$Pme$
>$N_{cv}$
>$V_{cil}$
>$V_c$


# Exercício 11
>[!info] Dados
>Máquina à vapor
>Monocilindo
>Horizontal
>Simples efeito
>Escape livre
>Vapor a atm de pressão
>Potência efetiva = 40 cv

>[!question] Calcule
>Área (A) = 
>Diâmetro (D) = 
>Relação S .. D


# Exercício 12
>[!info] Dados
>Motor Otto
>$T_1 = 303 K$
>$T_2 = 573 K$
>$PCs = 10.500$ Kcal .. kg
>$n_{mec} = 0,875$
>$n_{ind} = 0,36$

>[!question] Calcule:
>$T_v =$
>$n_{econ} =$
>$n_{total} =$
>$m_{combustível}$
>$q =$

$$T_v = \frac{V_1}{V_2}=\sqrt[K-1]{\frac{T_2}{T_1}}=\bigg(\frac{T_2}{T_1} \bigg)^{\frac{1}{k-1}}$$



>[!info] Dados:
>Motor de ciclo Otto
>Cilindrada = 1 litro
>Relação de compressão = $TC = 5,5$
>Potência = 30 cv
>rotação = 400 rpm

# Exercício 13
Determine as dimensões das válvulas de um motor diesel

>[!info] Dados
>Diâmetro do cilindro = $210 mm$
>Curso ($h2$) = $160 mm$
>rpm do eixo = 1.560 rpm

>[!question] Calcule:
>Área do cilindro = $\talXII$
>Velocidade média do cilindro
>Diâmetro interno
>Seção de passagem
>Altura do levantamento normal
>Diâmetro da haste
>Diâmetro da haste

## Área do cilindro ($A_c$)
$$A_c = \frac{\pi}{4}*d^2$$
$$A_c = \frac{\pi}{4}*210^2$$
$$A_c = 34.636 \, mm^2 \rightarrow 0
0346 \, m$$

## Diâmetro interno ($dm$)
$$dm = 0,4 * d$$
$$dm = 0,4 * 0,21$$
$$dm = 0,084 \, m$$

## Seção de passagem ($A_e$)


# Exercício 14
>[!info] Dados
>6 cilindros
>Cilindrada = $4.200 cm^3$ para $4.800cm^3$
>Diâmetro do cilindro = $10 cm$

>[!question] Calcule
>Novo diâmetro do cilindro


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Cilindrada unitária ($V_u$)

$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2=f*D^2*h_2$

$V_u$ = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Cilindrada unitária ($V_u$)\|Cilindrada unitária]]($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão
$D$ = Diâmetro do pistão

</div></div>


$$V_m=\frac{\pi*D^2}{4}*h_2*n_{cilindros}$$
$$4.200=\frac{\pi*10^2}{4}*h_2*6$$
$$4.200=\frac{314}{4}*h_2*6=78,5*h_2*6=471*h_2$$
$$h_2=\frac{4.200}{471}=8,91cm$$
---
 $$4.800=\frac{\pi*D^2}{4}*8,91*6=\frac{\pi*D^2}{4}*53,46$$
$$D^2=\frac{4.800*4}{53,46*\pi}=\frac{19.200}{53,46*\pi}=114,2$$
$$D=\sqrt{114,2}=10,6cm$$

# Exercício 15
>[!info] Dados
>8 cilindros
>Cilindrada = $5l$->$5.000cm^3$
>Taxa de compressão = $9$

>[!question] Calcule
>Volume total de um cilindro em $cm^3$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Câmara de combustão ou Volume morto ($V_{cam}$)
$V_{cam{}} = A_{pistão} * h_1 = \frac{\pi * D^2}{4} * h_1=\frac{V}{TC-1}$

$V_{cam}$ = Volume da câmara de combustão ou volume morto ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$D$ = Diâmetro da cabeça do pistão ($cm$)
$h_1$ = Altura entre o [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o cilindro ($cm$)
$V$ = Cilindrada ($cm^3$)
$TC$ = Taxa de compressão ()


</div></div>


$$V_{cam}=\frac{V}{TC-1}=\frac{5.000}{9-1}=\frac{5.000}{8}=625cm^3$$

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Volume total do cilindro ($V_C$)
$V_c = V_u + V_{cam}=\frac{V_{cam}}{TC-1}$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]
$TC$  = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Taxa de Compressão ($TC$ ou $ epsilon$)\|Taxa de compressão]]


</div></div>


$$V_c=\frac{5.000}{8}+625=1.250cm^3$$

# Exercício 16
>[!info] Dados
> Motor alternativo
> 4 cilindros
> Diâmetro do cilindro = $8,2 cm$
> Curso = $7,8$
> Taxa de compressão = $4,5$

>[!question] Calcule
>Cilindrada ou deslocamento volumétrico do motor em $cm^2$
>Volume total de um cilindro
>Volume morto


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Cilindrada do motor ($V_m$)
- Produto da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|cilindrada unitária]] pelo número de cilindros
$V_m = V_u * nº \, cilindros = \frac{\pi * D^2}{4} * h_2 * nº \, cilindros$
$V_m$ = Cilindrada do motor (cm³)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|Cilindrada unitária]] (cm³)
$D$ = Diâmetro do cilindro (cm)
$h_2$ = Curso (cm)


</div></div>


$$V_m=\frac{\pi*8,2^2}{4}*7,8*4=52,8*7,8*4=1.647cm^3$$

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Câmara de combustão ou Volume morto ($V_{cam}$)
$V_{cam{}} = A_{pistão} * h_1 = \frac{\pi * D^2}{4} * h_1=\frac{V}{TC-1}$

$V_{cam}$ = Volume da câmara de combustão ou volume morto ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$D$ = Diâmetro da cabeça do pistão ($cm$)
$h_1$ = Altura entre o [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o cilindro ($cm$)
$V$ = Cilindrada ($cm^3$)
$TC$ = Taxa de compressão ()


</div></div>


$$V_{cam}=\frac{1647}{4,5-1}=\frac{1647}{3,5}=470cm^3$$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Volume total do cilindro ($V_C$)
$V_c = V_u + V_{cam}=\frac{V_{cam}}{TC-1}$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]
$TC$  = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Taxa de Compressão ($TC$ ou $ epsilon$)\|Taxa de compressão]]


</div></div>


$$V_c=52,8*7,8+470=411,84+470=881cm^3$$
# Exercío 17
>[!info] Dados
>6 cilindros
>Cilindrada = $5,2l$ -> $5.200cm^2$
>Diâmetro dos cilindros = $10,2cm$
>Volume morto = $54,2 cm^3$

>[!question] Calcule
>Curso
>Taxa de compressão
>Volume total de um cilindro


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Cilindrada unitária ($V_u$)

$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2=f*D^2*h_2$

$V_u$ = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Cilindrada unitária ($V_u$)\|Cilindrada unitária]]($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão
$D$ = Diâmetro do pistão

</div></div>


$$\frac{5.200}{6}=\frac{\pi*10,2^2}{4}*h_2=\frac{326,8}{4}*h_2=81,7*h_2$$
$$h_2=\frac{866,6}{81,7}=10,6cm$$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




# Tópicos relacionados
[[Conhecimento Técnico/Motor\|Motor]]
[[Conhecimento Técnico/Motores de Combustão Interna (MCI)\|Motores de Combustão Interna (MCI)]]
[[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)\|Exercícios - Motores de Combustão Interna (MCI)]]

$
 Diâmetros
\def\D{D = Diâmetro \, do \, cilindro \, (comprimento)}
\def\Dp{D_p = Diâmetro \, da \, cabeça \, do \, pistão \, (coprimento)}
%% Volumes
\def\Vcam{V_{cam} = Volume \, da \, câmara \, de \, combustão \, ou \, volume \, morto \, (comprimento³)}
$

## Área do motor de simples efeito ($A_c$)
$A_c = \frac{\pi}{4}*D^2=0,7858*D^2$
$\Ac$
$\D$
## Área do motor de duplo efeito ($A_{c1}$ e $A_{c2}$)

$A_{c1} = \frac{\pi}{4}*D^2$

$A_{c2} = \frac{\pi}{4}*(D^2*d^2)$

## Área do motor de duplo efeito com haste em ambos

$A_{c} = \frac{\pi}{4}*(D^2*d^2)$

## Áreas simplificadas

$A_c = \frac{\pi}{4}*D^2 = f*D^2$
$f=0,785$, motores de simples efeito
$f=0,75$, motores de duplo efeito haste de um lado
$f=0,69$, motores duplo efeito haste prolongada em ambos os lados

$N_{cilindrada}=\frac{A_c*P_m*C_m*n_{cilindros}}{75*x}=\frac{A_c*P_m*2*h_2*n_{rotação}*n_{cilindros}}{60*75*x}=\frac{A_c*P_m*h_2*n_{rotação}*n_{cilindros}}{2.250*x}$

## Cilindros
### Máquina de vapor
#### Monocilíndrica de simples efeito
$x=2$
$n_c=1$

$N_{indc}=\frac{A_c*P_m*h_2*n_{rotação}}{4.500}$

#### Monocilíndrica de duplo efeito
$x=2$
$n_c=1$
$N_{indic}=N_{indic_{lado1}}*N_{indic_{lado2}}$

#### Policilíndrica de duplo efeito
- Potência total é a soma das potências para cada cilindro e de cada lado do êmbolo

# Motores de commbustão interna
## 4 tempo monocilíndrico, simples efeito
$x=4$
$N_c=\frac{A_c*P_m*h_2*n_{rotação}}{2*60*75}$
## 4 tempos, duplo efeito, monocilindrico
$x=2$
$\frac{A_c*P_m*h_2*n_{rotaçõa}}{4.500}$
## 2 tempos, simples efeito, monocilíndrico
$x=2$
$\frac{A_c*P_m*h_2*n_{rotação}}{4.500}$
## 4 tempos, simples efeito, policindrico
$x=4$
$\frac{A_c*P_m*h_2*n_{cilindros}*n_{rotação}}{9.000}$
## 4 tempos, duplo efeito, policilindrica
$x=4$
$\frac{A_c*P_m*h_2*n_{cilindros}*n_{rotação}}{4.500}$

## Fórmula geral
$A_c = f*D^2$
$\beta=\frac{h_2}{D}$
$h_2 = \beta*D$

$N_{indic}=\frac{f*D^2*P_m*betta*D*n_{rotação}*N_c}{60*75*x}=\frac{f*D^3*P_m*Betta*n_{rotação}*n_c}{4.500*x}$

### Velocidade média do êmbolo
#### Máquina a vapor
1. Com escape livre
$C_m=4,2 \sqrt{h_2}$
2. Com condensador
$C_m=3 \sqrt{h_2}$

#### MCI
- Motores fixos
- Grandes potências
- Lento
$C_m=3,5$
---
- Potência média
$C_m=3,5 \, a \, 4 ms$
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
- Movimento retilíneo produzido pelo vai e vem do êmbolo pela amplitude do [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Curso ($h_2$)\|#Curso ($h_2$)]]

### Potência útil do êmbolo


## Curso ($h_2$)


## Câmara de combustão ou Volume morto ($V_{cam}$)
$V_{cam{}} = A_{pistão} * h_1 = \frac{\pi * D^2}{4} * h_1=\frac{V}{TC-1}$

$V_{cam}$ = Volume da câmara de combustão ou volume morto ($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$D$ = Diâmetro da cabeça do pistão ($cm$)
$h_1$ = Altura entre o [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Ponto morto superior (pms)\|ponto morto superior (pms)]] e o cilindro ($cm$)
$V$ = Cilindrada ($cm^3$)
$TC$ = Taxa de compressão ()

## Cilindrada unitária ($V_u$)

$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2=f*D^2*h_2$

$V_u$ = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Cilindrada unitária ($V_u$)\|Cilindrada unitária]]($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão
$D$ = Diâmetro do pistão
## Volume total do cilindro ($V_C$)
$V_c = V_u + V_{cam}=\frac{V_{cam}}{TC-1}$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]
$TC$  = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Taxa de Compressão ($TC$ ou $ epsilon$)\|Taxa de compressão]]

## Taxa de Compressão ($TC$ ou $\epsilon$)
$TC = \frac{V_u + V_{cam}}{V_{cam}} = \frac{V_{cam}}{V_c}$
$TC$ = Taxa de compressão (adimensional)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Volume da Câmara de compressão\|Volume da câmara de compressão]] ($cm^3$)

## Cilindrada do motor ($V_m$)
- Produto da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|cilindrada unitária]] pelo número de cilindros
$V_m = V_u * nº \, cilindros = \frac{\pi * D^2}{4} * h_2 * nº \, cilindros$
$V_m$ = Cilindrada do motor (cm³)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária ($V_u$)\|Cilindrada unitária]] (cm³)
$D$ = Diâmetro do cilindro (cm)
$h_2$ = Curso (cm)

## Número de rotações ($n_{rotalção}$)
$n_{rotação}=\frac{A_c*P*h_2*n_{rotação}}{30}=A_c*P_m*C_m$
$n_{rotação}$ = Número de rotação em $m s$
$P_m$ = Pressão média sobre o êmbolo ($Kgf$ $cm^2$)
$h_2$ = Curso (cm)
$n_{rotação}$ = Número de rotações (rpm)
$A_c$ = Área do cilindro (cm²)
$C_m$ = Velocidade média do êmbolo 
## Velocidade média do êmbolo ($C_m$)
$C_m = \frac{2*h_2*n_{rotação}}{60}=\frac{h_2*n_{rotação}}{30}$

## Cilindrada ($C_v$)
$C_v = \frac{A_c*P_m*C_m*n_{cilindros}}{45*x}$

$C_m$ = $ms$
1CV = 75 Kgf ms

$x=4$, motores simples de 4 tempos
$x=2$, motores duplo efeito de 4 tempos
$x=2$, motores simples efeito 2 tempos
$x=2$, motores a vopor e simples efeito
$x=1$, motor a vapor de duplo efeito
$x=1$, motores a combustão, duplo efeito e 2 tempos

## Rendimento térmico ou termodinâmico ou ciclo ideal ($n_f$)

$n_t=\frac{\Sigma Q_{ciclo}}{\Sigma Q_{consumidos}}=\frac
{\Sigma N_{ciclo}}{\Sigma Q_{consumidos}}$

## Rendimento térmico indicado ($n_{ind}$)
- [[Leis da Termodinâmica copy#2ª Lei da Termodinâmica ($t_0 ne t_1$)\|2 lei da termodinâmica]]
- O calor utilizado segundo o ciclo ideal não se transforma em trabalho
- Se no aparelho indicador determinamos o trabalho representado em um diagrama real encontra-se:

$W_{ind}<W_{ideal}$
$n_{ind}=\frac{W_{ind}}{\Sigma Q_{cons}}=\frac{N_{disponível \, mecânico}}{\Sigma Q_{consumidos}}=\frac{632,3}{B1*PCs}$

1 $Cvh$ = $m$ -> Combustível por Cv hora
m = B1
$PCs$ = Poder Calorífico Superior

$1 Cvh = B1 *PCs * n_{ind}$
$75 \frac{Kgf}{s} * 3.600 s=B1\frac{Kg}{Cvh}*PCs\frac{Kcal}{Kg}*n_{ind}$
$n_{ind}$ = 0,28 -> motores a gás
$n_{ind}$ = 0,28 -> motores de benzina
$n_{ind}$ = 0,29 -> motores a gás alto forno
$n_{ind}$ = 0,40 -> Diesel com compressor
$n_{ind}$ = 0,42 -> Diesel sem compressor

## Coeficiente de qualidade do motor ($n_g$)
$n_g = \frac{n_{ind}}{n_{ideal}}=\frac{W_{ind}}{W_{c \, ideal}}=\frac{P_{ind \, ideal}}{P_{m \, ind \, real}}$

## Rendimento mecânico ou orgânico ($n_{mec}$) 
- Valor não constante
- Quanto maior a carga normal, maior o rendimento mecânico
- Menor quando trabalha sobrecarregado ou com carga menor que a nominal

$N_{mec}=\frac{n_{ef}}{N_{ind}}$
$n_{atrito}=n_{efit.}-n_{ind}$


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
	 $n_{econ}=n_{ind}*n_g*n_{mec}=\frac{632,3}{B2*PCs}$
	 B2 = Consumo de cobustível por cada Cv efetivo horas, disponível no eixo do motor
	 PCs = Poder calorífico superior

$B2=\frac{m_{combustível}}{N_{efetiva}}$
$\Delta_{e \, mec. \, eixo \, motor}=\Sigma Q_{consumidos}$

 d. Rendimento volumétrico
 $n_{vol}=\frac{V_a}{V_{h2}}$

 e. Pressão média em função de PCs
 $P_m = PCs*427*n_{vol}*n_{mec}=\frac{2*\pi*n*N*V_d*P_a}{IME*60*10^6}=\frac{Área \, do \, diagrama}{Comprimento\, da \, base}*K_{mola}$
 n = número de cilindros
 N = velocidade do motor em rpm
 $V_d$ = Volume de deslocamento do cilidro
 $P_d$ = Pressão no diagrama indicador
 IME = Área do diagrama indicador
 PCs = Poder calorifico superior
## Volume da Câmara de compressão
Pa -> Pressão do fluído no início da compressão ou pressão de aspiração
Pc -> Pressão de compressão

$Pa=V_t^k=P_c*V_c^r=V_t^n=P_c*V_c^n$
$n$ -> 1,25 a 1,42

$P_c=P_a*TC^n$
$V_c=\frac{V_s}{TC-1}$
$V_s=f*D^2*h_2$

</div></div>


$$TC=\frac{\frac{5.200}{6}+54,2}{54,2}=\frac{866,6+54,2}{54,2}=\frac{920}{54,2}=16$$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Volume total do cilindro ($V_C$)
$V_c = V_u + V_{cam}=\frac{V_{cam}}{TC-1}$

$V_c$ = Volume total do cilindro ($cm^3$)
$V_u$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Cilindrada unitária($V_u$)\|Cilindrada unitária]] ($cm^3$)
$V_{cam}$ = Volume da [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Câmara de combustão ou Volume morto ($V_{cam}$)\|câmara de combustão]]
$TC$  = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Taxa de Compressão ($TC$ ou $ epsilon$)\|Taxa de compressão]]


</div></div>


$$V_c=866,6+54,2=920,8cm^3$$

# Exercício 18
a) A gasolina foi misturada com ar, formando a mistura ar-combustível, em seguida foi aspirada pelo motor, comprimida, expandadida pela explosão causada pela ignição gerada pela vela, a energia da explosão foi transformada em trabalho, em seguida os gases gerados na combustão são eliminados na exaustão. O cliclo se repetiu até que toda a gasolina fosse consumida.

b) O maior consumo de cobustível por pessoa se dará no carro.

>[!info] Dados
>Ônibus: 
>	2 Km -> 1 l
>	40 pessoas
>Carro: 
>	10 Km -> 1 l
>	1 pessoa

$$Consumo = \frac{\frac{litros}{pessoa}}{km}$$
$$Consumo \, ônibus =\frac{\frac{1}{40}}{2}=\frac{0,025}{2}=0,0125l/pessoa$$
$$Massa \, diesel \, pessoa = consumo * densidade$$
$$Massa \, diesel \, pessoa = 0,0125 * 0,84 = 0,0105Kg/pessoa$$
$$Energia \, liberada \, pessoa = Massa *calor \, combustão $$
$$Energia \, liberada \, pessoa =0,0105 * 42.600 = 447,3 J/pessoa$$
---

$$Consumo \, carro =\frac{\frac{1}{1}}{10}=\frac{1}{10}=0,1l/pessoa$$
$$Massa \, gasolina \, pessoa = consumo * densidade$$
$$Massa \, gasolina \, pessoa = 0,1 * 0,75 = 0,075km/pessoa$$
$$Energia \, liberada \, pessoa = Massa *calor \, combustão $$
$$Energia \, liberada \, pessoa =0,075 * 44.000 = 3.300 J/pessoa$$
---

O consumo por pessoa do ônibus é menor

---

>[!info] Dados
>1 l gasolina -> 3,65 Kg $CO_2$
>1 l diesil -> 4,01 Kg $CO_2$
>...
>Casa -> CEFET = 10 Km
>200 dias letivos
>...
>Carro = 10Km/l
>Carro =  2 pessoas
>...
>Ônibus = 2 Km/l
>Ônibus = 40 pessoas

$$Km_{total \, ano} = (Km * 2) * dias \, letivos$$
$$Km_{total \, ano} = (10 * 2)*200 = (20)*200 = 4.000Km/ano$$

---
$$Consumo \, ano = \frac{Km_{total\,ano}}{consumo}$$
$$Consumo \, ano \, carro= \frac{4.000}{10}=400l$$

$$Consumo \, ano \, ônibus= \frac{4.000}{2}=2.000l$$
---
$$Consumo \, ano \, pessoa \, carro = \frac{consumo}{pessoas}$$
$$Consumo \, ano \, pessoa \, carro = \frac{400l}{2}=200l/pessoa$$
$$Consumo \, ano \, pessoa \, ônibus = \frac{2.000}{40}=50l/pessoas$$
---
$$Emissão \: CO_2 = (l \: pessoa * densidade) * emissão \, l$$
$$Emissão \: CO_2 \, carro = (200 * 0,75) * 3,65 = 547,5Kg CO_2$$
$$Emissão \: CO_2 \, ônibus = (50 * 0,84) * 4,01 = 168,42Kg CO_2$$

# Exercício 19
Determine o consumo de combustível e de calor em um ciclo de um motor de 6 cilindros e 4 tempos com potência efetiva de 746 kW, frequência de rotação do eixo 740 rpm, consumo específico de combustível de 224 g/kWh, PCs do combustível de 42300 Kj/kg

$$m_{combustível} = P_{efet} * N_{ef}$$
$$B_{combustível} = \frac{m_{combustível}}{60*n_{cilindros}}$$
$$b_{ciclo}= \frac{B_{combustível} * n_{revoluções}}{n_{rotação}}$$
$$Q_{consumido}=b_{ciclo}*PCs$$

$m_{combustível}= Massa \, combustível \, (kg/h)$
$N_{ef}=Consumo \, específico \, de \, combustível$
$b_{ciclo} = Consumo \, combustível \, ciclo \, (kg)$
$Q_{consumido} = Calor \, consumido \, em \, um \, ciclo \, (kJ)$

---

$$m_{combustível} = 746 * 224 = 167.104g$$
$$B_{combustível} = \frac{167.104}{60*6}=464,177kg$$
$$b_{ciclo}= \frac{464,177 * 2}{740}=\frac{928,35}{740}=1,25kg$$
$$Q_{consumido}=1,25*42.300=53.066,8 kJ$$

# Exercício 20
Determinar a potência indicada de um motor de combustão interna monocilíndrico de 4 tempos se sua pressão média indicada e 0,67Mpa, o diâmetro do cilindro 105mm, o curso do êmbolo do 130mm e a frequência de rotação 1500Rpm

$$P_i=\frac{2*\pi*n*P_m*h_2*A}{60*10^6}$$
$$P_i=\frac{2*\pi*1.500*0,67*10^6*0,13*0,008659}{60*10^6}=3,138kW$$


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



## Cilindrada unitária ($V_u$)

$V_u=A_{pistão} * h_2 = \frac{\pi*D^2}{4}*h_2=f*D^2*h_2$

$V_u$ = [[Conhecimento Técnico/Fórmulas Motores de Combustão Interna#Cilindrada unitária ($V_u$)\|Cilindrada unitária]]($cm^3$)
$A_{pistão}$ = Área da cabeça do pistão ($cm^2$)
$h_2$ = [[Conhecimento Técnico/Exercícios - Motores de Combustão Interna (MCI)#Curso ($h_2$)\|Curso]] do pistão
$D$ = Diâmetro do pistão

</div></div>


$$V_u=\frac{\pi*D^2}{4}*h_2$$
$$V_u=\frac{\pi*0,105^2}{4}*0,13=0,0087*0,13=0,0011m^3$$

# Exercício 21
Um motor de gasolina 6 cilindros e 4 tempos tem diâmetro interno de 82,55 mm e um curso de 79,5 mm. A área do diagrama modificador tomado de um cilindro é 27,1 $cm^2$ com comprimento de base de 15,24 mm e com constante elástica de mola 4,08 $\frac{bar}{cm}$ sendo a velocidade do motor 2.000 rpm, determine:
>[!info]
>6 cilindros
>4 tempos
>Diamêtro interno = 2,55
>Área = 27,1 $cm^2$
>Curso = 79,5
>Constante elástica da mola = 4,08 bar/cm
>2.000 rpm


1. (IMEP) ou PM
$$P_{m}=\frac{Área \, do \, diagrama}{Comprimento\, da \, base}*K_{mola}$$
$$P_{m}=\frac{27,1}{15,24}*4,08=1,77822*4,08=7,255bar/cm^2$$
2. Potência indicada total 6 cilindros
$$P_i=\frac{2*\pi*n*P_m*h_2*A}{60*10^6}$$
$$P_i=\frac{2*\pi*2.000*7,255*7,95*27,1}{60*10^6}=\frac{19.641.909,26}{60*10^6}=0,327W$$
$$P_{m}=0,327*6=1,9642W$$
# Exercício 22
Um motor consome 0,26 kg de gasolina por cvh do eixo a razão de compressão é 7 e PCs = 11.000 $\frac{kcal}{kg}$, determine:
$1cvh=632,4kcm$
1. $n_{térmico \, total}$
$$n_{témico \, total}=1-\frac{1}{\bigg(\frac{V_1}{V_2}\bigg )^{k-1}}$$
$$n_{témico \, total}=1-\frac{1}{7^{1,4-1}}=1-\frac{1}{7^{0,4}}=1-,459=0,54$$
2. $n_{térmico \, efetivo}$
$$n_{térmico \, efetivo}=\frac{1cv \, efetivo}{m_{combustível}*PCs*n_{combustível}}$$
$$n_{térmico \, efetivo}=\frac{632}{0,25*11.000*1}=\frac{632}{2.750}=0,22$$
3. $n_{efetivo}$
$$n_{efetivo}=\frac{n_{térmico}}{n_{total}}=\frac{0,22}{0,54}=0,4$$

# Exercício 23
>[!info] Dados
>4 cilindros
>Motor alternativo
>Diâmetro 8,2 cm
>Curso = 7,8 cm
>Taxa de Compressão 8,5

>[!question] Calcule
>Cilindrada em $cm^3$
>Volume total do cilindro
>Volume da câmara de combustão

$$V_{u}=\frac{\pi * D^2}{4}*h_{2}$$
$$V_{u}=\frac{\pi * 8,2^2}{4}*7,8=52,81*7,8=411,9cm^3$$
$$v_{cam}=\frac{V}{TC-1}$$
$$v_{cam}=\frac{411,9}{8,5-1}=\frac{411,9}{7,5}=54,9cm^3$$
$$V_{c}=V_{u}+V_{cam}$$
$$V_{c}=411,9+54,9=466,8cm^3$$
