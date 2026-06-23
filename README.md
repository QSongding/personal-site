# Personal Site

🌐 **网站地址**: https://l42857.dpdns.org

## 部署信息

- **托管平台**: Cloudflare Pages
- **源代码**: GitHub
- **域名**: l42857.dpdns.org

## 本地开发

```bash
# 启动本地服务器
cd site-crawl
python3 -m http.server 8080
```

访问 http://localhost:8080/cherished-happen-241290.framer.app/

## 目录结构

```
.
├── site-crawl/                  # 抓取的网站文件
│   ├── cherished-happen-241290.framer.app/  # 主站
│   ├── events.framer.com/       # 事件跟踪
│   ├── example.com/             # 示例
│   └── framerusercontent.com/   # 静态资源
├── CNAME                        # 自定义域名配置
└── README.md                    # 项目说明
```

## Cloudflare Pages 配置

- **构建命令**: 留空（静态网站）
- **输出目录**: `site-crawl/cherished-happen-241290.framer.app`

## 技术栈

- **前端框架**: Framer (React)
- **字体**: Inter, BDO Grotesk
- **部署**: Cloudflare Pages + GitHub
