#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.
  # syntax=docker/dockerfile:1
  FROM mcr.microsoft.com/dotnet/aspnet:5.0
  COPY bin/Release/netcoreapp3.1/publish/ App/
  WORKDIR /App
  ENTRYPOINT ["dotnet", "aspnetapp.dll"]

