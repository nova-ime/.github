<img src="https://raw.githubusercontent.com/nova-ime/nova-macos/nova/resources/brand/xingyu-512.png" width="96" alt="星语">

## Nova 星语输入法

整句盲打，一次打对；偶尔打错，按一两个键就能改。

Nova 星语是一个本地运行的中文整句输入法。它在 [Rime](https://rime.im) 引擎上加了一个约 1 亿参数的 GPT-2 中文模型，结合你前面打过的字给整句打分。模型在本机运行，打字时不联网。

### 下载

| 系统 | 安装包 | 要求 |
|---|---|---|
| macOS | [Nova-1.0.1.pkg](https://github.com/nova-ime/nova-macos/releases/latest) | macOS 13+，Apple 芯片 |
| Windows | [Nova-1.0.2-installer.exe](https://github.com/nova-ime/nova-windows/releases/latest) | Windows 10 / 11，64 位 |

支持全拼，以及自然码、小鹤、微软、搜狗四种双拼。安装时选打法，不用改配置文件。

### 成绩

首选整句和标准答案逐字相同的比例：

| | Nova 评测集（6486 句） | 万象测试集（246 句） | 水杉测试集（1631 句） |
|---|---|---|---|
| **Nova** | **80.6%** | **90.2%** | **93.1%** |
| 万象拼音 | 61.0% | 75.2% | 83.8% |

测法和更多对比见 [nova-macos 的测试结果](https://github.com/nova-ime/nova-macos#测试结果)。

### 仓库

| 仓库 | 内容 |
|---|---|
| [nova-macos](https://github.com/nova-ime/nova-macos) | macOS 版，从鼠须管分叉；输入方案、Lua 脚本和 GPT-2 插件也在这里 |
| [nova-windows](https://github.com/nova-ime/nova-windows) | Windows 版，从小狼毫分叉 |
| [nova-model](https://github.com/nova-ime/nova-model) | GPT-2 模型文件，在 Releases 里 |

许可证：GPL-3.0。
