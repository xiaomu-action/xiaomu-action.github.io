# xiaomu-action.github.io

这是佐佐的个人主页，风格参考了浪漫的星空/宇航员主题。

## 预览地址

发布后可访问：

```
https://xiaomu-action.github.io/
```

## 如何发布到 GitHub Pages

1. 在 GitHub 上创建一个仓库，仓库名必须是：

   ```
   xiaomu-action.github.io
   ```

2. 把本目录下的 `index.html` 上传到仓库根目录。

3. 打开仓库 **Settings -> Pages**，确认：
   - **Source** 选择 `Deploy from a branch`
   - **Branch** 选择 `main`
   - 目录选择 `/ (root)`
   - 点击 **Save**

4. 等待 2-5 分钟后，访问 `https://xiaomu-action.github.io/` 即可看到页面。

## 自定义内容

直接编辑 `index.html`：

- 修改标题、副标题、语录、位置、社交链接
- 纪念日时间：在 `<script>` 里修改 `startDate`
- 头像：把 `.avatar-placeholder` 替换成 `<img src="你的头像.jpg" class="avatar" alt="头像">`
- 专辑封面：把 `.album-cover` 里的占位 div 替换成 `<img src="封面.jpg">`
- 要添加真实音乐播放，需要引入音频文件并绑定播放逻辑

## 本地预览

直接用浏览器打开 `index.html` 即可预览。
