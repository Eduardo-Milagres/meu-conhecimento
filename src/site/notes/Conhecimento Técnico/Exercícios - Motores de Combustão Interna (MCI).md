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

