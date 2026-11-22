# <img src="https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/icon.png" width="36" height="36" alt=""> 思源语音 Lite

实验课上记下了“温水里的糖先溶解”，复习时却想再听听老师是怎么解释的。用思源语音把录音放进笔记，再给这句话加一个原音链接，下次点它就能从那一段开始听。这里的 Lite 可以录音、导入字幕和手工整理逐字稿，需要本地转写和发言人识别模型的话，可以选 [Full](https://github.com/jiangeeeeee/siyuan-voice-notes)。

**当前版本 0.8.6** · 思源 3.8.9 及以上 · 桌面端、移动端和浏览器 · [下载 Lite 安装包（package.zip）](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/download/v0.8.6/package.zip)

## 🌟 新版界面

| 想做什么 | 从哪里开始 |
| --- | --- |
| 把第一条录音放进笔记 | 文档面包屑上的「思源语音 · 录音 / 导入」→「导入音频」 |
| 剪掉录音里的休息时间 | 语音块「更多操作」→「音频与文件」→「裁剪录音」 |
| 在播放位置换一位发言人 | 「更多操作」→「发言人」→「从此处切换发言人」 |
| 把逐字稿带出思源 | 「更多操作」→「逐字稿与校对」→「导出逐字稿」 |
| 找到引用这条录音的笔记 | 「更多操作」→「批注与引用」→「查看正文与原音引用」 |

### 认准声波图标，放进第一条录音

先在正文点一下，选好放录音的位置。看文档上方显示笔记路径的那一行，点新的声波对话框图标，选「导入音频」，再选一条手机录音。图中把实验录音和同名字幕一起导入。自己试时，只选音频也可以。

正文里会出现一个带同样图标的语音块。点播放键就能听。如果一起选了 SRT 或 VTT 字幕，勾选「显示转写」还能看到每段话及其对应的时间。

![打开声波图标导入录音和同名字幕，正文里出现可播放的语音块和对应文字](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/import.gif)

### 想导出逐字稿，先展开「逐字稿与校对」

刚导入的实验课字幕也能单独导出。点语音块右上角的三个点「更多操作」，展开「逐字稿与校对」，再点「导出逐字稿」。在弹窗里勾选「添加时间戳」和「添加发言人」，就可以下载一份带时间和姓名的文本。

「更多操作」分成四组。剪录音在「音频与文件」，改人物在「发言人」，找笔记里的原音链接在「批注与引用」。点另一组，前一组就会收起。听到重点时，仍然可以直接点三个点旁边的「＋ 标记」。

![展开更多操作的四个分类，进入逐字稿与校对，打开导出选项](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/menu-lite.gif)

## ✍️ 其余功能

### 上课先录下来，下课就能听

在正文放好光标，点声波图标里的「开始录音」。听课中途可以暂停，接着讲时点「继续录音」。点「结束录音」，声音就保存在刚才选好的位置。第一次录音需要允许使用麦克风。双击保存后的录音标题，就能给这堂课起个好找的名字。

开会时可以先用「会前设置参会人」填好名单，再在录音控制里「变更发言人」。想把录音控件收起来，可以在开始前勾选「隐私模式 · 仅在面包屑提示录音」。如果录音被意外中断，可从文档上方的声波图标打开「恢复未保存录音」，查看当前设备还留有哪些草稿。

![开始录音，暂停后继续，结束录音后直接播放正文中生成的语音块](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/record-lite.gif)

### 放大一句话，再给它留个标记

点击波形跳到想听的位置，拖「缩放」逐步看清几秒钟的细节。每拖过相同距离，可见时长按相同比例变化。播放指针在画面内时会尽量留在原处。要看前后文，再拖「浏览」。也可以直接输入时、分、秒，或用播放器前后跳 15 秒。

![播放指针停在实验说明附近，向右拖缩放滑块，40 秒的音轨逐步展开为几秒的细节](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/zoom.gif)

听到老师说“现在开始计时”，点「＋ 标记」，把名称写成“开始计时”，备注里写下“两杯水同时加糖”。保存后，波形边会多一个标记。下次打开「标记」列表，就能从这里回听。

![在播放位置写下开始计时和实验备注，保存后从时间轴和列表找到标记](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/mark.gif)

### 一堂课只想留下两段声音

打开「音频与文件 → 裁剪录音」，选「只保留这些段」，每行填一对起止时间。图中保留了第 8 至 14 秒和第 25 至 30 秒，两段合起来是 11 秒。若只想去掉休息时间，就选「删除这些段」。点「生成并试听」，听过接缝、看过大小，再点「确认替换录音」。

原先指向保留内容的双链会跟着调整。整段都被剪掉时，点链接会看到提示，转写和批注文字仍在。若别的笔记还引用旧音频文件，思源会保留那份文件。

![填写两段保留时间，生成试听文件并确认替换，40 秒的录音变为 11 秒](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/trim.gif)

### 边听边记，让正文记住写下这句话的时刻

在语音块中勾选「同步正文笔记与音频」，开始播放，再回到正文写笔记。新段落旁会出现回听按钮。点它就能回到写这段话时正在播放的地方。录音控制也有正文同步开关。想先听一听上文，可以在插件设置中调整回听提前量。

![播放时写下两杯水要同时开始计时，再从这段正文旁的回听按钮打开原音](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/sync.gif)

### 给结论引用一段有头有尾的原话

按住 Ctrl（Mac 也可用 Command）在波形上点两处，再点「复制所选音频链接」。可以直接粘贴到正文，也可以选中已有的一句话，点选区工具栏的「链接至语音」。逐字稿已有时间定位时，点该段右侧的「复制语音段链接」更快。

点正文引用即可回听。要反过来找哪些笔记用了这段录音，打开「批注与引用 → 查看正文与原音引用」。

![在音轨上选定原话的起止位置，把原音链接附到实验结论上，再从正文打开播放器](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/link.gif)

### 改一段文字，把自己的想法写在旁边

在「显示转写」里找到要整理的那一句，点「批注与编辑」。可以改文字、发言人、起止时间和标签，也可以拆分语段或合并下一段。长逐字稿可以按人物筛选，也可以搜标签。手里只有 TXT 文稿也能先导入整理。没有现成文字时，勾选「显示转写」，点「手动添加转写」记下原话。暂时记不清时间的话，可以留空。

![在批注与编辑中修改一句转写并加上实验准备标签，用标签找回这句话](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/edit-lite.gif)

要留自己的想法，在同一窗口点「写批注」。保存后，语段旁会出现批注数量，点开就能读。想按“疑问”“待办”等习惯分类，可以在「批注与引用 → 设置批注类型」里调整。

![给实验准备这句话写一条提醒，保存后点开语段旁的计数重读批注](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/annotate.gif)

### 人物标错了，只改这一段

音轨上的色带表示发言区间。右键点一段色带，选「变更此段发言人」，从名单中选择，或填入新姓名。若只想清除人物标注，同一个右键菜单里也能删除。要调整切换时刻，打开「发言人 → 发言人切换记录」。

![右键第二段发言区间，把同学改为助教，第一段仍显示林老师](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/speaker.gif)

### 把反复出现的错词一次改好

打开「逐字稿与校对 → 本条录音附加词库」，点「＋ 纠错规则」，分别填写原词和正确写法。再点「按纠错词库预览替换」，逐段核对，确认后才会写回。改得不合适，可以在同一分类里撤销上次批量纠错。多门课都会用到的人名、缩写，也可以放进插件设置里的全局词库。

![保存一条纠错规则，在逐段预览中确认替换，回到逐字稿查看修改后的句子](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/vocab.gif)

### 导出一份别人也能打开的逐字稿

打开「逐字稿与校对 → 导出逐字稿」，选择是否添加时间戳和发言人，再点「下载逐字稿 TXT」。用普通文本编辑器打开，就能读到按时间排列的内容。

![选择时间戳和发言人，下载并打开 TXT，看到每段原话、姓名和时间](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/export-lite.gif)

想连同标记、批注和人物一起备份，可以在「信息」里点「导出 VoiceKnowledge JSON」。音频本身单独保存在工作空间的 `assets` 目录，迁移时记得把它和笔记一起带走。「信息 → 高级 / 导入与恢复」可以把同一录音的 JSON 重新读进来。

![展开信息页的备份与恢复工具，导出并打开 JSON 查看录音路径、时长和人物数据](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/backup.gif)

[安装与版本切换](INSTALL.md) · [使用手册](docs/user/使用手册.md) · [许可证](LICENSE) · [第三方声明](THIRD_PARTY_NOTICES.md)

## 🕰 版本记录

| 版本 | 主要更新 |
| --- | --- |
| [0.8.6](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.6) | 修正 GitHub 和思源集市里的动图链接。 |
| [0.8.5](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.5) | 文档录音入口和语音块有了同一枚声波图标。「更多操作」按用途收成四组，点开一组就能找到相关按钮。 |
| [0.8.4](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.4) | 可以试听并保留或删除多个时间段，已有引用会跟随裁剪重新定位。时间轴改为围绕播放位置按比例缩放。 |
| [0.8.3](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.3) | Lite 首次独立发布。可以录音、导入字幕、手工整理逐字稿，安装包不含识别模型。 |
