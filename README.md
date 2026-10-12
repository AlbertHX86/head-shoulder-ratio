# Shoulder-to-Head Ratio Tester · 头肩比测试器

[English](#english) · [中文](#中文)

**Try it online / 在线使用:** https://alberthx86.github.io/head-shoulder-ratio/
- English: https://alberthx86.github.io/head-shoulder-ratio/?lang=en
- 中文: https://alberthx86.github.io/head-shoulder-ratio/?lang=zh

---

## English

Take a front-facing photo, place a few points, and see how your shoulder-to-head ratio compares with real measurement data. It's a single-file web page. Nothing to install, and your photo never leaves your browser.

### Features

- **Shoulder-to-head ratio**: shoulder width ÷ head width, compared with ANSUR II, the 2012 US Army anthropometric survey (4,082 men / 1,986 women). You get your percentile and a category from "very narrow" to "very broad", with separate male and female norms.
- **Facial thirds & fifths (三庭五眼)**: a classical Chinese guideline for facial proportions. The ideal is three equal vertical thirds and a face width of five eye widths. You get each ratio and an overall score out of 100.
- **Two ways to add a photo**: take one with the front camera (mirroring optional) or upload one.
- **Works everywhere**: mouse and touch, desktop and phone.
- **Two languages**: switch between English and 中文 in the top-right corner. The page picks your browser's language the first time and remembers your choice.

### How to use

1. Open the link and tap **Start camera**, then allow camera access. You can also choose **Upload photo**. The upload button appears after the camera starts, or if the camera can't be used.
2. Face the camera straight on at eye level, relax your shoulders, and leave some room above your head. Tap **Take photo**.
3. **Shoulder ratio mode** has 4 crosshairs. Press and drag each one into place:
   - **Head left / head right**: the widest part of the head, about temple height, both on one horizontal line.
   - **Left shoulder / right shoulder**: the outermost top point of each shoulder joint (the acromion), both on one horizontal line.
4. The result card below updates as you drag. Switch between **Male norms** and **Female norms** to compare.
5. To measure your face, switch to **Thirds & fifths**. Drag the 10 points:
   - **4 points down the center line of the face:** hairline, between the brows, nose base (the bottom of the nostrils, not the nose tip), and chin.
   - **6 points across the face at eye level, left to right:** face edge, eye outer corner, eye inner corner, inner corner, outer corner, face edge.
   - Keep your forehead visible.
6. Hover over or drag any crosshair to see its name and the lengths of its segments. Tap **Retake** to start over.

### Privacy

Everything is processed locally in your browser. Photos are not uploaded anywhere.

### Run locally

Open `index.html` in a browser. Uploading photos works straight from the file. The camera needs HTTPS or `localhost`; the online version already uses HTTPS.

### Disclaimer

Just for fun. Hair and lens perspective affect the measurements, so treat the results as a rough guide. Thirds & fifths is a traditional aesthetic convention, not a medical standard.

---

## 中文

拍一张正面照，标几个点，看看你的头肩比在真实测量数据里排在哪里。这是一个单文件网页，打开就能用，照片不会离开你的浏览器。

### 功能

- **头肩比**：肩宽 ÷ 头宽，和 ANSUR II（2012 年美军人体测量调查，男 4,082 人 / 女 1,986 人）对比，给出百分位和档位（极窄肩 / 偏窄肩 / 标准肩 / 宽肩 / 超宽肩），可切换男性 / 女性标准。
- **三庭五眼**：传统的面部比例参照（理想：三庭等长、脸宽 = 5 个眼宽），给出每一段的比例和一个百分制分数。
- **两种添加照片的方式**：用前置摄像头拍照（可镜像），或上传本地照片。
- **哪里都能用**：支持鼠标和触屏，电脑、手机都可以。
- **中英双语**：右上角切换中文 / EN。第一次打开时按浏览器语言自动选择，之后会记住你的选择。

### 使用方法

1. 打开链接，点 **开启摄像头**，允许浏览器使用摄像头。也可以点 **上传照片**（摄像头开启后出现；摄像头无法使用时也会出现）。
2. 正对镜头平视，肩膀放松，头顶留出空间，点 **拍照定格**。
3. **头肩比模式**有 4 个十字准星，按住拖到对应位置：
   - **头左端 / 头右端**：头部最宽处（约太阳穴高度），两点在同一水平线。
   - **左肩峰 / 右肩峰**：肩关节外侧最高点（肩峰），两点在同一水平线。
4. 下方结果卡会随拖动实时更新，可以切换 **男性标准 / 女性标准** 对比。
5. 想测脸部，切换到 **三庭五眼**，拖动 10 个点：
   - **面部正中线上 4 个点**：发际线、眉心、鼻底（鼻孔底部，不是鼻尖）、下巴尖。
   - **眼睛高度的水平线上 6 个点**，从左到右：脸缘、眼外角、眼内角、眼内角、眼外角、脸缘。
   - 记得露出额头。
6. 悬停或拖动十字准星时会显示它的名称和对应线段长度。点 **重拍** 可以重新开始。

### 隐私

所有处理都在本地浏览器完成，照片不会上传到任何服务器。

### 本地运行

直接用浏览器打开 `index.html`。上传照片在本地就能用；摄像头需要 HTTPS 或 `localhost` 环境（在线版本已是 HTTPS）。

### 说明

纯娱乐向小工具。照片含头发且镜头有透视，结果仅供参考；三庭五眼是传统审美参照，不是医学标准。
