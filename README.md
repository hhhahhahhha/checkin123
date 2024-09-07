# GLaDOS 自动签到，实现无限白嫖

原仓库地址：https://github.com/lukesyy/glados_automation

复制了一个仓库，进行了些修改，防止原仓库被封

环境变量：`GLADOS_COOKIE`（必要） 和 `PUSHPLUS_TOKEN`（非必要）

`GLADOS_COOKIE`多个账号需使用 '&' 隔开，示例：cookie&cookie



# Github Actions

1. 点击右上角 **fork** 按钮
2. 在自己仓库中打开此项目
3. 将 `runGladosAction.yml` 放入 `.github/workflows` 文件夹下
4. 配置环境变量
5. 点亮右上角的星星 **star** 激活 actions
6. 然后点击 Actions 标签查看运行的详细状况
