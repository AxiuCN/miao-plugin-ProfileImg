# miao-plugin-ProfileImg
这个图库是 Yunzai 框架下的 miao-plugin 面板图资源，涵盖了**原神&星铁**的面板图资源

## 安装方式
建议使用**面板图图库管理器**安装管理。  
在 Yunzai 根目录执行命令安装（二选一）

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


如果要安装屏蔽仓库，在 `profile` 目录下继续执行（二选一）
> Github
```bash
git submodule add https://github.com/AxiuCN/miao-plugin-ProfileImg-Blocked.git blocked-character
```

> Gitee
```bash
git submodule add https://gitee.com/AxiuCN/miao-plugin-ProfileImg-Blocked.git blocked-character
```

## 面板图图库管理器
一个用于管理喵喵插件角色面板图库（主图库/屏蔽图库）的面板图图库管理器，支持状态查看、更新、安装、屏蔽/启用面板图等功能  
https://github.com/AxiuCN/ProfileImg-Plugin/

### 安装
在 Yunzai 根目录执行命令安装

> Github
```bash 
git clone --depth=1 https://github.com/AxiuCN/ProfileImg-Plugin ./plugins/ProfileImg-Plugin/
```

> Gitee
```bash 
git clone --depth=1 https://gitee.com/AxiuCN/ProfileImg-Plugin ./plugins/ProfileImg-Plugin/
```

## 屏蔽仓库
储存暂时被主图库屏蔽的 miao-plugin 面板图资源  
https://github.com/AxiuCN/miao-plugin-ProfileImg-Blocked/

## 免责声明
* **请勿将此模板图库用于任何以盈利为目的的场景.** 
* **图片与其他素材均来自于网络，图片资源严禁用于任何商业用途。如有侵权请联系删除**
