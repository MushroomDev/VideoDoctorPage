# VideoDoctorPage

VideoDoctor 官方宣传与技术支持站点（GitHub Pages），提供 **中文** 与 **English** 双语页面。

## 本地预览

```bash
cd /Volumes/Samsung512/Document/My/VideoDoctor/VideoDoctorPage
python3 -m http.server 8080
```

浏览器打开：

- 中文首页：http://localhost:8080/
- 英文首页：http://localhost:8080/en/
- 技术支持：http://localhost:8080/support.html
- 隐私说明：http://localhost:8080/privacy.html

## 发布到 GitHub Pages

仓库：`MushroomDev/VideoDoctorPage`

1. 推送到 `main`
2. GitHub → Settings → Pages → Source 选 **Deploy from a branch**
3. Branch 选 `main` / `/ (root)`
4. 站点地址通常为：  
   `https://mushroomdev.github.io/VideoDoctorPage/`

## 已配置

| 项目 | 值 |
|------|-----|
| App Store | `https://apps.apple.com/app/id6800692831` |
| 技术支持邮箱 | `swain6@163.com` |

若改用自定义域名，同步修改各页 `<link rel="canonical">` 与 `hreflang`。

## 结构

```
index.html / support.html / privacy.html   # 中文
en/…                                       # English
assets/css/site.css
assets/js/site.js
assets/img/…
```
