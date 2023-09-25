---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Exercício - Fadiga/","created":"","updated":""}
---

[[Conhecimento Técnico/Fadiga\|Fadiga]]
# Exercício 1 
>[!info] Dados
Uma peça metalica sob uma carga fletora F.
A mola flutua entre 9,3 kN e 10,67 kN.
Limite de resistência a tração = $\sigma_{rup}=1.400 MPa$ 
Limite de escoamento $\sigma_e = 950MPa$.
Espessura = 18 mm
Fator de acabamento: a = 272MPa e b = -0,995
Sendo um acoplamento forjado para a peça, calcule o fator de seguraça ($FS$) contra o escoamento  e a fadiga.


> [!question] Calcule
> $S_f=$
> $K_a=$
> $d_e=$
> $K_c$


[[Imagens/Excalidraw/Fadiga - Exercício 1\|Fadiga - Exercício 1]]

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements


</div></div>


$$d_1=d_2$$
$$R_1 = R_2 = \frac{F}{2}*d_1$$
Máx
$$R_1=\frac{10.670}{2}*0,15$$
$$R_1=R_2=800,25Nm$$
Mín
$$R_1=R_2=\frac{9.300}{2}*0,15$$
$$R_1=R_2=697,5Nm$$

---
$$K_a = a*\sigma_{rup}^b$$
$$K_a=272*1.400^{-0,995}$$
$$K_a  = 0,201$$

---
$$d_e=0,808*(h*b)^{0,5}$$
$$d_e=0,808(75*18)^{0,5}$$
$$d_e=29,6$$

---
$$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}$$
$$K_b=\bigg(\frac{29,6}{7,62}\bigg)^{-0,1133}$$
$$K_b=0,857$$

---

$$\frac{d}{W}=\frac{10}{75}=0,13$$
$$\frac{d}{H}=\frac{10}{18}=0,55$$

Relação no gráfico = $K_t=2,1$

$$K_f = 1 + q * (K_t-1)$$
$$K_f = 1 + 0,65 * (2,1-1)$$
$$K_f = 1 + 0,65 * 1,1$$
$$K_f = 1 + 0,715$$
$$K_f = 1,715$$

---

$$K_e = \frac{1}{K_f}$$
$$K_e = \frac{1}{1,715}$$
$$K_e = 0,58$$

---

$$S_f'= 0,504 * S_{rup} = 0,504 * S_{\micro}$$
$$S_f'= 0,504 * 1400$$
$$S_f'= 705,6MPa$$

---

$$S_f = 0,201 * 0,857 * 1 * 1 * 0,58 * 705,6$$
$$S_f=70,49MPa$$

-> A partir de 70MPa a peça apresentaria sinais de fadiga, trincas, etc

### Tensão máxima e Mínima
#### Área da peça
$$S=75*18-\pi*\bigg(\frac{d}{2}\bigg)^2$$
$$S=1.350-\pi*\bigg(\frac{10}{2}\bigg)^2$$
$$S=1.350-\pi*25$$
$$S=1.350-78,53$$
$$S=1.271,47$$

---

$$\sigma_{máx}=\frac{P_{máx}}{S}$$
$$\sigma_{mín}=\frac{P_{mín}}{S}$$

$$\sigma_{máx}=\frac{800,25}{1.271,47}=0,63$$
$$\sigma_{mín}=\frac{697,5}{1.271,47}=0,55$$

---

$$\sigma_m=\frac{\sigma_{máx}+\sigma_{mín}}{2}$$
$$\sigma_m=\frac{0,63+0,55}{2}=\frac{1,18}{2}=0,59$$

---

$$\sigma_a=\frac{0,63-0,55}{2}=\frac{0,08}{2}=0,4$$

---

$$FS = \frac{\sigma_a}{S_f}+\frac{\sigma_m}{\sigma_{rup}}=\frac{1}{n}$$

$$\frac{0,4}{70,49}+\frac{0,59}{1.400}=\frac{1}{n}$$
$$0,0057+0,0004=0,0061$$
$$n=\frac{1}{0,0061}=163,9$$

---


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/fadiga/#tensao-de-flexao-sigma-f" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





[[Conhecimento Técnico/Exercício - Fadiga\|Exercício fadiga]]

- Fadiga sob tensão
- Fadiga superficial

## Limite de Resistência à Fadiga por corpo de prova ($S_f$)
- Diagrama S-N
	- Determina a quantidade de ciclos suportados pela peça
	- O limite de resistência a fadiga = Tensão de Ruptura 
		- Tensão de ruptura ($\sigma_{rup}$ ou $S_{\micro}$ ou $S_u$)
		- $S_f$ usado o valor do corpo de prova
		- Para $S_u$ > 1.400 MPa 
		$S_f'= 0,504 * S_{rup} = 0,504 * S_{\micro}$
## Fatores Modificadores
$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$

$S_f$ = Limite de resistência a fadiga
$K_a$ = Fator de acabamento superficial
$K_d$ = Fator devido à temperatura
$K_e$ = Fatores diversos 

## Fator de acabamento ($K_a$)
- Considera o acabamento superficial da peça
$K_a = a *\sigma_{rup}^b$
a e b são tabelados

## Fator devido ao tamanho ($K_b$)
Polegada:
$K_b = \frac{d}{0,3}^{-1133} \rightarrow 0,11 \leqslant d \leqslant 2 $

Milímetro
$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}=1,24*d^{-0,107}$

$K_b = 0,859 - 0,00637...$
### Diâmetro Efetivo
- Para seção transversal não circular
$d_e=0,808 (h*b)^{0,5}$
### Fator devido ao carregamento
Carregamento axial $K_c=1$ ou $K_c=0,922$ ($\sigma_{rep}>1400MPa$)
Carregamento de flexão = $K_c = 1$
Carregamento de cisalhamento e torção = $K_c = 0,577$

### Fator devido à temperatura
 - Em desenvolvimento
 - Fase de testes em laboratório
 - Enquanto não há definição oficial por ensaio laboratorial usa-se $K_d = 1$

### Fator devido à concentração de tensões ($K_f$)
- Presente onde houve modifiação na região
	- Curvaturas
	- Entalhes
	- Perturbações geométricas
- Obtido em tabelas e gráficos

#### Quando não houver entalhes
...

#### Quando houver entalhes
q = sensibilidade -> causada por entalhes ou furos
	- Entre 0 e 1
	- 
$K_f = 1 + q * (K_t-1)$
$K_e = \frac{1}{K_f}$

#### Limite de resistência para vida finita
- Traçar diagrama S-N (não feito)

### Teoria da fadiga acumulada (Teoria de Minner)
(Próxima aula)

### Fator de segurança
- Usar a linha de Goodman
#### Goodman
$\frac{S_a}{S_f}+\frac{S_m}{\sigma_{rup}}=1$

#### Soderberg
...

### Gerber
...

#### Coeficiênte de segurança para tensão de fadiga

$n=\frac{S_a}{\sigma_a}=\frac{S_m}{\sigma_m}$
$FS = \frac{\sigma_a}{S_f}+\frac{\sigma_m}{\sigma_{rup}}=\frac{1}{n}$

## Tensão de flexão ($\sigma_f$)
$I=\frac{(w-d)*h^3}{12}$
$\sigma_f = \frac{b*h^2}{6}=\frac{M_f*c}{I}$
$w$ = Largura
c = linha neutra
d = diâmetro do furo


</div></div>



$$I=\frac{(75-10)*18^3}{12}$$
$$I=\frac{(0,075-0,01)*0,018^3}{12}=\frac{0,065*0,018^3}{12}=\frac{4*10^{-7}}{12}$$
$$I=3*10^{-8}m^4$$

---

$$M=\sigma_{máx}$$
Máx
$$\sigma_f=\frac{M*c}{I}=\frac{800,25*0,009}{3*10^{-8}}=\frac{7,202}{3*10^{-8}}=2,4*10^8Nm^2 \rightarrow 2,4MPa$$

Mín
$$\sigma_f=\frac{M*c}{I}=\frac{697,5*0,009}{3*10^{-8}}=\frac{6,278}{3*10^{-8}}=2,09*10^8Nm^2 \rightarrow 2,09MPa$$

Média
$$\sigma_m= \frac{2,4+4,9}{2}=3,65MPa$$
$$\sigma_a = \frac{4,9-2,4}{2}=1,25MPa$$

---

$$n=\frac{1,25}{70,74}+\frac{3,65}{1.400}=2,79$$
## FS contra escoamento
$$n=\frac{\sigma_{rup}}{\sigma_{máx}}$$
$$n=\frac{950}{2,4}=583$$

Reações em carga, tipos de reação
Carga centrada
Distribuida
Lados das reações
Porque das reações

---
## Correção
A força é aplicada no centro da peça, portanto $w_1 = w_2$ e $R_1 = R_2$
Como $d_1=d_2$ a força será dividade igualmente sobre a peça -> $\frac{F}{2}$
$$w_1=w_2$$
$$R_1=R_2=\frac{F}{2}$$
$$M_f=R*\frac{w}{2}=\frac{F}{2}*\frac{w}{2}=\frac{F*w}{4}$$
$$M_{f\,mín}=\frac{F_{mín}*w}{4}=\frac{9.300N*0,3m}{4}=\frac{2.790Nm}{4}=697,5Nm$$
$$M_{f\,máx}=\frac{F_{máx}*w}{4}=\frac{10.670N*0,3m}{4}=\frac{3.201Nm}{4}=800Nm$$

$R$ = Reação no ponto de apoio (N)
$F$ = Força (N)
$w$ = Comprimento (m)
$M_f$ = Momento fletor (Nm)


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/fadiga/#tensao-de-flexao-sigma-f" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





[[Conhecimento Técnico/Exercício - Fadiga\|Exercício fadiga]]

- Fadiga sob tensão
- Fadiga superficial

## Limite de Resistência à Fadiga por corpo de prova ($S_f$)
- Diagrama S-N
	- Determina a quantidade de ciclos suportados pela peça
	- O limite de resistência a fadiga = Tensão de Ruptura 
		- Tensão de ruptura ($\sigma_{rup}$ ou $S_{\micro}$ ou $S_u$)
		- $S_f$ usado o valor do corpo de prova
		- Para $S_u$ > 1.400 MPa 
		$S_f'= 0,504 * S_{rup} = 0,504 * S_{\micro}$
## Fatores Modificadores
$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$

$S_f$ = Limite de resistência a fadiga
$K_a$ = Fator de acabamento superficial
$K_d$ = Fator devido à temperatura
$K_e$ = Fatores diversos 

## Fator de acabamento ($K_a$)
- Considera o acabamento superficial da peça
$K_a = a *\sigma_{rup}^b$
a e b são tabelados

## Fator devido ao tamanho ($K_b$)
Polegada:
$K_b = \frac{d}{0,3}^{-1133} \rightarrow 0,11 \leqslant d \leqslant 2 $

Milímetro
$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}=1,24*d^{-0,107}$

$K_b = 0,859 - 0,00637...$
### Diâmetro Efetivo
- Para seção transversal não circular
$d_e=0,808 (h*b)^{0,5}$
### Fator devido ao carregamento
Carregamento axial $K_c=1$ ou $K_c=0,922$ ($\sigma_{rep}>1400MPa$)
Carregamento de flexão = $K_c = 1$
Carregamento de cisalhamento e torção = $K_c = 0,577$

### Fator devido à temperatura
 - Em desenvolvimento
 - Fase de testes em laboratório
 - Enquanto não há definição oficial por ensaio laboratorial usa-se $K_d = 1$

### Fator devido à concentração de tensões ($K_f$)
- Presente onde houve modifiação na região
	- Curvaturas
	- Entalhes
	- Perturbações geométricas
- Obtido em tabelas e gráficos

#### Quando não houver entalhes
...

#### Quando houver entalhes
q = sensibilidade -> causada por entalhes ou furos
	- Entre 0 e 1
	- 
$K_f = 1 + q * (K_t-1)$
$K_e = \frac{1}{K_f}$

#### Limite de resistência para vida finita
- Traçar diagrama S-N (não feito)

### Teoria da fadiga acumulada (Teoria de Minner)
(Próxima aula)

### Fator de segurança
- Usar a linha de Goodman
#### Goodman
$\frac{S_a}{S_f}+\frac{S_m}{\sigma_{rup}}=1$

#### Soderberg
...

### Gerber
...

#### Coeficiênte de segurança para tensão de fadiga

$n=\frac{S_a}{\sigma_a}=\frac{S_m}{\sigma_m}$
$FS = \frac{\sigma_a}{S_f}+\frac{\sigma_m}{\sigma_{rup}}=\frac{1}{n}$

## Tensão de flexão ($\sigma_f$)
$I=\frac{(w-d)*h^3}{12}$
$\sigma_f = \frac{b*h^2}{6}=\frac{M_f*c}{I}$
$w$ = Largura
c = linha neutra
d = diâmetro do furo


</div></div>


$$c = \frac{esp}{2}$$
$$\sigma=\frac{M_f*c}{I}=\frac{M_f*c}{\frac{(w-d)*h^3}{12}*d}$$
$$\sigma_{máx}=\frac{800Nm*0,009m}{\frac{(0,075m-0,01m)*0,018^3m}{12}*0,01m}=2,28*10^8Nm^2 \rightarrow 2,28*10^8Pa$$
$$\sigma_{mín}=\frac{697,5Nm*0,009m}{\frac{(0,075m-0,01m)*0,018^3m}{12}*0,01m}=1,99*10^8Nm^2 \rightarrow 1,99*10^8Pa$$
$$\sigma_m=\frac{\sigma_{máx}+\sigma_{mín}}{2}=\frac{2,28*10^8+1,98*10^8}{2}=2,13*10^7Pa$$
$$\sigma_a=\frac{\sigma_{máx}-\sigma_{mín}}{2}=\frac{2,28*10^8-1,98*10^8}{2}=1,46*10^7Pa$$


$$\frac{1}{n}=\frac{\sigma_a}{S_f}+\frac{\sigma_m}{\sigma_{rup}}$$
$$\frac{1}{n}=\frac{14,7MPa*10^7}{70,74MPa}+\frac{213,3MPa*10^7}{1.400MPa}=0,36$$
$$n=\frac{1}{0,36}=2,77$$

---
$$n=\frac{\sigma_{rup}}{\sigma_{máx}}$$
$$n=\frac{950*10^6Pa}{2,28*10^8Pa}=4,16MPa$$

# Exercício 2
Um amola é submetida a uma carga variável, sendo a carga máxima $F=133N$ e a carga mínima $F=66N$. O material da mola é aço $\sigma_{rup}=1.170MPa$ e o diâmetro $d=9,5mm$.
Nesse projeto não foi considerado a concentração de tensão ao longo do comprimento da mola. O acabamento superficial corresponde a um laminado a quente. Qual o número de aplicações de carga N, que causará falha na peça

![[fadiga_exercicio_2.excalidraw\|fadiga_exercicio_2.excalidraw]]

>[!info] Dados
>Mola de aço
>$F_{máx} = 133 N$
>$F_{mín}=66N$
>$\sigma_{rup}=1.170MPa$
>$d=9,5 mm$

## Formulário
$$\sigma=\frac{\sigma_a}{1-\frac{\sigma_m}{\sigma_{rup}}}=a*n^b$$
$$a=\frac{(0,9*\sigma_{rup})^2}{\sigma_f}$$
$$b=-\frac{1}{3}*log\frac{0,9*\sigma_{rup}}{\sigma_f}$$
$$n=\bigg(\frac{\sigma_f}{a}\bigg)^{\frac{1}{b}}$$

## Resolução

$$M_{f \, máx}=F_{máx}*w$$
$$M_{f \, máx}=133N*410mm=133N*0,41m$$
$$M_{f \, máx}=54,53Nm$$

$$M_{f \, mín}=F_{mín}*w$$
$$M_{f \, mín}=66N*41mm=66N*0,41m$$
$$M_{f \, mín}=27,06Nm$$
---
$$S=\frac{\pi*d^4}{4}=\frac{\pi*0,0095^4}{4}=\frac{0,0298}{4}=0,0075m^2$$

$$\sigma_{máx}=\frac{M_{f \, máx}}{S}=\frac{54,53Nm}{0,0075m}=7.308,39N$$
$$\sigma_{mín}=\frac{M_{f \, mín}}{S}=\frac{27,06Nm}{0,0075m}=3.608N$$

---


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/fadiga/#fatores-modificadores" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Fatores Modificadores
$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$

$S_f$ = Limite de resistência a fadiga
$K_a$ = Fator de acabamento superficial
$K_d$ = Fator devido à temperatura
$K_e$ = Fatores diversos 


</div></div>


a -> $57,7MPa$
b -> $-0,718$

$$K_a=a*\sigma_{rup}^b$$
$$K_a=57,7MPa*1.170MPa^{-0,718}=0,36MPa$$

$$K_b=1,24*d=1,24*0,0095=0,0118$$

$$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$$
$$S_f = 0,36 * 0,0118* 1 * 1 * 1 * (0,504*1.170)$$
$$S_f=2,5MPa$$
---

$$a=\frac{(0,9*\sigma_{rup})^2}{S_f}=\frac{(0,9*1.170)^2}{2.016,7}=\frac{1.108.809}{2.016,7}=549,81MPa$$

$$b=-\frac{1}{3}*log\frac{0,9*\sigma_{rup}}{\sigma_f}$$
$$b=-\frac{1}{3}*log\frac{0,9*1.170}{2.016,7}=-\frac{1}{3}*log\frac{1.053}{2.016,7}=-\frac{1}{3}*log \, 0,5221$$
$$b=-\frac{1}{3}*(-0,2822)=0,094$$

---
$$N=\bigg(\frac{S
_f}{a}\bigg)^{\frac{1}{b}}$$
$$N=\bigg(\frac{1.170}{549,81}\bigg)^{\frac{1}{0,094}}=2,12^{\frac{1}{0,094}}=3.083,75$$

---
$$\sigma_f=\frac{M_f}{W}=\frac{M_f}{\frac{I}{y}}=\frac{M_f}{\frac{\pi*d^3}{32}}=\frac{32*M_f}{\pi*d^3}$$
$$\sigma_{f \, máx}=\frac{32*54,53Nm}{\pi*0,0095^3m}=\frac{1.744,96Nm}{\pi*8,574*10^{-7}m}=\frac{1.744,96Nm}{2,694*10^{-6}m}$$
$$\sigma_{f \, máx}=6,478*10^8N$$

$$\sigma_{f \, mín}=\frac{32*27,06Nm}{\pi*0,0095^3m}=\frac{865,92Nm}{\pi*8,574*10^{-7}m}=\frac{865,92Nm}{2,694*10^{-6}m}$$
$$\sigma_{f \, mín}=3,215*10^8N$$

