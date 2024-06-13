# 杯盏光影阁有限公司网站

欢迎来到杯盏光影阁有限公司的官方网站！我们是全球领先的高品质玻璃杯制造商和供应商。本网站旨在展示我们的产品，提供个性化定制服务，并吸引有才华的人才加入我们的团队。

## 文件结构
```
glassWebexample2/
│
├── _config.yml          # Jekyll配置文件
│
├── _layouts/
│   └── default.html    # 布局模板文件
│
├── index.html          # 主页入口文件
├── product-page.html   # 产品页面，列出产品和价格
├── service-after.html  # 售后服务页面
├── service-recruit.html # 招聘服务页面
│
├── assets/             # 存放静态资源的文件夹
│   ├── CSS/            # 存放CSS样式文件
│   ├── img/            # 存放图片资源
│   ├── js/             # 存放JavaScript脚本文件
│   ├── SCSS/           # 存放SCSS预处理器样式文件
│   └── vendor/         # 存放第三方库文件
│
└── README.md           # 项目说明文件
```



### 功能说明

- **主页** (`index.html`): 提供公司概述、产品目录、团队介绍和联系方式。
- **售后服务** (`service-after.html`): 介绍我们的售后服务政策和客户支持。
- **产品页面** (`product-page.html`): 展示所有产品，包括价格和购买链接。
- **招聘服务** (`service-recruit.html`): 吸引并介绍加入我们团队的机会。
- **配置文件** (`_config.yml`): Jekyll配置文件，用于网站构建和部署。
- **模板文件** (`default.html`): Jekyll布局模板，它定义了网站所有页面的通用结构和样式，包括以下部分：

    - **导航栏**：
        - 包含主页、关于、更多（可能包含子菜单如公司优势、个性化定制、严格的标准、优质的服务、相关服务、主要产品、常见问题、主要成员）和联系方式的链接。

    - **页脚**：
        - 包含公司地址、电话、邮箱和直达链接。

    - **SEO元数据**：
        - 包含页面的标题、描述等SEO相关信息。

    - **通用样式和脚本**：
        - 链接到CSS样式表和JavaScript脚本，这些通常用于整个网站的布局和行为。

    - **内容区域**：
        - 一个或多个yield语句，用于插入页面特定内容（如`index.html`、`product-page.html`等页面的内容）。


### 安装和使用

1. 克隆仓库到本地机器。
2. 安装Jekyll（如果尚未安装）。
3. 在项目根目录下运行`jekyll serve`以启动本地服务器。
4. 访问`https://wang152boom.github.io/glassWebexample2/`查看网站。


### 作者信息
<a href="https://github.com/wang152boom" alt="wang152boom"><img src="https://avatars.githubusercontent.com/u/167402892?v=4" style="width: 64px; height: 64px;"/></a>
<a href="https://github.com/SpikeShaun" alt="SpikeShaun"><img src="https://avatars.githubusercontent.com/u/121989821?v=4" style="width: 64px; height: 64px;"/></a>
<a href="https://github.com/FlashBlank7" alt="FlashBlank7"><img src="https://avatars.githubusercontent.com/u/122159986?v=4" style="width: 64px; height: 64px;"/></a>
<a href="https://github.com/Flora-xyyy" alt="Flora-xyyy"><img src="https://avatars.githubusercontent.com/u/121485747?v=4" style="width: 64px; height: 64px;"/></a>
<a href="https://github.com/KidZwq" alt="KidZwq"><img src="https://avatars.githubusercontent.com/u/128034889?v=4" style="width: 64px; height: 64px;"/></a>
<a href="https://github.com/LiJiaquan1" alt="LiJiaquan1"><img src="https://avatars.githubusercontent.com/u/167403951?v=4" style="width: 64px; height: 64px;"/></a>


### 杯盏光影阁有限公司
```
公司电话：+65 93761484
公司邮箱：info@glasscompany.com
公司地址：33 Jln Afifi, Singapore 409180
```


### 贡献指南

我们欢迎任何形式的贡献！无论是修复bug、添加新功能还是改进文档，都请提交Pull Request。

### 许可证

本项目采用[MIT许可证](LICENSE)。
