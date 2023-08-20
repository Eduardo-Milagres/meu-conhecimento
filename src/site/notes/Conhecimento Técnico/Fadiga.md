---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Fadiga/","created":"","updated":""}
---


- Fadiga sob tensão
- Fadiga superficial

## Limite de Resistência à Fadiga por corpo de prova ($S_f$)
- Diagrama S-N
	- Determina a quantidade de ciclos suportados pela peça
	- O limite de resistência a fadiga = Tensão de Ruptura 
		- Tensão de ruptura ($\sigma_{rup}$ ou $S_{\micro}$ ou $S_u$)
		- $S_f$ usado o valor do corpo de prova
		- Para $S_u$ > 1.400 MPa 
		$$S_f'= 0,504 * S_{rup} = 0,504 * S_{\micro}$$
## Fatores Modificadores
$$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$$

$S_f$ = Limite de resistência a fadiga
$K_a$ = 
$K_d$ = Fator devido à temperatura
$K_e$ = Fatores diversos 

## Fator de acabamento ($K_a$)
- Considera o acabamento superficial da peça
$$K_a = a *\sigma_{rup}^b$$
a e b são tabelados

## Fator devido ao tamanho ($K_b$)
Polegada:
$$K_b = \frac{d}{0,3}^{-1133} \rightarrow 0,11 \leqslant d \leqslant 2 $$

Milímetro
$$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}=1,24*d^{-0,107}$$

$$K_b = 0,859 - 0,00637...$$
### Diâmetro Efetivo
- Para seção transversal não circular
$$d_e=0,808 (h*b)^{0,5}$$
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
$$K_f = 1 + q * (K_t-1)$$
$$K_e = \frac{1}{K_f}$$

#### Limite de resistência para vida finita
- Traçar diagrama S-N (não feito)

### Teoria da fadiga acumulada (Teoria de Minner)
(Próxima aula)

### Fator de segurança
- Usar a linha de Goodman
#### Goodman
$$\frac{S_a}{S_f}+\frac{S_m}{\sigma_{rup}}=1$$

#### Soderberg
...

### Gerber
...

#### Coeficiênte de segurança para tensão de fadiga

$$n=\frac{S_a}{\sigma_a}=\frac{S_m}{\sigma_m}$$
$$FS = \frac{\sigma_a}{S_f}+\frac{\sigma_m}{\sigma_{rup}}=\frac{1}{n}$$
 

# Exercício 1 
Uma peça metalica sob uma carga fletora F.
A mola flutua entre 9,3 e 10,67 kN.
Limite de resistência a tração = $\sigma_{rup}=1.400 MPa$ 
Limite de escoamento $S_e = 950MPa$.
Espessura = 18 mm
Fator de acabamento: a = 272MPa e b = -0,995
Sendo um acoplamento forjado para a peça, calcule o fator de seguraça ($F_s$) contra o escoamento  e a fadiga.

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
$$S=75*8-\pi*\bigg(\frac{d}{2}\bigg)^2$$
$$S=600-\pi*\bigg(\frac{10}{2}\bigg)^2$$
$$S=600-\pi*25$$
$$S=600-78,53$$
$$S=521,47$$

---

$$\sigma_{máx}=\frac{P_{máx}}{S}$$
$$\sigma_{mín}=\frac{P_{mín}}{S}$$

$$\sigma_{máx}=\frac{800,25}{521,47}=1,53$$
$$\sigma_{mín}=\frac{697,5}{521,47}=1,33$$

---

$$\sigma_m=\frac{\sigma_{máx}+\sigma_{mín}}{2}$$
$$\sigma_m=\frac{1,53+1,33}{2}=\frac{2,86}{2}=1,43$$

---

$$\sigma_a=\frac{1,53-1,33}{2}=\frac{0,2}{2}=0,1$$

---

$$n=\frac{S_a}{\sigma_a}=\frac{S_m}{\sigma_m}$$


Reações em carga, tipos de reação
Carga centrada
Distribuida
Lados das reações
Porque das reações
