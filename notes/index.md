# LaTeX

## Texlive

- [Download](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/)
- [Documentation](https://tug.org/texlive/doc.html)
- [Overleaf, Online LaTeX Editor](https://www.overleaf.com/)

## 安装

以管理员身份运行`install-tl-windows.bat`。
安装完成后，确保`${INSTALL_LOCATION}\texlive\${VERSION_YEAR}\bin\win32`在环境变量中。

### 仓库

```batch
tlshell
```

![](.//images/texlive_repository.png)

### 更新

```batch
REM 查看可用更新
tlmgr update --list

REM 更新全部
tlmgr update --self --all
```

## VSCode

需要`Plugin: LaTex Workshop`

## [数学公式](./formula.html)