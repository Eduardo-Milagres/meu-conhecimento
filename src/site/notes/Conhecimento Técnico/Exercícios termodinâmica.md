---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Exercícios termodinâmica/","created":"","updated":""}
---


---
# Páginas
	[[Leis da Termodinâmica copy\|Leis da termodinâmica]]
	[[Conhecimento Técnico/Conceitos da Termodinâmica\|Conceitos da Termodinâmica]]

---
## [[Conhecimento Técnico/Leis da Termodinâmica#1ª lei da termodinâmica\|1ª lei da termodinâmica]]
#### 1.  Numa transferência de energia gasosa reversível. ∆u=300J. Houve uma compressão e o trabalho realizado pela força de pressão do gás é em módulo 200J.

$$Q=∆u+W$$
$$Q=300+200=500J$$

c) recebeu 500J de calor do meio.

## 2. Determine o trabalho realizado por um gás em expansão, que teve seu volume alterado de $5*10^6m^3$ para $10*10^6m^3$ em uma transformação à pressão constante de $4*10^5N/m^2$



<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





Data: 24/05/23

# [[Conhecimento Técnico/Conceitos da Termodinâmica#Ciclo Carnot\|Ciclo de Carnot]]
## 3. Calcule

- O conjunto constitui um [[Conhecimento Técnico/Conceitos da Termodinâmica#Sistema Fechado\|sistema fechado]] fomado por 4 [[Conhecimento Técnico/Conceitos da Termodinâmica#Sistema Aberto\|sistemas abertos]]
- Usado como ciclo padrão ou cilco de comparação para julgamento de outros ciclos

$\def\m{0,05} m = 0,05 Kg/s$
$\def\Ta{940} T_1=940 \, K$
$\def\Tc{301,282} T_3=301,282 \, K$
$\def\Pa{8,4*10^5} \def\Pd{\Pa} P_1=P_4=8,4*10^3 \, Kpa \rightarrow *1.000=\Pa N/m^2$
$\def\R{287} R=29,28577 \, KgFm/KgK \rightarrow *9,8=287*10^5\frac{J}{KgK}=\frac{Nm}{KgK}\rightarrow 287KJ/KgK$
$\def\Cv{0,716} Cv=0,716 \,Kj/Kg \, K$
$\def\Qab{4,2} Q_{1-2}=4,2 \, KJ/s$

> [!question] Calcule
$T_2=$ 
$T_4=$ 
$Cp=\Cp KJ/KgK$
$K=\K$
$V_1=V_4=\Va m/s$
$V_2=\Vb$
$V_3=\Vc$
$P_2=$
$η_{térmico}=$
$Pme=$
$W_{2-3}=$
$\sum_{ciclo}=$

1 -> 2 (Isoterma)
	 $P_1*V_1=m*R*T_1$
	 $V_1=\frac{m*R*T_1}{P_1}$ $V_1=\frac{\m*\R*\Ta}{\Pa}$
	 $V_1=\frac{13.489}{\Pa}=0,016 m/s$
	 $\def\Va{0,002}$
---


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#calor-especifico-em-pressao-constante-c-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Calor Específico em Pressão Constante ($C_p$)
$C_p = R + C_v = K * C_v$


</div></div>

$Cp=\R+\Cv$
$Cp=287,716kJ/KgK$
$\def\Cp{287,719}$
---


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#constante-de-boltzmann-k" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Constante de Boltzmann ($K$)
$K=\frac{Cp}{Cv}$


</div></div>
 
$K=\frac{\Cp}{\Cv}$
$K=401,842$
$\def\K{401,842}$

---
$V_2=Q_{1-2}=m*R*T_1*ln\frac{V_2}{V_1}=P_1*V_1*ln\frac{V_2}{V_1}$
$V_2=m*R*T_1*ln\frac{Q_{1-2}}{V_1}$
$V_2=\m*\R*ln\frac{\Qab}{\Va}$
$V_2=14,35*ln\frac{\Qab}{\Va}$
$V_2=14,35*ln\,2.100$
$V_2=14,35*7,65$
$V_2=109,773m^3/s$
$\def\Vb{109,773}$

- 2 -> 3: Isentropa
>[!info]- Fórmulas
$T_2*V_2^{K-1} = T_3*V_3^{k-1}$
$\frac{T_2}{T_3}=\bigg(\frac{V_3}{V_2}\bigg)^{K-1}$
$\frac{T_3}{T_2}=\bigg(\frac{V_2}{V_3}\bigg)^{K-1}$
$\frac{T_3}{T_2}=\bigg(\frac{V_2}{V_3}\bigg)^{K-1}$

$\frac{P_2}{P_1}=\bigg(\frac{V_1}{V_2}\bigg)^K$
$P_2=\bigg(\frac{V_1}{V_2}\bigg)^K*P_1$
$P_2=\bigg(\frac{\Va}{\Vb}\bigg)^{\K}*\Pa$
$P_2=\bigg(\frac{\Va}{\Vb}\bigg)^{\K}*\Pa$
---

- 4-> 1: Isentropa
>[!info]- Fórmulas
$T_1*V_1^{K-1} = T_4*V_4^{k-1}$
$\frac{T_1}{T_4}=\bigg(\frac{V_4}{V_1}\bigg)^{K-1}$
$\frac{T_4}{T_1}=\bigg(\frac{V_1}{V_4}\bigg)^{K-1}$
$T_3=T_4$
$\frac{T_3}{T_1}=\bigg(\frac{V_1}{V_4}\bigg)^{K-1}$
portanto:
$\frac{V_2}{V_3}=\frac{V_1}{V_4} \rightarrow \frac{V_3}{V_4}=\frac{V_2}{V_1}$


## 4. Calcule
No ciclo de refrigeração são dados:
$\def\CppkJ{1,04} \def\CppJ{1.040} C_p=\Cpp kJ/kgK \rightarrow 1.040J/kgK$
$\def\Paa{5*10^6} P_1=\Paa N/m^2=50 \, bar$
$\def\Pbb{1*10^6} P_2=\Paa N/m^2=50 \, bar$
$\def\Taa{550} \def\Tcc{\Taa} T_1=T_3=\Taa K$
$\def\RR{256} R=\RR J/kgK$
$\def\mm{1,2} m=\mm kg/s$

>[!question] Calcule
>$C_v=\Cvv$
>$K=\KK$
>$T_2=$
>$V_1=$
>$V_2=V_3=$
>$P_3=$
>$W_{1-2}=$
>$Q_{2-3}=$
>$\delta s_{2-3}=$
>$\delta s_{3-1}=$
>$Q_{3-1}=$
>$\sum Q_{ciclo}=$
>$\sum Q_{consumida}=$
>$\sum Q_{desprendida}=$
>$\epsilon=$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#calor-especifico-em-volume-constante-c-v" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Calor Específico em Volume Constante($C_v$)
$C_v = C_p - R = \frac{R}{K - 1} = \frac{C_p}{K}$


</div></div>

$C_v=\CppJ-\RR$
$\def\Cvv{787} C_v=\Cvv J/kgK$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#constante-de-boltzmann-k" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Constante de Boltzmann ($K$)
$K=\frac{Cp}{Cv}$


</div></div>

$K=\frac{\CppJ}{\Cvv}$
$\def\KK{1,321}K=\KK$

---

 $P_1*V_1=m*R*T_1$
	 $V_1=\frac{m*R*T_1}{P_1}$ $V_1=\frac{\mm*\RR*\Taa}{\Paa}$
	 $V_1=\frac{168.960}{\Paa}=0,034m/s$

---

$\Delta s_{1-2}=0$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#variacao-entropia-delta-s" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





## Calor ($Q$)
$Q = \Delta u + W$
## Lei de Carnot
$\frac{Q_a}{Q_b}=\frac{T2}{T1}$
  $η=\frac{Qa-Qb}{Qa}=\frac{T}{Qa}=1-\frac{T2}{T1}=1-\frac{Qb}{Qa}$

  η = rendimento 
  Qa = calor fornecido por aquecimento 
  Qb = calor não transformado em trabalho
  T = trabalho
  T1 = fonte quente
  T2 = fonte fria 
  --> Sempre divide-se a temperatura menor pela maior (Qb/Qa)(T2/T1)

## Temperatura ($T$)
$T=\frac{P*V}{m*R}$

## Trabalho por variação de volume ($W_{dv}$)
$Wif = - (-P*A)x = P * A*x=P*V$

$dWif=Pfv \rightarrow Wif = \int P dv$

## Variação de energia interna ($\Delta u$)
$\Delta u = Q - W$
$∆u = \int m\, * Cv * dt = m * Cv * \int dt\, = \frac{3}{2} \, n * R * \Delta t$
  
$\Delta u$ = Energia final - Energia  inicial

$∆Wif + ∆u = uf - ui$
Q = Calor
W = Trabalho
m = massa
Cv = 
t = temperatura (K)
n = número de mols do gás
R = constante do gás

## Variação Entalpia ($\Delta H$)

$∆H = m * Cp * \int ∆u\ = u + Pv = m * Cv * (tf - ti) + m * R * T$
$\frac{∆H}{∆u}=\frac{K*\frac{Wif}{(k-1)}}{\frac{Wif}{(k-1)}}$
## Trabalho ($W$)
$W=p*\Delta V$
W = trabalho
p = pressão
$\Delta$V = variação de volume

## Trabalho Térmico ($Wt$)
$Wt = \int_f ^ i \, Vap$
## Variação entropia ($\Delta s$) 
$\Delta s = \frac{dQ}{t} = m * R * ln \frac{V_f}{V_i} = m * R * ln \frac{P_f}{P_i}$

## Calor Específico em Pressão Constante ($C_p$)
$C_p = R + C_v = K * C_v$

## Calor Específico em Volume Constante($C_v$)
$C_v = C_p - R = \frac{R}{K - 1} = \frac{C_p}{K}$

## Constante de Boltzmann ($K$)
$K=\frac{Cp}{Cv}$

## Constante universal do gás ($R$)
$R = C_p - C_v = C_v(K - 1)$


## Pressão ($P$)
$P = \frac{m}{V} * R * T = \rho * R * T = \frac{\gamma}{g} * R * T$


</div></div>

$\Delta s = \frac{dQ}{t}=m*R*ln\frac{V_f}{V_i}=m*R*ln\frac{P_f}{P_i}$

</div></div>
