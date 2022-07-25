Na branch master, antes de rodar o projeto fazer as seguintes configuracoes no terminal:

#1 dotnet add package Microsoft.EntityFrameworkCore -v 5.0.12
#2 dotnet add package Microsoft.EntityFrameworkCore.Relational -v 5.0.12
#3 dotnet add package Microsoft.EntityFrameworkCore.SqlServer -v 5.0.12
#4 dotnet tool install --global dotnet-ef --version 3.0.0
#5 dotnet ef migrations add criacaoBD

Após isso, rodar: dotnet run