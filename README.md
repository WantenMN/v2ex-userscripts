## V2EX Login State Toggle

### 用途

TLDR: 尽可能避免增加账号的活跃度

登录状态下，请求站内任意网页都会增加一点活跃度，如果你不想让你的活跃度增加，你有这些选项：

- 退出登录
- 在隐私窗口或其他浏览器打开 v2ex
- 打开镜像网站
- 移除并恢复 cookie

这个脚本的作用便是在同一窗口，同一页面，快捷移除或恢复 cookie，实现未登录或已登录的效果。未登录状态，自然不会增加活跃度。

### 使用

安装脚本后，刷新页面，你会在右下角看到一个小按钮，登陆状态按钮为绿色，未登录状态按钮为黄色。点击按钮会立即切换登录状态。

一般情况浏览主题/帖子，使用黄色按钮，即未登录状态。当你要回复或发帖时，请点击按钮，切换至登录状态，此时按钮为绿色。

### 链接

- **脚本**：https://greasyfork.org/en/scripts/509863
- **源代码**：https://github.com/WantenMN/v2ex-userscripts/blob/main/v2ex_login_state_toggle/index.user.js

## V2EX Domain Switcher （已弃用）

已弃用，请使用新的实现：[V2EX Login State Toggle](https://greasyfork.org/en/scripts/509863)

### 用途

TLDR: 尽可能避免增加账号的活跃度

登录状态下，请求任意站内网页都会增加一点活跃度，如果你不想让你的活跃度增加，你有这些选项：

1. 退出登录
2. 在隐私窗口或其他浏览器打开 v2ex
3. 打开镜像网站

这个脚本的作用便是在同一窗口，同一页面，快捷切换当前使用的站点，达到登录，不登录的目的。未登录状态，自然不会增加活跃度。

### 使用

安装脚本后，刷新页面，你会在右下角看到一个小按钮，当域名为 `v2ex.com` 时，按钮为绿色（登录状态）；域名为 `global.v2ex.co` 时，按钮为黄色（未登录）。点击按钮会立即切换到另一个域名。

请只登录 `v2ex.com`，而不登录 `global.v2ex.co`。

一般情况浏览主题/帖子，使用 `global.v2ex.co`，即按钮为黄色。当你要回复或发帖时，请点击按钮，切换至登录状态，`v2ex.com` 域名，此时按钮为绿色。

### 链接

- **脚本**：https://greasyfork.org/en/scripts/509836
- **源代码**：https://github.com/WantenMN/v2ex-userscripts/blob/main/domain_switcher/domain_switcher.user.js
