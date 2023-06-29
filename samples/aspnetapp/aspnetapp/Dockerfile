# final stage/image
FROM mcr.microsoft.com/dotnet/aspnet:7.0
WORKDIR /app
COPY /bin/Debug/net7.0/publish/* /app/
ENTRYPOINT ["dotnet", "aspnetapp.dll"]
EXPOSE 80
