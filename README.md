<!--
 * @Description: 
 * @Author: 唐健峰
 * @Date: 2023-10-17 18:55:21
 * @LastEditors: ${author}
 * @LastEditTime: 2023-10-17 19:28:33
-->
## 添加未注册的包
### 如果包不在注册表中，可以通过指定 Git 存储库的 URL 来添加它：
```
(@v1.8) pkg> add https://github.com/fredrikekre/ImportMacros.jl
     Cloning git-repo `https://github.com/fredrikekre/ImportMacros.jl`
   Resolving package versions...
    Updating `~/.julia/environments/v1.8/Project.toml`
  [92a963f6] + ImportMacros v1.0.0 `https://github.com/fredrikekre/ImportMacros.jl#master`
    Updating `~/environments/v1.9/Manifest.toml`
  [92a963f6] + ImportMacros v1.0.0 `https://github.com/fredrikekre/ImportMacros.jl#master`
```