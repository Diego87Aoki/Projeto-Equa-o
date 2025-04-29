# 🎯 Projeto: Calculadora de Raízes de Equação do 2º Grau

> Um projeto Java para praticar tratamento de exceções e cálculo de raízes de equações quadráticas! 🚀

---

## 📂 Estrutura do Projeto

- `AulaPratica1.java` — Classe principal para interação com o usuário.
- `Equacao.java` — Cálculo das raízes com tratamento de erros.
- `NaoTemRaizesReaisException.java` — Exceção personalizada (checada).
- `NaoTemRaizesReaisRuntimeException.java` — Exceção personalizada (não checada).

---

## ⚙️ Tecnologias Utilizadas

- Java 17 ou superior ☕
- Visual Studio Code 💻
- Extension Pack for Java (no VSCode) 🔧

---

## 🛠️ Como Executar

1. Clone este repositório ou baixe os arquivos.
2. Abra a pasta no **Visual Studio Code**.
3. Compile os arquivos:

   ```bash
   javac *.java
   ```

4. Execute o programa:

   ```bash
   java AulaPratica1
   ```

5. Siga as instruções no terminal para informar os valores de `a`, `b` e `c`. 📥

---

## 🧠 Funcionamento

- Solicita ao usuário os coeficientes `a`, `b` e `c`.
- Calcula o valor do discriminante (Δ = b² - 4ac).
- Se Δ ≥ 0:
  - Calcula e exibe as raízes reais.
- Se Δ < 0:
  - Lança uma exceção (`NaoTemRaizesReaisException` ou `NaoTemRaizesReaisRuntimeException`).

---

## 💬 Exemplo de Execução

**Entrada:**

```
Digite o valor de a:
1
Digite o valor de b:
-3
Digite o valor de c:
2
```

**Saída:**

```
Raiz x1: 2.0
Raiz x2: 1.0
Raiz RT x1: 2.0
Raiz RT x2: 1.0
```

Se o delta for negativo:

```
Não existem raízes reais para essa equação (Exceção Checada).
Não existem raízes reais para essa equação (RuntimeException).
```

---

## 📚 Aprendizados

- Tratamento de exceções em Java.
- Diferença entre exceções checadas e não checadas.
- Cálculo de raízes reais de uma equação do 2º grau.

---

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais em **Programação Orientada a Objetos** — Linguagem Java.

Feito com dedicação e prática! 🎓

---

# 🚀 Bora praticar Java!

---
