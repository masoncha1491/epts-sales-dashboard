# EPTS Group Sales Performance Dashboard

这是可直接部署到 GitHub Pages 的正式版本。

## 文件说明

- `index.html`：网站首页
- `sales_dashboard_template.xlsx`：空白 Excel 模板
- `sales_dashboard_sample_filled.xlsx`：示例参考文件
- `.nojekyll`：避免 GitHub Pages 处理静态文件时出现路径问题

## GitHub Pages 部署步骤

1. 在 GitHub 新建一个仓库，例如 `epts-sales-dashboard`
2. 把这个文件夹里的所有文件上传到仓库根目录
3. 打开仓库 `Settings`
4. 进入 `Pages`
5. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. 保存后等待 GitHub Pages 发布
7. 打开生成的网址即可使用

## 使用方式

1. 打开网站
2. 点击 `Choose Excel`
3. 选择你已经填写好的 Excel 文件
4. Dashboard 会在浏览器中直接解析并显示结果

## 说明

- 当前版本不依赖后端
- 数据不会自动保存到网站
- 每次重新打开网页后，需要重新选择 Excel 文件
