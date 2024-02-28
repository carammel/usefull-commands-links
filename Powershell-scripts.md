#### Rename Path
  - Rename-Item -Path $(build.artifactstagingdirectory)\_PublishedWebsites\$(Build.Repository.Name)\abc.config -NewName "web.config"

#### Azure Devops authorization inside pipeline 
$myt = @{Authorization = 'Basic ' + [Convert]::ToBase64String([Text.Encoding]::ASCII.GetBytes(":$($token)")) }
