# 📚 Sistema de Biblioteca Simples em C#

## 📌 Descrição

Este projeto é um sistema simples de biblioteca desenvolvido em C#. Ele permite cadastrar livros e alunos, além de simular o empréstimo de livros.

O programa utiliza conceitos básicos de programação orientada a objetos, como classes, atributos, construtores e métodos.

---

## ⚙️ Funcionalidades

* Cadastro de livros
* Cadastro de alunos
* Exibição de informações dos livros
* Exibição de dados dos alunos
* Controle de disponibilidade dos livros
* Simulação de empréstimo

---

## 🧱 Estrutura do Código

### 📖 Classe `Livro`

Responsável por representar os livros da biblioteca.

**Atributos:**

* `Titulo`
* `Autor`
* `AnoPublicacao`
* `Disponivel`

**Métodos:**

* `ExibirDetalhes()` → Mostra as informações do livro
* `Emprestar()` → Marca o livro como emprestado

---

### 👨‍🎓 Classe `Aluno`

Representa os alunos que podem pegar livros emprestados.

**Atributos:**

* `Nome`
* `Matricula`
* `Turma`

**Método:**

* `ExibirDados()` → Mostra os dados do aluno

---

### 🚀 Classe `Program`

Contém o método `Main`, que executa o sistema.

**O que acontece no programa:**

* Cria uma lista de livros
* Adiciona livros (com e sem parâmetros)
* Cria alunos
* Realiza um empréstimo
* Exibe a lista de livros
* Exibe os dados do aluno responsável

---

## ▶️ Como Executar

1. Abra o projeto em uma IDE (como Visual Studio ou VS Code)
2. Compile o código
3. Execute o programa
4. Veja os dados sendo exibidos no console

---

## 💡 Exemplo de Saída

```
LISTA DE LIVROS CADASTRADOS
Título: Sem título
Autor: Desconhecido
Ano de Publicação: 0
Situação: Disponível
-------------------------
Título: Dom Casmurro
Autor: Machado de Assis
Ano de Publicação: 1899
Situação: Emprestado
-------------------------

ALUNO RESPONSÁVEL PELO EMPRÉSTIMO
Nome: Ana Paula Goulart
Matrícula: 2026001
Turma: Informática
```

---

## 📚 Tecnologias Utilizadas

* C#
* .NET (Console Application)

---

## ✍️ Autor

Projeto desenvolvido para fins de aprendizado em programação.
