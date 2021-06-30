FROM microsoft/aspnetcore:2.1.0-preview1-bionic
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "PartsUnlimitedWebsite.dll"]
