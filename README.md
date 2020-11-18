This is so I don't forget how to symlink previous dotnet versions in Linux

1. Create the old version folder inside shared/Microsoft.NETCore.App/{oldVersion} of current version
2. Run the following command in the Microsoft.NETCore.App folder of current version

```ln -s /{pathToOldDotNet}/shared/Microsoft.NETCore.App/{oldVersion}/* ./{oldVersion}/```
