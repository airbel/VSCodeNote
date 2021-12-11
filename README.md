### VSCode使用筆記
每次按F5 都只能跑指定檔案，不能開A檔案，就執行A檔案!
修改方式 打開 launch.Json 
修改
```
"program":"${fileDirname}/${fileBasenameNoExtension}"
```
