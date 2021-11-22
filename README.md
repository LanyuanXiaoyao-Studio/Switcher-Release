# Switcher (Input Switcher) 输入法布局切换工具
此工具旨在提供切换输入法布局的简便操作, 值得注意的是, 工具切换的是系统输入法布局, 并非具体某一个输入法的中英文输入模式, 通过将输入法布局切换为英语, 可以达到将输入法切换为英文输入的模式

> 此工具为 uTools 插件「书签与历史记录」设计, 但亦可以独立使用, 对插件感兴趣, 可以访问 [LanyuanXiaoyao-Studio/utools-recent-projects](https://github.com/LanyuanXiaoyao-Studio/utools-recent-projects) 查看

**目前仅支持 Windows 和 macOS, Linux 暂不支持**

## 使用方式
```
Input Switcher 1.0.38

  -l  --list     列出所有已激活的布局编号
  -s  --set      设置输入法布局为指定的布局编号
  -v  --version  显示当前工具的版本
  -h  --help     显示帮助信息
```

## 例子
### `--list`
```bash
C:\Users\Administrator\Desktop>.\build.release.input-switcher-1.0.39_windows_x64.exe -l
00000804
00000409
```

### `--set`
*返回值为切换前布局编号*
```bash
C:\Users\Administrator\Desktop>.\build.release.input-switcher-1.0.39_windows_x64.exe -s 00000409
00000804
```

### `--version`
```bash
C:\Users\Administrator\Desktop>.\build.release.input-switcher-1.0.39_windows_x64.exe -v
1.0.38
```
