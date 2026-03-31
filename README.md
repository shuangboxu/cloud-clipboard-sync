项目结构：
cloud-clipboard-sync/
│
├── backend/                 # 后端服务
│
├── mobile/                  # 移动端（Android 和 iOS）
│   ├── android/             # Android 客户端
│   ├── ios/                 # iOS 客户端，暂时不做
│   ├── harmonyos/           # HarmonyOS 客户端
│
├── desktop/                 # 桌面端（Windows 和 HarmonyOS）
│   ├── windows/             # Windows 客户端，JavaFX + Maven/Gradle + jpackage
│
├── web/                     # Web 客户端
│
├── docs/                    # 文档
│
└── README.md                # 项目介绍文档

核心功能
用户认证与管理：支持用户注册、登录，且支持多设备登录和设备管理。
跨设备同步：实现 Android、Windows 和 HarmonyOS 设备之间的剪切板同步，支持文本、图片等内容。
剪切板历史管理：提供剪切板历史记录，用户可以查看过去复制过的内容并进行管理。
实时同步：实现设备间的实时同步，不需要手动刷新。

未来扩展
图片与文件同步：计划支持图片、文件等类型的数据同步，扩展产品功能。、