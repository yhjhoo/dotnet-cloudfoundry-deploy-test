dotnet publish -r linux-x64 -c Release

cf push dotnet-hj -p bin/Release/netcoreapp2.1/linux-x64/publish/
# dotnet-cloudfoundry-deploy-test
