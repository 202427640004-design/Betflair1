# 📊 Fila de Apostas - BetFair

Este módulo adiciona ao projeto uma estrutura de **fila (FIFO)** para gerenciar apostas em ordem cronológica.

## 📁 Arquivos adicionados

- `src/repositorios/RepositorioApostaFila.java` — implementação da fila.
- `src/aplicacoes/Main.java` — método `testarFila()` para demonstração.

## 🧪 Como testar

1. Certifique-se de que `RepositorioApostaFila.java` está em `src/repositorios/`.
2. Cole o método `testarFila()` no final do `Main.java`.
3. Dentro do método `main()`, adicione:

```java
testarFila();
