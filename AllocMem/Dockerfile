FROM image-registry.openshift-image-registry.svc:5000/openshift/dotnet:6.0
COPY bin/Release/net6.0/ App/
WORKDIR /App
ENTRYPOINT ["dotnet", "AllocMem.dll"]
