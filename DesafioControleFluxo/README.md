# 🚀 Desafio Controle de Fluxo  

Este projeto é um exercício prático de **Controle de Fluxo** em Java, no qual implementamos um sistema que recebe dois números inteiros via terminal e imprime uma sequência numérica baseada na diferença entre eles.  

Caso o primeiro número seja maior que o segundo, uma **exceção personalizada** será lançada para indicar o erro.  

---

## 📌 Funcionalidades  

✅ Recebe dois números inteiros via terminal  
✅ Verifica se o primeiro número é **maior** que o segundo  
✅ Se os números forem válidos, imprime uma sequência numérica  
✅ Lança uma exceção customizada (`ParametrosInvalidosException`) caso os valores sejam inválidos  

---

## 🛠️ Como Funciona  

1️⃣ O usuário insere dois números inteiros no terminal.  
2️⃣ Se o primeiro for **menor** que o segundo, o programa imprime uma contagem de `1` até `(segundo - primeiro)`.  
3️⃣ Se o primeiro número for **maior** que o segundo, o programa lança a exceção `ParametrosInvalidosException`.  

---

## 📌 Aprendizados 
* Como utilizar try-catch para tratamento de exceções  
* Como criar e lançar exceções personalizadas em Java
* Uso do for loop para controle de fluxo 
