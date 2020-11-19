This is so I don't forget how to symlink previous dotnet versions in Linux

1. Create the old version folder inside shared/Microsoft.NETCore.App/{oldVersion} of current version
2. Run the following commands in the Microsoft.NETCore.App and Microsoft.AspNetCore.App folder of current version

```
ln -s /{pathToOldDotNet}/shared/Microsoft.NETCore.App/{oldVersion}/* ./{oldVersion}/
ln -s /{pathToOldDotNet}/shared/Microsoft.AspNetCore.App/{oldVersion}/* ./{oldVersion}/
```
