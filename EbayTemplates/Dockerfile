FROM microsoft/aspnetcore:1.1.1
WORKDIR /app
COPY bin/Debug/netcoreapp1.1/publish /app
ENV ASPNETCORE_URLS http://*:59241
EXPOSE 59241
 
ENTRYPOINT /bin/bash -c "dotnet EbayTemplates.dll"
