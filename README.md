```shell
git clone https://github.com/trail-b1az3r/stuff.git ; cd stuff ; Get-ChildItem -Recurse -Filter *.zip | ForEach-Object { Expand-Archive -Path $_.FullName -DestinationPath $_.DirectoryName -Force }
```
