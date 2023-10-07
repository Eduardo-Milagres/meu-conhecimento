---
{"dg-publish":true,"permalink":"/Conhecimento Técnico/Programação/Latex/","tags":["latex"],"created":"","updated":""}
---

# Definição de variáveis

Para definir a variável usa-se o comando:
$\def\myName{John}$
```latex
\def\varibleName{value}
\def\myName{John}
```

>[!warning] Atenção
>Os nome definidos diferenciam maiúsculas e minúsculas (_Case Sensitive_), sendo "*variableName*" e "*variablename*" duas variáveis diferentes.

Para usar as variáveis definidas usa-se:

```Latex
\variableName
Olá, meu nome é \myName
```

>[!info] Resultado
>Olá, meu nome é $\myName$

# Bibliografia
[How to Define Variables in LaTeX? | Baeldung on Computer Science](https://www.baeldung.com/cs/latex-define-variables)