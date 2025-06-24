
# 这是一个切换镜像源的库

```html

          _____                    _____                    _____          
         /\    \                  /\    \                  /\    \         
        /::\____\                /::\    \                /::\    \        
       /::::|   |               /::::\    \              /::::\    \       
      /:::::|   |              /::::::\    \            /::::::\    \      
     /::::::|   |             /:::/\:::\    \          /:::/\:::\    \     
    /:::/|::|   |            /:::/__\:::\    \        /:::/__\:::\    \    
   /:::/ |::|   |           /::::\   \:::\    \       \:::\   \:::\    \   
  /:::/  |::|   | _____    /::::::\   \:::\    \    ___\:::\   \:::\    \  
 /:::/   |::|   |/\    \  /:::/\:::\   \:::\____\  /\   \:::\   \:::\    \ 
/:: /    |::|   /::\____\/:::/  \:::\   \:::|    |/::\   \:::\   \:::\____\
\::/    /|::|  /:::/    /\::/   |::::\  /:::|____|\:::\   \:::\   \::/    /
 \/____/ |::| /:::/    /  \/____|:::::\/:::/    /  \:::\   \:::\   \/____/ 
         |::|/:::/    /         |:::::::::/    /    \:::\   \:::\    \     
         |::::::/    /          |::|\::::/    /      \:::\   \:::\____\    
         |:::::/    /           |::| \::/____/        \:::\  /:::/    /    
         |::::/    /            |::|  ~|               \:::\/:::/    /     
         /:::/    /             |::|   |                \::::::/    /      
        /:::/    /              \::|   |                 \::::/    /       
        \::/    /                \:|   |                  \::/    /        
         \/____/                  \|___|                   \/____/         
                             
```


安装建议加上-g

npm i nrm-xiecr -g
##### nrs ls 查看目前源

* npm-------  https://registry.npmjs.org/
  
  yarn------  https://registry.yarnpkg.com/

  tencent---  https://mirrors.cloud.tencent.com/npm/

  cnpm------  https://r.cnpmjs.org/

  taobao----  https://registry.npmmirror.com/
  
  npmMirror-  https://skimdb.npmjs.com/registry/

##### nrs use 切换源

选择你要切换的源

##### nrs current 查看当前源

当前源: npm

##### nrs add 添加源

1.输入添加的名称
2.输入源地址

##### nrs ping 测试源

? 请选择镜像 cnpm
响应时长: 1635ms

##### nrs delete 删除自定义源

add添加的源都可以删除


##### nrs rename 重命名

自定义添加的源都可以进行重新命名

##### nrs edit 编辑自定义镜像地址

# 用法 Usage

Usage: nrs [options] [command]

Options:

  -V, --version   output the version number

  -h, --help      display help for command


Commands:
  ls              查看镜像

  use             请选择镜像

  current         查看当前源

  ping            测试镜像地址速度

  add             自定义镜像

  delete          删除自定义的源

  rename          重命名

  edit            编辑自定义镜像地址

  help [command]  display help for command
