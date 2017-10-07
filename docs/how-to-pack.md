How to Pack
===========

To pack the TaskBuilder.fs, use the following command:

```console
$ dotnet pack -c Release ./TaskBuilder.fs.fsproj
$ dotnet nuget push bin/Release/TaskBuilder.fs.<version>.nupkg -k <NuGet API key> -s https://www.nuget.org/api/v2/package
```
