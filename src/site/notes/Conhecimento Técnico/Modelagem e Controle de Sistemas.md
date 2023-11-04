---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Modelagem e Controle de Sistemas/","created":"","updated":""}
---

# Tópicos relacionados

# Generalidades
- Visualiza um sistema de automação de forma gráfica ou de equação.
- Facilita o entendimento dos sistemas de automação.
- Minimiza os erros do sistema para o usuário final.
- Sistema projetado para determinar qual o desvio entre o sinal de entrada e o de saída.
	- O desvio deve ser o mínimo possível para tornar o sistema viável;
	- Otimização contínua para ganho de velocidade.

## Tipos de controladores
1. Proporcional;
2. Integral;
3. Derivativo;
4. Proporcional-integra (PI)
5. Proporcional-derivativo (PD)
6. Proporcional-integral-derivativo (PID)

```mermaid
%%{init: {"flowchart": {"curve": "linear"}}}%%
flowchart LR
	sistemas(Sistemas) --> tipos(Tipos)
		tipos --> natural(Natural)
		tipos --> artificial(Artificial)
		tipos --> natural_artificial(Natural e Artificial)
	 sistemas --> classificacao(Classificação)
		classificacao --> representacao(Representação)
			representacao --> diagrama_equacao(Diagrama de fluxo de sinais + Equação)
			representacao --> grafico(Gráficos)
			representacao --> equacao(Equações)
		classificacao --> configuracoes(Configurações)
			configuracoes --> aberta(Malha aberta)
			configuracoes --> fechada(Malha fechada)
		classificacao --> n_entrada_saida(Número de entradas e saídas)
			n_entrada_saida --> simples(Entrada simples / Saída simples)
			n_entrada_saida --> multipla(Entrada multipla / Saída multipla)
			n_entrada_saida --> multipla_simples(Entrada multipla / Saída simples)
		classificacao --> continuidade(Continuidade do Sinal)
			continuidade --> continuo(Contínuo)
			continuidade --> discreto(Discreto)
```

