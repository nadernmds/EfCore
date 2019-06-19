dotnet new react
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Proxies
dotnet ef dbcontext scaffold "connection" Microsoft.EntityFrameworkCore.SqlServer -o Models
