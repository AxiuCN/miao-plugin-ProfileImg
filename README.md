# miao-plugin-ProfileImg
这个图库是 Yunzai 框架下的 miao-plugin 面板图资源，涵盖了**原神&星铁**的面板图资源

## 安装方式
在Yunzai根目录执行命令安装（二选一）

> Github
```bash 
cd plugins/miao-plugin/resources/profile
git init --initial-branch=main
git remote add origin https://github.com/AxiuCN/miao-plugin-ProfileImg.git
git fetch origin main --depth 1
git reset --hard origin/main
```

> Gitee
```bash 
cd plugins/miao-plugin/resources/profile
git init --initial-branch=main
git remote add origin https://gitee.com/AxiuCN/miao-plugin-ProfileImg.git
git fetch origin main --depth 1
git reset --hard origin/main
```

如果要安装屏蔽仓库，在 `profile` 目录下继续执行
> Github
```bash
git submodule add https://github.com/AxiuCN/miao-plugin-ProfileImg-Blocked.git blocked-character
```

## 面板图图库管理器
用于管理本图库的单文件插件，支持查看状态、自动/手动更新等功能

### 安装

在 Yunzai 根目录下执行以下命令：
```bash
curl -o plugins/example/面板图图库管理器.js "https://raw.githubusercontent.com/AxiuCN/Yunzai_JS_Plugins/main/%E9%9D%A2%E6%9D%BF%E5%9B%BE%E5%9B%BE%E5%BA%93%E7%AE%A1%E7%90%86%E5%99%A8.js"
```

下载失败可尝试：JsDelivr CDN：
```bash
curl -o plugins/example/面板图图库管理器.js "https://cdn.jsdelivr.net/gh/AxiuCN/Yunzai_JS_Plugins@main/%E9%9D%A2%E6%9D%BF%E5%9B%BE%E5%9B%BE%E5%BA%93%E7%AE%A1%E7%90%86%E5%99%A8.js"
```

## 屏蔽仓库
储存暂时被主图库屏蔽的 miao-plugin 面板图资源  
https://github.com/AxiuCN/miao-plugin-ProfileImg-Blocked/

## 免责声明
* **请勿将此模板图库用于任何以盈利为目的的场景.** 
* **图片与其他素材均来自于网络，图片资源严禁用于任何商业用途。如有侵权请联系删除**
