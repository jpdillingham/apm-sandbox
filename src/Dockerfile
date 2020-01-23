FROM mcr.microsoft.com/dotnet/core/aspnet:3.0
ENV ASPNETCORE_URLS=http://+:5000
COPY bin/Debug/netcoreapp3.0/publish app/
ENTRYPOINT ["dotnet", "app/dotnetAPM.dll"]