
## 鲁虺LIVP转换器

一个轻量级、隐私优先的在线工具，用于处理iPhone实况照片(LIVP格式)的转换与提取。一个免费的将iPhone的实况照片（LIVP格式）转换为JPG格式的工具。可以通过简单的拖放操作，将LIVP文件上传到网站进行批量转换。不仅支持将LIVP文件转换为JPG，还可以提取HEIC图片和MOV视频。

关于LIVP转换器 LIVP转换器是一款专业的iPhone实况照片在线处理工具，帮助用户轻松处理LIVP文件。 .livp 文件是苹果 iPhone 拍摄的 live 图格式，当我们解压缩 .livp，可以发现 .livp 文件实际上是由一个 jpeg / heic 和 mov 组成的，本工具就是帮您简单快捷地将 .livp 文件中的 jpeg / heic 提取出来。

# 故事

 制作这个工具的起因是在工作中有这方面的需求，需要批量从 .livp 文件中提取 jpeg。这是一个很小众的需求，早期在互联网上并没有找到合适的解决方案，在 GitHub 上也只有通过命令行执行的方案，在考虑了多种方式后，我想到可以利用 HTML 技术来实现这一需求。于是，这个简单的小工具就诞生了。

# 使用方法

前往 LivpToJpeg 工具网页即可使用； 下载本仓库的文件到本地，使用任意浏览器打开 index.html 文件即可； 拖拽 .livp 文件到方框内，网页会自动进行提取，稍等片刻，就会显示缩略图。您可以通过「点击缩略图」进行单个图片的下载，也可点击「下载全部图片」按钮进行批量下载。

# 注意

由于代码是本地运行的，所以通过以上两种不同的方式打开网页，「拖拽文件至网页」和「下载文件至本地」的操作都不会消耗流量，也不会上传您的图片至云端服务器，确保不会侵犯您的隐私，如您仍感到不放心，可以断网使用本工具，或检查源码确认安全。



![LIVP转换器界面](http://livp.luhui.net/livpscreenshot1.jpg)
![LIVP转换器界面](http://livp.luhui.net/livpscreenshot2.jpg)
![LIVP转换器界面](http://livp.luhui.net/livpscreenshot3.jpg)
![LIVP转换器界面](http://livp.luhui.net/livpscreenshot4.jpg)



*界面示意图：简洁直观的操作界面，支持拖放操作*

## 🌟 功能特点

- **格式转换**：将LIVP文件转换为JPG格式
- **内容提取**：提取LIVP中的原始HEIC图片和MOV动态视频
- **批量处理**：支持多文件同时上传与处理
- **隐私保护**：所有文件处理均在浏览器本地完成，不会上传至服务器
- **离线可用**：下载后可离线使用，无需网络连接
- **多语言支持**：提供中英日韩俄西等多种语言界面
- **PWA支持**：可安装为桌面/移动应用，提升使用体验
- **完全免费**：无广告、无付费功能、无需注册

## 🌐 在线使用

直接访问官方网站：[https://livp.luhui.net](https://livp.luhui.net)

## 📱 使用方法

1. **上传文件**：
   - 点击上传区域选择LIVP文件
   - 或直接将LIVP文件拖拽至网页指定区域

2. **处理文件**：
   - 系统自动解析并提取LIVP中的内容
   - 生成图片和视频预览

3. **下载内容**：
   - 点击单个缩略图下载对应文件
   - 点击"下载全部图片"或"下载全部视频"批量获取内容

## 🚀 部署指南

### 本地部署

1. 克隆仓库：
   ```bash
   git clone https://github.com/kugeceo/livp.luhui.net.git
   ```

2. 进入项目目录：
   ```bash
   cd livp.luhui.net
   ```

3. 直接打开`index.html`文件即可使用，无需额外依赖

### 服务器部署

1. 将项目所有文件上传至你的Web服务器（如Nginx、Apache等）的网站根目录
2. 确保服务器正确配置以支持静态文件访问
3. 通过服务器IP或绑定的域名访问

### 一键部署

#### Netlify部署

点击下方按钮一键部署到Netlify：

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kugeceo/livp.luhui.net)

部署步骤：
1. 点击上方按钮，登录Netlify账号
2. 授权Netlify访问你的GitHub账号
3. 选择仓库并配置项目名称（可选）
4. 点击"Deploy site"完成部署
5. 部署完成后，可自定义域名（需在Netlify控制台配置）

#### Vercel部署

点击下方按钮一键部署到Vercel：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kugeceo/livp.luhui.net)

部署步骤：
1. 点击上方按钮，登录Vercel账号
2. 授权Vercel访问你的GitHub账号
3. 系统自动检测项目配置，无需额外设置
4. 点击"Deploy"开始部署
5. 部署完成后可直接使用Vercel提供的域名，或绑定自定义域名

## 🔧 技术栈

- HTML5 + CSS3
- JavaScript (原生)
- Tailwind CSS
- Font Awesome
- PWA 技术

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开Pull Request

## 📜 许可证

本项目采用MIT许可证 - 详见[LICENSE](LICENSE)文件

## 💬 联系与支持

- 项目主页：[https://livp.luhui.net](https://livp.luhui.net)
- 问题反馈：[GitHub Issues](https://github.com/kugeceo/livp.luhui.net/issues)

如果觉得这个工具对你有帮助，欢迎通过项目网站上的捐赠渠道支持开发者！



我们致力于提供简单、高效、安全的文件转换服务，让用户便捷地处理iPhone实况照片。

主要特点 支持批量转换LIVP文件 可以转换为JPG，或者提取原始HEIC图片 支持提取MOV动态视频 完全在浏览器端处理，保护隐私 界面直观、易上手 完全免费，无需注册

使用条款 欢迎使用LIVP转换器。使用我们的服务即表示您同意以下条款。

服务使用 本工具仅供个人使用。您同意不会滥用我们的服务或将其用于非法目的。

知识产权 您上传的文件版权归您所有。我们不会保留或声明任何权利。

免责声明 我们提供"按原样"的服务，不对服务的可用性或结果做出任何保证。

服务变更 我们保留随时修改或终止服务的权利，恕不另行通知。

隐私政策 我们非常重视您的隐私保护。本隐私政策说明了我们如何收集、使用和保护您的信息。

数据处理 所有文件处理都在您的浏览器中完成，我们不会上传或存储您的文件。

信息收集 我们不收集任何个人识别信息。我们可能会收集匿名的使用统计数据，以改进服务质量。

Cookie 使用 我们使用必要的 Cookie 来确保网站正常运行。这些 Cookie 不会收集您的个人信息。





## 捐助打赏作者

手机如何扫码：

![打赏作者](http://flash.luhui.net/images/zhifu.png)

① 保存上面二维码图片　② 打开微信、支付宝、手机qq、“扫一扫”　③ 点击右下脚图标　④ 选择刚才保存的图片

感谢每一位捐赠者，我一直在坚持不懈地努力和创新，不断精心打磨产品，并坚持完全免费，我走过的每一步、开发的每一个功能，离不开那些默默支持我的热心用户，
大家的每一份捐赠和建议，都是我做的更好、走的更远最大的支持和动力！感谢大家，感谢有你，与你相遇好幸运！

您的捐赠将会用于：

①  支付服务器、域名费用。
②  开发更丰富的功能，设计更友好的用户界面。
③  撰写发布更多文章，保证作者的官网一直免费为大家提供服务。



