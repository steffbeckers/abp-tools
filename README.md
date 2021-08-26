# ABP.io dev tools

## SteffBeckers.Abp.Cli

- Localization
  - Scan folder, search for localization keys
  - Export localizations to formats
    - Excel
  - Import localizations from formats to JSON
    - Excel

### Install

```powershell
dotnet tool install -g SteffBeckers.Abp.Cli
```

### Update

```powershell
dotnet tool update -g SteffBeckers.Abp.Cli
```

### Release to NuGet.org

```powershell
dotnet pack -c Release
```

```powershell
dotnet nuget push SteffBeckers.Abp.Cli.x.x.x.nupkg --api-key <API key here> --source https://api.nuget.org/v3/index.json
```

