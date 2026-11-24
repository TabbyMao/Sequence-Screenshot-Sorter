# Sequence · Screenshot Sorter / 截图排序工具

**English** | [中文](#中文)

A single-page web tool for putting lots of screenshots in order on paper.

**🌐 Open the tool: https://tabbymao.github.io/Sequence-Screenshot-Sorter/**

1. **Add screenshots**: click, drag in, or paste them. Each one gets a fixed number.
2. **Cut sheet**: every screenshot is scaled to the **same text size**, trimmed, put on **white paper** (text keeps its original color; dark-mode text is made dark), and packed onto Letter / A4 / Legal / A5 pages to use as little paper as possible. Each one has a **dashed cut line** and its **number**. Download the PDF and print it.
3. Cut the pieces out and arrange them on your desk.
4. **Sorted**: type the numbers in your order (e.g. `3 1 5 2 4`) to get a sorted PDF with the same text size throughout.

### Privacy
Everything runs in your browser. Screenshots, projects and PDFs are **never uploaded** and are **not part of this repository**. The project is saved only in your own browser (IndexedDB); “Save project file” lets you move it to another device. `.gitignore` blocks PDFs, images and saved project files from being committed.

### Run
Open `index.html` in a browser (it loads jsPDF and Google Fonts from CDNs). Or serve the folder: `python3 -m http.server`.

### Files
- `index.html` — the whole app (HTML + CSS + JS)
- `bg/healing.svg` — background for the Chinese version (Healing)
- `bg/fresh.svg` — hanging leaves for the English version (Fresh)
- `bg/hydrangea-scene.svg` — the hydrangea oil painting, extended with painted heads, leaves and drifting florets
- `bg/hydrangea.webp` — the original hydrangea painting

---

## 中文

把很多截图排好顺序的单页网页工具。

**🌐 打开工具：https://tabbymao.github.io/Sequence-Screenshot-Sorter/**

1. **上传截图**：点击、拖入或粘贴，每张自动编号，编号不变。
2. **剪裁版**：所有截图**统一字号**、自动裁掉空白、换成**白底**（文字保持原色，深色模式的浅色字会变深），用最省纸的方式排在 Letter / A4 / Legal / A5 纸上，每张有**虚线**和**编号**。下载 PDF 打印。
3. 沿虚线剪下来，在桌上排好顺序。
4. **排序版**：按顺序输入编号（如 `3 1 5 2 4`），生成字号一致、排好序的 PDF。

### 隐私
全部在浏览器里运行。截图、项目和 PDF **不会上传**，也**不在这个仓库里**。项目只保存在你自己的浏览器（IndexedDB）中，可用“保存项目文件”带到别的设备。`.gitignore` 会阻止 PDF、图片和项目文件被提交。

### 使用
直接用浏览器打开 `index.html`（需要联网加载 jsPDF 和 Google 字体），或在文件夹里运行 `python3 -m http.server`。
