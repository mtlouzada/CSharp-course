# Aula 1 by CFB Cursos 🧑🏻‍💻

### Configurando o ambiente

#### Downloads necessários:

[.NET Core](https://dotnet.microsoft.com/pt-br/download)

[.NET Framework](https://dotnet.microsoft.com/pt-br/download/dotnet-framework)

#### Extensões VS Code:

- C# Kit dev tools

#### Adicioar o compilador csc(Compilador C# Pu) ao PATH do sistema:

[Vídeo Tutorial](https://www.youtube.com/watch?v=JxUd8P3_1B8)

[Vídeo Tutorial 2](https://www.youtube.com/watch?v=dVzJ3bx68FA&list=PLx4x_zx8csUglgKTmgfVFEhWWBQCasNGi)

**OBS**: *Na versão do windows 11 não é necessário reiniciar o computador após configurar o path, mas em versões mais antigas talvez seja necessário.*

---

### Caso queria optar por usar o .NET para compilar os arquivo

O comando ```dotnet new console -o MeuProjeto``` cria um projeto estruturado com suporte ao .NET Core/.NET 5+.

#### 📌 Como usar dotnet new console

```bash
dotnet new console -o MeuPrograma
cd MeuPrograma
dotnet run
```

Isso cria uma estrutura de diretórios com:

```bash
MeuProjeto/
├── MeuProjeto.csproj  # Arquivo de configuração do projeto
├── Program.cs         # Código-fonte
├── obj/               # Arquivos temporários de compilação
└── bin/               # Arquivos compilados (executável)

```

---

### Resumo

Nessa aula, aprendi a configurar o ambiente para o desenvolvimento utilizando C# (CSharp) e .NET. Entendi a diferença entre utilizar um compilador C# puro, como o csc, e criar um projeto com dotnet new console.