# Jialu-Guidebooks Repo 架构设计

## 目录结构

```
Jialu-Guidebooks/
├── README.md                          # 主入口（英文）
├── README_CN.md                       # 中文版 README
├── LICENSE                            # 开源协议（推荐 CC BY-NC-SA 4.0）
├── CONTRIBUTING.md                    # 贡献指南
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       ├── feature_request.md
│       └── translation_improvement.md
│
├── guides/                            # 所有指南的根目录
│   ├── ai-short-drama/               # AI短剧从入门到精通
│   │   ├── zh-CN/                     # 中文版
│   │   │   └── README.md             # 或 PDF / 完整文档
│   │   └── en/                        # 英文版
│   │       └── README.md
│   │
│   ├── deerflow-2.0/                  # DeerFlow 2.0从入门到精通
│   │   ├── zh-CN/
│   │   │   └── README.md
│   │   └── en/
│   │       └── README.md
│   │
│   ├── multi-agent-architecture/      # 多Agent架构从入门到精通
│   │   ├── zh-CN/
│   │   │   └── README.md
│   │   └── en/
│   │       └── README.md
│   │
│   ├── coze/                          # Coze从入门到精通
│   │   ├── zh-CN/
│   │   │   └── README.md
│   │   └── en/
│   │       └── README.md
│   │
│   ├── ai-avatar/                     # AI分身从入门到精通
│   │   ├── zh-CN/
│   │   │   └── README.md
│   │   └── en/
│   │       └── README.md
│   │
│   └── ai-native-organization/        # AI Native组织从入门到精通
│       ├── zh-CN/
│       │   └── README.md
│       └── en/
│           └── README.md
│
├── assets/                            # 全局静态资源
│   ├── banner.png                     # 顶部 Banner
│   ├── logo.png                       # Logo
│   └── covers/                        # 每本指南的封面图
│       ├── ai-short-drama.png
│       ├── deerflow-2.0.png
│       ├── multi-agent-architecture.png
│       ├── coze.png
│       ├── ai-avatar.png
│       └── ai-native-organization.png
│
└── CHANGELOG.md                       # 更新日志
```

## 设计原则

1. **每个指南一个文件夹**：方便单独维护、版本管理
2. **zh-CN / en 双语子目录**：结构清晰，读者一目了然
3. **assets 集中管理**：封面图、Banner 统一存放，README 引用方便
4. **新增指南只需复制目录结构**：降低维护成本
5. **CHANGELOG.md**：让读者知道什么时候有新教程发布
