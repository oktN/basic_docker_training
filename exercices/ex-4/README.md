# EXERCICE 4

1. Build the dotnet core app (src dir) in a multi stage dockerfile
2. Hint:
    - SDK/Build image: microsoft/dotnet:sdk 
    - Runtime image: microsoft/dotnet:aspnetcore-runtime
    - dotnet restore 
    - dotnet publish -c Release -o out 
    - dotnet dotnet-core-hello-world.dll
