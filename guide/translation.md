# 翻译步骤

新加入的译者，需要完成一些基础准备工作，才能投入到翻译贡献当中。

根据你的喜好和技术基础，你可以选择在[本地计算机](translation_local.md)进行翻译，也可以选择全程都在 [GitHub 网站](translation_web.md)上进行。具体的细节流程在此不赘述。

翻译需要首先对喜好的文章进行申请，然后将该申请发起 PR。通常来说，只要该 PR 在提交后显示并无冲突、也满足了 CI 检查，就可以自行翻译了，而不需要等待 PR 得到批准。每翻译一篇文章，都需要单独就此文章发起一个 PR。

翻译完毕后，将该译文从 `sources` 目录移动到 `translated` 对应的子目录下，然后对该成果发起 PR。等待批准进入仓库即可。

## 翻译的规则

译者在翻译文章时，要遵循如下规则：

- 要忠实原文，可以在不损失原文含义的情况下进行意译，但是不能导致读者有误解和难以理解的语素增加。
- 译文的排版要求符合[中文排版指北](../tutorials/copywriting.md)。
- 所有内置的代码要格式正确（通常选题会确保正确），如果原文有误，可以修改。
- 正确使用 Markdown 标签，通常沿袭选题原文中的标签即可。
- 在必要时，如原文有误、原文需要进一步解释时，可以增加译注。
- 遇到专有名词时可以使用 RUBY 标签，即：`<ruby>这是中文<rt>This is English</rt></ruby>`。RUBY 标签是我们正常情况下唯一允许使用的 HTML 标签。
- 正确输入元信息，即在（新模板）文章头部的 `[#]: translator: ( )` 的 `()` 中输入你的译者 ID；也需要在文末的 `译者ID` 处同样输入。

## 译后检查

完成翻译后，需要译者至少自行检查一遍：

- 检查全篇是否格式排版规范。
- 检查全篇是否通顺、行文是否一致。
- 检查段落组织是否合理，必要时可以调整段落设置。

## 禁止事项

- 我们允许使用类似谷歌翻译这样的工具来辅助翻译，但是**绝不允许**直接提交翻译工具的结果，略加修改就提交上来。
- 我们鼓励各种英语水平和技术水平的人参与翻译贡献，因此，选择符合自己能力和兴趣的文章翻译即可，但是**绝不允许**委托他人代为翻译，也**绝不允许**照抄网络上别人已有译文。
