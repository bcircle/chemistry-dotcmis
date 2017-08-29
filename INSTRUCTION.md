## Instruction

```bash
# restore
nuget restore

# build
msbuild DotCmis/DotCMIS.csproj /target:Rebuild

# pack
nuget pack DotCmis/OpenDataSpace.DotCMIS.nuspec -OutputDirectory ~/.local-nuget
```