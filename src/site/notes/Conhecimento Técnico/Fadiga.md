---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Fadiga/","created":"","updated":""}
---


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

## Tensão de flexão
$$I=\frac{(w-d)*h^3}{12}$$
$$\sigma_f = \frac{b*h^2}{6}=\frac{M*c}{I}$$
$w$ = Largura
c = linha neutra
