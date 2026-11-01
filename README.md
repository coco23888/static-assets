# static-assets

通用静态资源库。存放各项目的 JS / CSS / 字体 / 图片等静态资源，配合 [jsDelivr](https://www.jsdelivr.com/) CDN 加速加载。

## 目录结构

```
static-assets/
├── farm/     # 农场计算器（QQFarmCalc）相关运行时
├── roco/     # 洛克王国相关运行时
└── common/   # 跨项目通用库
```

## 加速链接用法

仓库里的任意文件都可通过 jsDelivr 访问，格式：

```
https://cdn.jsdelivr.net/gh/coco23888/static-assets@main/<路径>
```

示例：

```
https://cdn.jsdelivr.net/gh/coco23888/static-assets@main/farm/spine-webgl-3.8.js
```

## 已有资源

| 路径 | 说明 | 大小 |
| --- | --- | --- |
| `farm/spine-webgl-3.8.js` | Spine 骨骼动画 WebGL 运行时（3.8 版） | 416KB |

## 注意

- 只放**可公开的运行时代码/资源**，不放游戏逆向产物（骨骼、贴图、配置表等）。
- 大文件建议先压成有损格式再上传。
