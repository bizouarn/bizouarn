# Nuget
[[_TOC_]]
## Création d'un package Nuget
### Convertir le projet en nuget  
https://docs.microsoft.com/fr-fr/nuget/consume-packages/migrate-packages-config-to-package-reference  

### Générer le fichier .nuspec  
``` batch
nuget spec <assembly-name>.dll  
```
### Compléter le fichier .nuspec  

### Générer le fichier .nupkg  
``` batch
nuget pack
```
### pousser le packages sur gitlab 
``` batch
nuget source Add -Name "HERAKLES" -Source "https://gitlab.com/api/v4/groups/`GroupID`/-/packages/nuget/index.json" -UserName `UserName` -Password `SECRET SSH KEY`  
nuget source Add -Name "Projet" -Source "https://gitlab.com/api/v4/projects/`ProjectID`/packages/nuget/index.json" -UserName `UserName` -Password `SECRET SSH KEY`  

nuget push HeraklesFiltrage.0.0.1.nupkg -src "https://gitlab.com/api/v4/groups/`GroupID`/-/packages/nuget/index.json"  
nuget push HeraklesFiltrage.0.0.1.nupkg -src "https://gitlab.com/api/v4/groups/`GroupID`/-/packages/nuget/index.json"
```
