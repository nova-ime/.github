<p align="center">
  <img src="https://raw.githubusercontent.com/nova-ime/nova-macos/nova/resources/brand/xingyu-512.png" width="112" alt="星语">
</p>

<h2 align="center">Nova 星语输入法</h2>

<p align="center">整句盲打，一次打对。不联网，免费，开源。</p>

<p align="center">
  <a href="https://github.com/nova-ime/nova-macos/releases/latest"><b>下载 macOS 版</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/nova-ime/nova-windows/releases/latest"><b>下载 Windows 版</b></a>
</p>

### 为什么可以放心用

- **准。** 6486 句真实文本，首选整句和原文一字不差的比例是 80.6%。在两款国内知名开源输入法自己公开的测试集上，Nova 的成绩也比它们高（见下表）。
- **不联网。** 约 1 亿参数的 GPT-2 中文模型就在你的电脑上运行，打的字不会离开这台电脑。可以用系统的活动监视器或资源监视器自己查。
- **看到什么，上屏什么。** 候选不会在你按空格的那一刻悄悄换掉。
- **改起来快。** 紫色的词是 Nova 结合上下文改过的，备选就列在它下面，按数字就换。Tab、Shift+Tab 逐词跳到要改的地方，不用退格重打。
- **装上就能用。** 安装时选打法，不用改配置文件。
- **只做打字。** 没有广告、弹窗和账号。

### 下载

| 系统 | 安装包 | 要求 |
|---|---|---|
| macOS | [Nova-1.0.3.pkg](https://github.com/nova-ime/nova-macos/releases/latest) | macOS 13+，Apple 芯片 |
| Windows | [Nova-1.0.3-installer.exe](https://github.com/nova-ime/nova-windows/releases/latest) | Windows 10 / 11，64 位 |

### 成绩

首选整句和标准答案逐字相同的比例。三组都是打完一整句、不挑候选，第一个就对才算：

| | Nova 评测集<br>6486 句 | 开源输入法 A 的公开测试集<br>246 句 | 开源输入法 B 的公开测试集<br>1631 句 |
|---|---|---|---|
| **Nova** | **80.6%** | **90.2%** | **93.1%** |
| 开源输入法 A | 61.0% | 75.2% | 83.8% |

A、B 都是国内知名的开源输入法。具体版本、测法和逐句结果见 [nova-macos 的测试结果](https://github.com/nova-ime/nova-macos#测试结果)，可以自己复现。

### 能做什么

- 全拼，以及自然码、小鹤、微软、搜狗四种双拼
- 辅助码：在拼音后打 `` ` `` 加形码，筛出想要的字
- 全拼拼错个别字母也能认出来，比如 `kafeigaun` 照样出「咖啡馆」
- 表情、符号、日期：`obq` 列出表情，`orq` 列出今天日期的几种写法
- Shift 切换中英文
- 学错的词，在它上面按 Shift+Delete 就删掉

### 仓库

| 仓库 | 内容 |
|---|---|
| [nova-macos](https://github.com/nova-ime/nova-macos) | macOS 版，从鼠须管分叉；输入方案、Lua 脚本和 GPT-2 插件也在这里 |
| [nova-windows](https://github.com/nova-ime/nova-windows) | Windows 版，从小狼毫分叉 |
| [nova-model](https://github.com/nova-ime/nova-model) | GPT-2 模型文件，在 Releases 里 |

基于 [Rime](https://rime.im) 引擎。许可证：GPL-3.0。
