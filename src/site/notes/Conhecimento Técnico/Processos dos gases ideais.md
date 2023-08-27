---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Processos dos gases ideais/","created":"","updated":""}
---


# Tópicos relacionados
[[Conhecimento Técnico/Fórumlas Termodinâmica\|Fórmulas básicas da termodinâmica]]

## Isotérmico / Isotermo (*Boyle - Marriote*) ($T_i=T_f$)
- [[Conhecimento Técnico/Conceitos da Termodinâmica#Temperatura\|Temperatura]] constante ($T_i=T_f$)
- [[Conhecimento Técnico/Fórumlas Termodinâmica#Variação de energia interna ($ Delta u$)\|Variação de energia interna]] ($\Delta u$) = 0
- [[Conhecimento Técnico/Fórumlas Termodinâmica#Variação Entalpia ($ Delta H$)\|Variação da entalpia]] ($\Delta H$ ) = 0
- [[Conhecimento Técnico/Processos dos gases ideais#Trabalho por variação de volume ($W_{dv}$)\|Trabalho por variação de volume]] = [[Conhecimento Técnico/Processos dos gases ideais#Trabalho por variação de pressão ($W_{dp}$)\|Trabalho por variação de pressão]] = [[Conhecimento Técnico/Conceitos da Termodinâmica#Calor\|Calor]]-> ($W_{dv}=W_{dp}=Q$) 

### Trabalho por variação de volume ($W_{dv}$)
$$W_{dv} = m * R * T_i * ln \frac{V_f}{V_i} = m * R * T_i * ln \frac{P_i}{P_f}$$
$$W_{dv} = W_{dp} = Q$$

### Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = m * R * T_i * ln \frac{P_i}{P_f} = m * R * T_i * ln \frac{V_f}{V_i}$$
$$W_{dp} = W_{dv} = Q$$
### Variação entropia ($\Delta s$)

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/forumlas-termodinamica/#variacao-entropia-delta-s" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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


## Isóbaro *(Gay-Lussak)* ($P_i = P_f$)
- [[Conhecimento Técnico/Conceitos da Termodinâmica#Pressão ($P$)\|Pressão]] constante ($P_i=P_f$)
- Trabalho por variação de pressão ($W_{dp}$) = 0
- [[Conhecimento Técnico/Conceitos da Termodinâmica#Calor\|Calor]] = [[Conhecimento Técnico/Fórumlas Termodinâmica#Variação Entalpia ($ Delta H$)\|Variação da entalpia]] ($Q = \Delta H$)

### Trabalho por variação de volume ($W_{dv}$)
$$W_{dv} = P_i(V_f-V_i) = m * R(T_f-T_i)$$

### Variação de energia interna ($\Delta u$)
$$\Delta u = m * C_v(T_f-T_i) = \frac{W_{dv}}{K-1}$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = m * C_p * (t_f-T_i) = \frac{K * W_{dv}}{K-1} = K * \Delta u$$

### Variação da entropia ($\Delta s$)
$$\Delta s = m * C_p * ln \frac{T_f}{T_i} = m * C_p * ln \frac{V_f}{V_i}$$

## Isométrico / Isovolumétrico / Isocóro *(Charles)* ($V_i=V_f$)
- [[Conhecimento Técnico/Propriedades da matéria#Volume ($V$)\|Volume]] constante ($V_i=V_f$)
- Se não há variação de [[Conhecimento Técnico/Propriedades da matéria#Volume ($V$)\|volume]] (V), o [[Conhecimento Técnico/Processos dos gases ideais#trabalho por variação de volume ($W_{dv}$)\|trabalho por variação de volume]] ($W_{dv}$) é 0. ($W_{dv} = 0$)

### Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = - V_i(P_f - P_i) = -m * R * (T_f- T_i) = -(K-1) \Delta u = \frac{(K-1) \Delta H}{K}$$

### Variação de energia interna ($\Delta u$)
$$m * C_v * (T_f - T_i)$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = m * C_p * (T_f - T_i) = K * \Delta u$$

### Variação da entropia ($\Delta s$)
$$\Delta s = m * C_v * ln \frac{T_f}{T_i} = m * C_v * ln \frac{P_f}{P_i}$$

## Isentropo / Isentrópico ($S_i = S_f$)
- [[Conhecimento Técnico/Conceitos da Termodinâmica#Entropia ($S$)\|Entropia]] constante ($S_i = S_f$)
- O sistema é isolado termicamente
- Variação de [[Conhecimento Técnico/Conceitos da Termodinâmica#Calor\|calor]] = variação da [[Conhecimento Técnico/Conceitos da Termodinâmica#Entropia ($S$)\|entropia]] = 0 -> ($Q = \Delta s = 0$)
- Trabalho por variação de volume = - [[Conhecimento Técnico/Fórumlas Termodinâmica#Variação de energia interna ($ Delta u$)\|variação de energia interna]] ($W_{dv} = - \Delta u$)

### Constante de Boltzmann ($K$) 
$$K = \frac{C_p}{C_v} = 1 + \frac{R}{C_v}$$
### Relações
1. $$\frac{V_i}{V_f} = \bigg( \frac{P_f}{P_i} \bigg) ^ \frac{1}{K} = \bigg(\frac{T_f}{T_i} \bigg )^ \frac{1}{K-1}$$
2. $$\frac{T_f}{T_i} = \bigg( \frac{P_f}{P_i} \bigg) ^ \frac{K-1}{K} = \bigg(\frac{V_i}{V_f} \bigg )^ {K-1}$$
3. $$\frac{V_f}{V_i} = \bigg( \frac{P_i}{P_f} \bigg) ^ \frac{1}{K} = \bigg( \frac{T_i}{T_f} \bigg) ^ \frac{1}{K-1}$$
### Trabalho por variação de volume ($W_{dv}$)
1. 
$$ W_{df} = - \Delta u =  
\frac{P_i * V_i}{K - 1} * \bigg[ 1 - \bigg( \frac{V_i}{V_f} \bigg)^{K-1} \bigg] = 
\frac{P_i * V_i}{K - 1} * \bigg[ 1 - \bigg( \frac{P_f}{P_i} \bigg)^ \frac{K-1}{K} \bigg] =
$$ 
$$
= \frac{m * R}{K - 1} (T_i - T_f) = 
\frac{P_i * V_i - P_f * V_f}{K-1} = 
$$
2. $$ T_f - T_i = \frac{- W_{dv}}{m * R} = \frac{- W_{dv}}{m * C_v}$$
###  Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = K - W_{dv}$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = - W_{dp} = m * C_p(T_f-T_i) = K * \Delta u = -K * W_{dv}$$


## Polítropo / Polítropico ($dQ \neq 0, \, dS \neq 0, \, \Delta s \neq 0$)
- Usa-se o coeficiente polítropo ($n$) no lugar da [[Conhecimento Técnico/Fórumlas Termodinâmica#Constante de Boltzmann ($K$)\|constante de Boltzmann]] ($K$)
- [[Conhecimento Técnico/Conceitos da Termodinâmica#Sistema\|Sistema]] não isolado termicamente

1. $$P_i * V_i^n = P_f * V_f^n$$
2. $$\frac{P_f}{P_i} = \bigg( \frac{V_i}{V_f} \bigg) ^ n$$
3. 