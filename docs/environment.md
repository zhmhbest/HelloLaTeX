<link rel="stylesheet" href="https://zhmhbest.gitee.io/hellomathematics/style/index.css">
<script src="https://zhmhbest.gitee.io/hellomathematics/style/index.js"></script>

# [配置环境](./index.html)

## Texlive

- [Documentation](https://tug.org/texlive/doc.html)
- [Overleaf, Online LaTeX Editor](https://www.overleaf.com/)
- [Downlaod Texlive](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/)

### 安装

![texlive_files](.//images/texlive_files.png)

以管理员身份运行`install-tl-windows.bat`。
安装完成后，确保`${INSTALL_LOCATION}\texlive\${VERSION_YEAR}\bin\win32`在环境变量中。

### 仓库

```batch
tlshell
REM 选项 -> Repositories
```

![texlive_repository](.//images/texlive_repository.png)

### 更新

```batch
REM 查看可用更新
tlmgr update --list

REM 更新全部
tlmgr update --self --all
```

### 文档

查看ctex文档

```batch
texdoc ctex
```

查看lshort文档

```batch
texdoc lshort-zh
```

查看graphicx文档

```batch
texdoc graphicx
```

查看svg文档

```batch
texdoc svg
```

其它第三方文档

- [LaTeX入门（刘海洋）](./pdf/LaTeX入门（刘海洋）.pdf)

## VSCode

- [Downlaod VSCode](https://code.visualstudio.com/Download)
- [Plugin: LaTex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

### 操作

- 新建`*.tex`
- `Ctrl + Alt + B`: 编译为PDF
- `Ctrl + Alt + V`: 预览PDF
- `Ctrl + Alt + J`: 代码对于PDF位置
- `Ctrl + Click on PDF`: 跳转到PDF内容对应代码位置
