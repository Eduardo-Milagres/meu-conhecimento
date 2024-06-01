---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Leis da Termodinâmica/","created":"","updated":""}
---


[[Conhecimento Técnico/Fórmulas -  Termodinâmica\|Fórmulas -  Termodinâmica]]

## 1ª lei da termodinâmica

- Lei da conservação de energia
    - A quantidade total de energia em um sistema isolado é sempre a mesma, exceto quando se transforma em outras energias
    - Conserva a energia em forma de calor e trabalho
    - Realiza trabalho
    
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#variacao-de-energia-interna-delta-u" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

[[Conhecimento Técnico/Exercícios termodinâmica#1. Numa transferência de energia gasosa reversível. ∆u=300J. Houve uma compressão e o trabalho realizado pela força de pressão do gás é em módulo 200J.\|1. Numa transferência de energia gasosa reversível. ∆u=300J. Houve uma compressão e o trabalho realizado pela força de pressão do gás é em módulo 200J.]]

# 2ª Lei da Termodinâmica ($t_0 \ne t_1$)
  Lei da transformação de energia
  Indica a troca de valor que têm tendências para igualar diferentes temperaturas, buscando o [[Conhecimento Técnico/Leis da Termodinâmica#Lei 0 (Equilíbrio térmico)\|equilíbrio térmico]]. Esse processo acontece de forma espontânea.
  O [[Conhecimento Técnico/Conceitos da Termodinâmica#Calor\|calor]] é transmitido do corpo com maior [[Conhecimento Técnico/Conceitos da Termodinâmica#Temperatura\|temperatura]] para o de menor [[Conhecimento Técnico/Conceitos da Termodinâmica#Temperatura\|temperatura]].
  Todo processo tem perda, nenhum sistema é 100%
  Todo calor injetado no sistema gera trabalho e calor (desperdício)
  

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#lei-de-carnot" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



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


</div></div>

  
 * Se $T_2$ fosse igual a 0 K o rendimento seria 100%
 * [[Conhecimento Técnico/Exercícios termodinâmica#3. Calcule\|Ciclo de Carnot]]

# Lei 0 (Equilíbrio térmico)
 - Transfere calor do meio mais quente para o mais frio
 - Tende ao equilíbrio térmico

# 3ª Lei da Termodinâmica
 - Ponto de referência para entropia
 - Não é possível uma substância pura com temperatura 0 apresentar entropia próxima a 0

### Sistema Diatérmico
Permite a troca de valor atravéz da fronteira 

### Sistema Diabático 
Impede a troca de calor atravéz da fronteira havendo variação de temperatura


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#trabalho-por-variacao-de-volume" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

O produto $Pdv$ indica trabalho 
![20230320_190138~2 1.jpg](/img/user/Imagens/20230320_190138~2%201.jpg)


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#variacao-de-energia-interna-delta-u" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

  
- A energia armazenada no sistema tem volume constante. 
- Formando trabalho no sistema ele se armazém como energia interna
- O trabalho fornecido em um sistema é negativo, portanto $∆u$ é positivo


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#variacao-entalpia-delta-h" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

- É a energia trocada a pressão constante


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/formulas-termodinamica/#trabalho-termico-wt" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





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

- Trabalho contínuo por variação de pressão sem atrito


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
  
 -  Base da 2 lei
 - Energia evoluída no processo
 - Função ligada a desordem molecular
 - Definida em um estado de equilíbrio do sistema
 - Derivado do calor em relação a temperatura
 $$P, V, T, M, R$$P = Pressão
 V = Volume 
 T = Tempo
 M = Massa
 R = Constante do gás (ar = 287 J/KgK)

# Notas
NR13 - Vasos de pressão

Condensado de água ≈ 60°C 
