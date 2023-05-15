This repo demonstrates a solution-level publish of two containerized applications using a new target called `Containerize`.

To demonstrate:

```shell
dotnet build /t:Containerize && docker-compose up
```

This will build containers for both projects for all RuntimeIdentifiers that they explicitly target, and then run the linux-x64 versions of those in docker-compose.