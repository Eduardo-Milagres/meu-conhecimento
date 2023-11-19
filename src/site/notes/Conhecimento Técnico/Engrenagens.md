---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Engrenagens/","created":"","updated":""}
---

# Tópicos relacionados

$$
\def\De{D_e = Diâmetro \, externo}
\def\Di{D_i = Diâmetro \, interno}
\def\Dp{D_p = Diâmetro \, primitivo}
\def\P{P = Passo}
\def\M{M = Módulo}
\def\z{Z = Número \, de \, dentes}
\def\h{h = altura \, do \, dente}
\def\k{k = altura \, da \, cabeça}
\def\f{f = altura \, do \, pé}
\def\Ft{F_t = Força \, tangencial}
\def\b{b = Espessura \,  da \, engrenagem}
\def\q{q = Coeficiente \, em \, função \, do \, número \, de \, dentes \, e \, ângulo \, de \, ataque}
$$

# Fórmulas
## Diâmetro primitivo ($D_p$)
$$D_{p}=M*Z$$
$D_{P}$ = Diâmetro primitivo (mm)
$M$ = Módulo (adimensional)
$Z$ = Número de dentes (quantidade)

## Diâmetro externo ($D_e$)
$$D_{e}=M(Z+2)$$
$D_{e}=\De$
$M = \M$
$Z=\Z$

## Diâmetro interno ($D_i$)
$$D_{i}=M(Z-2,33)$$
$\Di$
$\M$
$\z$

## Passo ($P$)
$$P=\pi*M$$
$\P$
$\M$
## Altura do dente ($h$)
$$h=2,166*M$$
$\h$
$\M$
##  Altura da cabeça ($k$)
$$k=M$$

## Altura do pé ($f$)
$$f=1,166*M$$

## Módulo ($M$)
$$M=\frac{F_{t}*Q}{b*\sigma_{f}}$$

$\sigma_{f}=$Tensão admissível à flexão do material

## Carregamento estático ($m$)
* Abaixo de 10 rpm

$$m\geq = \sqrt{\bigg ( \frac{2*M_{t}}{\sigma *K * Y * Z} \bigg)}$$
$$\sigma= \frac{\sigma_{adm}}{K_{s}}$$

## Carregamento dinâmico ($m$)
- Acima de 10rpm
$$m\geq\sqrt[3]{ \frac{2*M_{t}*K_{t}*K_{1}}{\sigma * C_{v} * K *Y*Z*K_{2}} }$$

## Coeficiente de velocidade ou super solicitação dinâmica ($C_v$)
$$C_{v}=\frac{5,6}{5,6+\sqrt{ v }}=\frac{A}{A+v}$$
A = tabelado


## Velociade periférica no $D_p$ ($v$)
$$v=\frac{\pi*d*n}{60}$$

$v=\frac{m}{s}$

## Momento torçor ou Torque ($M_t$ ou $T$)
$$N=\frac{F*V}{75}$$
$$F=\frac{M_{t}}{R}=\frac{2*M_{t}}{D}$$
$$V=\frac{\pi*D*n}{60}$$
$$M_{t}=71.620*\frac{N}{n}=\frac{N*30*75}{\pi*n}$$
$N$ = Potência (Cv)
$F$ = Força (kgf)
$V$ = Velocidade (m/s)
$M_t$ = Momento torçor (kgf/cm ou kgf/m)
$R$ = Raio (m ou cm)
$D$ = Diâmetro (m ou cm)
$n$ = Rotação (rpm)
$W$ = $\pi * n$

# Exercício 1
Dimensionar a engrenagem para carregamento dinâmico.
>[!info] Dados
>Toque a transmitir = $3kgm$
>$\sigma=3\frac{kg}{mm²}$
>$Z=50 \, dentes$
>$n=300 rpm$
>$\beta=20°$
>Espessura = $50mm$
>$Q = 2,8$
>$F_t = 80.000N$
>$SAE 1050=\sigma_{f}=1.400 \frac{kgf}{cm²}$
>$K_{t}=1,33$
>$K_{1}=1,25$
>$K_{2}=1$
>$K=10$
>$Y=0,408$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#modulo-m" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Módulo ($M$)
$M=\frac{F_{t}*Q}{b*\sigma_{f}}$

$\sigma_{f}=$Tensão admissível à flexão do material


</div></div>



$$M=\frac{800*2,8}{0,5*1.400}=3,2$$
$$M=3,2 \rightarrow 3 (tabelado)$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-primitivo-d-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro primitivo ($D_p$)
$D_{p}=M*Z$
$D_{P}$ = Diâmetro primitivo (mm)
$M$ = Módulo (adimensional)
$Z$ = Número de dentes (quantidade)


</div></div>


$$D_{p}=3*50=150cm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-interno-d-i" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro interno ($D_i$)
$D_{i}=M(Z-2,33)$
$\Di$
$\M$
$\z$


</div></div>


$$D_{i}=3(50-2,33)=3*47,67=143cm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-externo-d-e" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro externo ($D_e$)
$D_{e}=M(Z+2)$
$D_{e}=\De$
$M = \M$
$Z=\Z$


</div></div>


$$D_{e}=3(50+2)=3*52=156cm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#passo-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Passo ($P$)
$P=\pi*M$
$\P$
$\M$

</div></div>

$$P=\pi*3=9,42cm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#altura-do-dente-h" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Altura do dente ($h$)
$h=2,166*M$
$\h$
$\M$

</div></div>

$$h=2,166*3=6,5mm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#altura-do-pe-f" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Altura do pé ($f$)
$f=1,166*M$


</div></div>

$$f=1,166*3=3,5cm$$



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#velociade-periferica-no-d-p-v" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Velociade periférica no $D_p$ ($v$)
$v=\frac{\pi*d*n}{60}$

$v=\frac{m}{s}$


</div></div>


$$v=\frac{\pi*6,2*300}{1.000*60}=\frac{5.843.362}{60.000}=0,094$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#coeficiente-de-velocidade-ou-super-solicitacao-dinamica-c-v" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Coeficiente de velocidade ou super solicitação dinâmica ($C_v$)
$C_{v}=\frac{5,6}{5,6+\sqrt{ v }}=\frac{A}{A+v}$
A = tabelado



</div></div>


$$C_{v}=\frac{5,6}{5,4+\sqrt{ 0,094 }}=\frac{5,6}{5,4+0,312}=\frac{5,6}{5,712}=0,9$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#carregamento-dinamico-m" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Carregamento dinâmico ($m$)
- Acima de 10rpm
$m\geq\sqrt[3]{ \frac{2*M_{t}*K_{t}*K_{1}}{\sigma * C_{v} * K *Y*Z*K_{2}} }$


</div></div>

$$m\geq\sqrt[3]{ \frac{2*300*1,33*1,25}{1.400 * 0,9 * 10 *0,408*50*1}}=\sqrt[3]{\frac{9.975}{257.040}}=\sqrt[3]{0,0388}=2,66$$

# Exercício 2
Dimensionar o par de engrenagens

>[!info] Dados
>$\beta = 20°(não \, corrigido)$
>$n=1.200rpm$ -> pinhão
>$R=4/1$-> Razão de redução
>Carregamento com choques
>Engrenagem de média precisão
>SAE 1045 -> $\sigma_{adm}=60\frac{kg}{mm²}$
>Potencial a transmitir -> $N=10Cv$
>$M_t$=6.000kgf/mm
>$K_s$=5 (tabelado)
>$Y$=0,302
>$Z$=17
>$C_v$=0,7
>$K$=10 (tabelado)

>[!question] Calcule
>$M$=
>$D_e$=
>$D_i$=
>$P$=
>$h$=
>$k=M$=
>$f$=

$$\sigma_=\frac{\sigma_{adm}}{K_{s}}=\frac{60}{5}=12\frac{kgf}{mm²}$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#carregamento-dinamico-m" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Carregamento dinâmico ($m$)
- Acima de 10rpm
$m\geq\sqrt[3]{ \frac{2*M_{t}*K_{t}*K_{1}}{\sigma * C_{v} * K *Y*Z*K_{2}} }$


</div></div>

$$m\geq \sqrt[3]{\frac{2*6.000*1,33*2,5}{12*0,7*10*0,302*17*1}}=\sqrt[3]{\frac{39.900}{431,26}}=\sqrt[3]{92,52}=4,52$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-primitivo-d-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro primitivo ($D_p$)
$D_{p}=M*Z$
$D_{P}$ = Diâmetro primitivo (mm)
$M$ = Módulo (adimensional)
$Z$ = Número de dentes (quantidade)


</div></div>

$$D_{p}=4,52*17=76,89 \to 77$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#velociade-periferica-no-d-p-v" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Velociade periférica no $D_p$ ($v$)
$v=\frac{\pi*d*n}{60}$

$v=\frac{m}{s}$


</div></div>

$$v=\frac{\pi*0,077*1.200}{60}=\frac{290,28}{60}=4,84$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#coeficiente-de-velocidade-ou-super-solicitacao-dinamica-c-v" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Coeficiente de velocidade ou super solicitação dinâmica ($C_v$)
$C_{v}=\frac{5,6}{5,6+\sqrt{ v }}=\frac{A}{A+v}$
A = tabelado



</div></div>

$$C_{v}=\frac{6}{6+4,84}=0,55$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#carregamento-dinamico-m" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Carregamento dinâmico ($m$)
- Acima de 10rpm
$m\geq\sqrt[3]{ \frac{2*M_{t}*K_{t}*K_{1}}{\sigma * C_{v} * K *Y*Z*K_{2}} }$


</div></div>


$$M\geq \sqrt[3]{\frac{2*6.000*1,33*2,5}{12*0,55*10*0,302*17*1}}=\sqrt[3]{\frac{39.900}{338,84}}=\sqrt[3]{117,75}=4,9$$
$$M \to 5 \, (tabelado)$$

---
## Recalculo

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-primitivo-d-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro primitivo ($D_p$)
$D_{p}=M*Z$
$D_{P}$ = Diâmetro primitivo (mm)
$M$ = Módulo (adimensional)
$Z$ = Número de dentes (quantidade)


</div></div>

$$D_{p}=5*17=85$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-externo-d-e" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro externo ($D_e$)
$D_{e}=M(Z+2)$
$D_{e}=\De$
$M = \M$
$Z=\Z$


</div></div>

$$D_{e}=5(17+2)=5(19)=95$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#diametro-interno-d-i" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Diâmetro interno ($D_i$)
$D_{i}=M(Z-2,33)$
$\Di$
$\M$
$\z$


</div></div>

$$D_{i}=5(17-2,33)=5*14,67=73,35$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#passo-p" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Passo ($P$)
$P=\pi*M$
$\P$
$\M$

</div></div>

$$P=\pi*5=15,71cm$$

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#altura-do-dente-h" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Altura do dente ($h$)
$h=2,166*M$
$\h$
$\M$

</div></div>

$$h=2,166*5=10,83cm$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/conhecimento-tecnico/engrenagens/#altura-do-pe-f" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Altura do pé ($f$)
$f=1,166*M$


</div></div>

$$f=1,166*5=5,83cm$$

# Exercício 3
>[!info] Dados
>N=16  Cv (potência a transmitir)
>n = 900 rpm (rotação do pinhão)
>E = 180 mm (+5%)
>Perfil envolvente
>$\beta$ = 20°
>Carregamento pulsante
>Oscilação de carga
>Engrenagem de alta precisão
>SAE 1045 -> $\sigma_{rup}$=60 kgf/mm²

