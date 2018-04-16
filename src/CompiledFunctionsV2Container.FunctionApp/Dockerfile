# Gets the nightly build of Azure Functions runtime
FROM microsoft/azure-functions-dotnet-core2.0:dev-jessie

ENV AzureWebJobsScriptRoot=/home/site/wwwroot

COPY ./bin/Debug/netstandard2.0 /home/site/wwwroot
