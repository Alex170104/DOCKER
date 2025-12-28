FROM mcr.microsoft.com/dotnet/sdk:7.0

WORKDIR /app

COPY . .

RUN dotnet restore
RUN dotnet build -c Release

CMD ["dotnet", "bin/Release/net7.0/Worker.dll"]