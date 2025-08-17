### ✅ Create a Console Project

```bash
dotnet new console -n YourProjectName.Console
```

### ✅ Add the Console App to Your Solution

```bash
dotnet sln add YourProjectName.Console/YourProjectName.Console.csproj
```

### ✅ Run and Test

```bash
dotnet run --project YourProjectName.Console
```

### ✅ Remove the Old WPF Project

```bash
dotnet sln remove YourProjectName.App/YourProjectName.App.csproj
```

### ✅ Create dll library package and upload to nuget.org

```bash
dotnet pack -c Release
dotnet nuget push bin/Release/Potato.NET.SQLite.1.0.0.nupkg --api-key xxxxxxxxxxxxxxxxxxxxxxxx --source https://api.nuget.org/v3/index.json

```
