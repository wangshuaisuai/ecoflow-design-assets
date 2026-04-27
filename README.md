# EcoFlow Design Assets

设计资产云端仓库，通过 jsDelivr CDN 分发。

## 目录结构

```
├── tokens/
│   ├── tokens.json    ← Figma Variables 原始数据
│   └── tokens.css     ← CSS Variables
├── icons/
│   ├── svg/           ← SVG 图标
│   └── png/           ← 位图素材 @2x
```

## 使用方式

### Design Token
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/wangshuaisuai/ecoflow-design-assets@main/tokens/tokens.css">
```

### SVG 图标
```html
<img src="https://cdn.jsdelivr.net/gh/wangshuaisuai/ecoflow-design-assets@main/icons/svg/图标名.svg">
```

### 位图素材
```html
<img src="https://cdn.jsdelivr.net/gh/wangshuaisuai/ecoflow-design-assets@main/icons/png/素材名@2x.png">
```
