# 📦 API Mínima com ASP.NET Core (.NET 9)

Este repositório contém uma implementação simples de uma **Web API mínima** utilizando o [ASP.NET Core](https://learn.microsoft.com/aspnet/core) com foco em boas práticas, leveza e desempenho.
O projeto segue o [tutorial oficial da Microsoft](https://learn.microsoft.com/pt-br/aspnet/core/tutorials/min-web-api?view=aspnetcore-9.0&tabs=visual-studio) como referência.

## 🚀 Tecnologias utilizadas

* [.NET 9 (ASP.NET Core)](https://dotnet.microsoft.com/)
* API mínima (Minimal APIs)
* Entity Framework Core (em memória)
* Visual Studio 2022 ou superior

## 📁 Estrutura do projeto

```bash
📦MinimalApi
 ┣ 📄Program.cs        # Arquivo principal com definição dos endpoints
 ┣ 📄Todo.cs           # Modelo da entidade Todo
 ┣ 📄TodoDb.cs         # DbContext da aplicação
```

## 📌 Funcionalidades

A API permite o gerenciamento de tarefas simples (todos):

* ✅ **GET /todos** – Lista todas as tarefas
* ✅ **GET /todos/{id}** – Retorna uma tarefa específica
* ✅ **POST /todos** – Cria uma nova tarefa
* ✅ **PUT /todos/{id}** – Atualiza uma tarefa existente
* ✅ **DELETE /todos/{id}** – Remove uma tarefa

## ▶️ Como executar

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/minimal-api-aspnetcore.git
   cd minimal-api-aspnetcore
   ```

2. **Abra no Visual Studio**:

   * Clique duas vezes no arquivo `.sln` ou abra via `File > Open`.

3. **Execute o projeto**:

   * Pressione `F5` ou clique em **Run**.
   * A API será iniciada e estará disponível em `https://localhost:port/api`.

4. **Testes com Swagger**:

   * Ao iniciar, a interface Swagger será exibida automaticamente.
   * Você pode testar todos os endpoints diretamente pelo navegador.

## 📖 Referência oficial

Este projeto é baseado no guia da Microsoft:

> 📚 [Tutorial: Criar uma API Web minimal com o ASP.NET Core](https://learn.microsoft.com/pt-br/aspnet/core/tutorials/min-web-api?view=aspnetcore-9.0&tabs=visual-studio)

## 🧠 Conceitos abordados

* Minimal API (sem controllers)
* Injeção de dependência com `builder.Services`
* Registro de serviços e contexto em memória
* Tipagem simples e direta com C# moderno
* Endpoint mapping com `MapGet`, `MapPost`, etc.

## 🛠️ Requisitos

* [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
* Visual Studio 2022 ou superior com o workload de ASP.NET

---

Se quiser, posso adaptar o conteúdo com seu nome, GitHub ou contexto específico. Deseja isso?

