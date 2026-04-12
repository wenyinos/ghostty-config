# Ghostty Config

A beautifully commented Ghostty configuration file with bilingual (Chinese/English) annotations.



## Features / 特性

- **Theme**: TokyoNight Moon 主题
- **Font**: Cascadia Code 字体
- **Transparency**: 背景透明 + 模糊效果
- **Comments**: 每个配置项都有详细的中英文说明
- **Shader**: 可选 CRT 复古显示器效果

## Installation / 安装

### Prerequisites / 前置要求

Install Cascadia Code font

安装 Cascadia Code 字体

### Steps / 步骤

Clone the repository, or download the theme of your choice:

克隆仓库，或下载你需要的主题：

We use default Linux config directory as our storage location here.

这里使用 Linux 默认配置目录作为存储位置。

clean old config file (optional)

清理旧配置文件（可选）

```shell
rm -rf ~/.config/ghostty

git clone https://github.com/wenyinos/ghostty-config ~/.config/ghostty
```

## Configuration Structure / 配置结构

| Section / 部分 | Description / 描述 |
|---|---|
| Basic Settings / 基本设置 | Title, shell integration, clipboard |
| Font & Title Bar / 字体与标题栏 | Title font, subtitle content |
| Background & Transparency / 背景与透明度 | Opacity, blur, unfocused windows |
| Window Size & Style / 窗口尺寸与样式 | Dimensions, decoration type |
| Theme & Colors / 主题与颜色 | Theme, contrast, colors |
| Palette / 调色板 | 16-color terminal palette |
| Font Settings / 字体设置 | Size, family, styles |
| Mouse Behavior / 鼠标行为 | Hide cursor while typing |
| GTK Settings / GTK 设置 | Linux GTK integration |
| macOS Settings / macOS 设置 | Fullscreen, title bar |
| Update Settings / 更新设置 | Auto-update channel |
| Shaders / 着色器 | CRT retro effect (optional) |

## Usage / 使用

After installation, restart Ghostty to apply the configuration.

安装后，重启 Ghostty 以应用配置。

To enable the CRT shader effect, uncomment the following line in the config file:

要启用 CRT 着色器效果，在配置文件中取消注释以下行：

```
#custom-shader = shaders/crt.glsl
```
