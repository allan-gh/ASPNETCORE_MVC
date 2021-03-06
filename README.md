# ASPNETCORE_MVC
projeto elaborado a partir do padrão arquitetural MVC. A aplicação web consiste no cadastro e consulta de filmes , possuindo assim persistência de dados

<p align="center">
 <a href="#Objetivo">Objetivo</a> •
 <a href="#Tecnologias">Tecnologias</a> • 
 <a href="#Extensões">Extensões</a> • 
 <a href="#Pacotes">Pacotes Nuget</a> • 
 
</p>


## Objetivo
O objetivo do projeto é criar uma aplicação web baseada no padrão arquitetural Mvc (Model-View-Controller). O projeto cumpre o padrão na medida em que foram adicionadas os componentes em cada camada .

A Aplicação permite que o usuário cadastre filmes em uma tabela de filmes , que permanece armazenada num banco de Dados. O usuário pode : 

- cadastrar novos filmes 
- pesquisar os existentes 
- editar 
- ver detalhes 
-  excluir alguns filmes da Tabela.

O projeto foi contruído com base no tutorial disponível no site da Microsoft ---> [Tutorial](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-5.0&tabs=visual-studio)

 Confira os prins de tela da aplicação : [print](https://allan-gh.github.io/ASPNETCORE_MVC/Prints.docx)

## Tecnologias

- Visual Studio Code (1.53.1)
- SDK 5.0.103 [Download sdk](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.200-windows-x64-installer)
- Asp.Net Core

### Extensões
Instale essas extensões no visual studio code
- c# distribuidora microsoft 
Name: C#
Id: ms-dotnettools.csharp
Description: C# for Visual Studio Code (powered by OmniSharp).
Version: 1.23.9
Publisher: Microsoft
VS Marketplace Link: [link](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

- c# extensions
Name: C# Extensions
Id: jchannon.csharpextensions
Description: C# IDE Extensions for VSCode
Version: 1.3.1
Publisher: jchannon
VS Marketplace Link: [link](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)

## Pacotes 
Se você utilizar o visual studio code para realizar este projeto, então precisará instalar os pacotes Nuget.

Abra o Vscode -> Abra o terminal no vs code -> insira os comando abaixo (um por vez) :
```
1. dotnet tool install --global dotnet-ef
2. dotnet tool install --global dotnet-aspnet-codegenerator
3. dotnet add package Microsoft.EntityFrameworkCore.SQLite
4. dotnet add package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore
5. dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
6. dotnet add package Microsoft.EntityFrameworkCore.Design
7. dotnet add package Microsoft.EntityFrameworkCore.SqlServer
8. dotnet add package Microsoft.Extensions.Logging.Debug
```



