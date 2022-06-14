FROM image-registry.openshift-image-registry.svc:5000/openshift/dotnet:5.0
COPY bin/Release/net5.0/ App/
WORKDIR /App
ENTRYPOINT ["dotnet", "AllocMem.dll"]
