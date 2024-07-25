# APICatalogo

# Configurar VSCode (Caso utilize)

    Plugin VSCode: c# dev kit

# Pacotes NuGet instalados

    Microsoft.AspNetCore.OpenApi
    Microsoft.EntityFrameworkCore.Design
    Pomelo.EntityFrameworkCore.MySql
    Swashbuckle.AspNetCore

# Connection Strings

    https://www.connectionstrings.com/mysql/

# Migrations

    Verifique se a ferramenta EF Core Tools está instalada
        Utilize o comando dotnet ef
    Crie um script de migration
        Utilize o comando dotnet ef migrations add 'nome'
    Caso queira remover um script de migration criado
        Utilize o comando dotnet ef migrations remove 'nome'
    Para gerar o banco de dados e as tabelas com base no script
        Utilize o comando dotnet ef database update
    É possível utilizar o Package Manager Console do próprio Visual Studio
        Para isso:
            Instale o pacote NuGet Microsoft.EntityFrameworkCore.Tools
            Altere os comandos.
                Criar: add-migration 'nome'
                Remover: remove-migration 'nome'
                Gerar banco de dados: update-database

# Configurar o ambiente

## Instalar o EntityFrameworkCore

    Abrir o prompt de comando e digitar o comando "dotnet ef"
    	Se não exibir erro, está instalado. Caso esteja instalado, atualizar a versão utilizando o comando "dotnet tool update --global dotnet-ef"
    	Se exibir erro, deve instalar utilizando o comando "dotnet tool install --global dotnet-ef"
