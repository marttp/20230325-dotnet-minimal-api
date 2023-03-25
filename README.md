# Learn .NET 6 Minimal API

Learn from [This](https://github.com/binarythistle/S05E03---Minimal-APIs/tree/main)

## Command

```bash
dotnet restore
```

```bash
dotnet user-secrets init
dotnet user-secrets set "UserId" "sa"
dotnet user-secrets set "Password" "p@55w0rd"
```

### EF migration

```bash
dotnet tool install --global dotnet-ef
dotnet ef migrations add initialmigration
dotnet ef database update
```
