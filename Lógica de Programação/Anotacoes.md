# 🧠💻 Cheat Sheet ABSURDAMENTE COMPLETO: Lógica de Programação (Do Básico ao Avançado)

> Tudo o que um ser humano decente, com sede de código e desprezo por bugs, precisa saber sobre **lógica de programação**.

---

## 📌 Fundamentos Brutos

| Conceito         | Descrição                                                                 | Exemplo                            |
|------------------|---------------------------------------------------------------------------|------------------------------------|
| **Variável**     | Espaço de memória para armazenar valores                                 | `x = 10`                           |
| **Constante**    | Valor imutável após ser definido                                          | `PI = 3.14`                        |
| **Tipo de dado** | Categoria do valor armazenado (int, float, str, bool)                    | `idade = 25` (int)                 |
| **Operadores**   | Símbolos para cálculos e comparações                                     | `+`, `-`, `*`, `/`, `==`, `&&`     |
| **Entrada/Saída**| Comunicação com o usuário                                                 | `input()`, `print()`               |

---

## 🔁 Controle de Fluxo

| Estrutura        | Descrição                                                | Exemplo                                      |
|------------------|----------------------------------------------------------|----------------------------------------------|
| **If/Else**      | Desvio condicional                                       | `if idade >= 18:`                            |
| **Switch/Case**  | Seleção múltipla (equivalente ao if/elif/else)          | `match opcao:` (Python 3.10+)                |
| **While**        | Laço com condição inicial                                | `while saldo > 0:`                           |
| **For**          | Repetição com contador                                   | `for i in range(10):`                        |
| **Break/Continue**| Interrupção ou salto de iteração                        | `break`, `continue`                          |

---

## 🔧 Operadores de Vergar Cérebro

| Tipo               | Operadores                     | Exemplo                      |
|--------------------|--------------------------------|------------------------------|
| **Aritméticos**     | `+ - * / % ** //`              | `x = (a + b) * c`            |
| **Comparação**      | `== != > < >= <=`              | `if x != y:`                 |
| **Lógicos**         | `and or not`                   | `if a > 10 and b < 5:`       |
| **Atribuição**      | `= += -= *= /=`                | `total += 1`                 |
| **Bitwise**         | `& | ^ ~ << >>`                | `a = a << 2`                 |

---

## 🧱 Estruturas de Dados Essenciais

| Estrutura        | Descrição                                     | Exemplo                              |
|------------------|-----------------------------------------------|--------------------------------------|
| **Array/List**   | Lista indexada de elementos                   | `lista = [1, 2, 3]`                  |
| **Tupla**        | Lista imutável                                | `tupla = (1, 2)`                     |
| **Dicionário**   | Conjunto chave:valor                          | `dados = {"nome": "Ana"}`           |
| **Set/Conjunto** | Coleção não ordenada sem valores repetidos    | `set = {1, 2, 3}`                    |
| **Stack/Pilha**  | LIFO: Último a entrar, primeiro a sair        | `stack.append(x); stack.pop()`      |
| **Queue/Fila**   | FIFO: Primeiro a entrar, primeiro a sair      | `queue.append(x); queue.pop(0)`     |

---

## 📚 Funções e Modularização

| Conceito        | Descrição                                            | Exemplo                              |
|------------------|------------------------------------------------------|--------------------------------------|
| **Função**       | Bloco reutilizável de código                         | `def soma(a, b): return a + b`       |
| **Parâmetros**   | Dados passados para a função                         | `soma(2, 3)`                         |
| **Retorno**      | Valor devolvido pela função                          | `return resultado`                   |
| **Recursão**     | Função que chama a si mesma                          | `def fatorial(n): return n*f(n-1)`   |

---

## 🧠 Conceitos Avançados Sem Vergonha

| Conceito             | Descrição                                                         | Exemplo                                      |
|----------------------|-------------------------------------------------------------------|----------------------------------------------|
| **Escopo**           | Onde a variável existe (local vs global)                          | `global x`                                    |
| **Função Lambda**    | Função anônima de uma linha só                                    | `lambda x: x * 2`                             |
| **Closure**          | Função interna que “lembra” o contexto externo                    | `def outer(): def inner(): ...`              |
| **Ponteiros**        | Endereço de memória de uma variável (em C, C++)                   | `int *p = &x;`                                |
| **Casting**          | Conversão de tipo                                                 | `float(5)` ou `int("10")`                    |
| **Expressões Regulares** | Padrões para buscar strings                                 | `import re; re.search(r"\d+", texto)`        |
| **Tratamento de Erros**| Captura de exceções e falhas                                  | `try: ... except: ...`                       |
| **Compilado vs Interpretado** | Código convertido antes ou durante a execução          | C (compilado), Python (interpretado)         |

---

## 🧠 Paradigmas de Programação (Condensado Nuclear)

| Paradigma            | Característica-chave                                  | Exemplo                           |
|----------------------|--------------------------------------------------------|-----------------------------------|
| **Imperativo**       | Sequência de instruções explícitas                     | C, Python                         |
| **Declarativo**      | Define o que fazer, não como fazer                     | SQL, HTML                         |
| **Funcional**        | Usa funções puras, evita estado mutável                | Haskell, Elixir                   |
| **Orientado a Objetos** | Baseado em objetos com estado e comportamento      | Java, C++, Python                 |
| **Lógico**           | Baseado em regras e inferência lógica                  | Prolog                            |

---

## 📚 Bibliografia e Fontes Sem Frescura

- Cormen, T. H., Leiserson, C. E., Rivest, R. L., Stein, C. (2009). *Introduction to Algorithms*.  
- Sebesta, R. W. (2012). *Conceitos de Linguagens de Programação*.  
- Deitel, P., Deitel, H. (2020). *Como Programar em C/C++/Python/Java*.  
- Knuth, D. E. (1997). *The Art of Computer Programming*.  
- [w3schools](https://www.w3schools.com/) — Referência prática de sintaxe.  
- [GeeksforGeeks](https://www.geeksforgeeks.org/) — Conceitos teóricos + prática.  
- [Codecademy](https://www.codecademy.com/) — Cursos interativos para iniciantes.  
- [Python Docs](https://docs.python.org/3/) — Documentação oficial.

---

> **LEMBRETE SAGRADO:** Quem domina lógica, domina qualquer linguagem. A linguagem é só o sotaque. A lógica é o idioma.

