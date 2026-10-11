# 第三方组件说明

AI 磁盘管家发行版包含 Python/Tcl/Tk 运行时和 Pillow 图像组件，由 PyInstaller 打包。公开可执行程序不改变这些组件的原许可。

| 组件 | 发行版本/说明 | 许可文本 |
| --- | --- | --- |
| CPython | 3.10.11；含 Python 标准库与所附第三方声明 | [Python LICENSE](third_party_licenses/Python-LICENSE.txt) |
| Tcl | 8.6.12 | [Tcl license.terms](third_party_licenses/Tcl-license.terms) |
| Tk | 8.6 系列，许可从实际 EXE 包提取 | [Tk license.terms](third_party_licenses/Tk-license.terms) |
| Pillow | 12.3.0；MIT-CMU 及随 wheel 附带的组件声明 | [Pillow LICENSE](third_party_licenses/Pillow-LICENSE.txt) |
| PyInstaller | 6.22.3 打包工具；原工具采用 GPL 附打包例外等许可 | [官方打包例外说明](https://pyinstaller.org/en/stable/license.html) |

Python 和 Pillow 许可文本来自本机实际打包环境；Tk 许可取自本次发布 EXE。Tcl 许可来自其 [8.6.12 官方源码](https://github.com/tcltk/tcl/blob/core-8-6-12/license.terms)。PyInstaller 官方说明允许按应用自身许可发行打包结果，依赖组件仍遵守各自许可。

完整便携压缩包包含本说明及许可文本。单独 EXE 下载者也可在发行仓库获取这些随附声明。本项目对第三方组件不授予额外权利，不以组件原作者名称作产品背书。

