封面图生成工具
===

### 依赖
Python3
PIL (Pillow)

### 安装依赖
安装 Python：V3.7 Microsoft

安装 PIL：

```bash
# Windows Powershell 或者 CMD
pip install Pillow
# 如果提示权限不足（[WinError 5] Access is denied），请运行：
pip install Pillow --user
```

### 运行
把图片文件放到 `gallary` 目录，CMD 中运行：

```bash
# 切换到 manifest.py 所在目录：
cd c:
cd desktop
cd manifest
python manifest.py
```

### TODO
shell/batch 自动安装依赖、自动删除过期文件、压缩图片、GitHub API push、release