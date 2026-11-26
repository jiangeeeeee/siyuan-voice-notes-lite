# <img src="https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/icon.png" width="36" height="36" alt=""> 思源语音 Lite

会上刚定下交付日期，你在笔记里写了个“周五”。想核对是谁说的、有没有附加条件，点那段原音就能再听一遍。Lite 不带识别模型，适合录音、导入字幕和整理笔记。想边录边出文字，可以选 [Full](https://github.com/jiangeeeeee/siyuan-voice-notes)。

**当前版本 0.9.0** · 思源 3.8.9 及以上 · 桌面端、浏览器及移动端（会议录音见下） · [下载 Lite 安装包（package.zip）](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/download/v0.9.0/package.zip)

## 🌟 本版新增 · 会议录音

| 想做什么 | 从哪里开始 |
| --- | --- |
| 录下会议里对方说的话 | 文档上方的声波图标 →「会议录音」→「只录系统声音」。戴着耳机也能录，麦克风可以关着。 |
| 把自己的发言也录进去 | 在「会议录音」中选「系统声音和麦克风」。双方的声音会存进同一条语音块，用耳机可以减少对方声音被麦克风再收一次。 |
| 长会只想先留下原音 | 把录音控制点「收起」，波形会停画，声音继续按秒写入草稿。听到要紧的地方，再打开录音控制加标记。 |

在 Windows 或支持系统音频采集的 macOS 桌面端，可录电脑正在播放的声音。Mac 首次使用时，请按系统提示允许思源录制屏幕与系统音频。也可以用本机 Chrome 或 Edge 打开思源，在共享窗口选择会议标签页，勾选「同时共享标签页音频」。Linux 请使用浏览器标签页录音。能选哪些声音取决于系统和浏览器，手机端仍可用麦克风录音。

![从声波菜单选择会议录音和声音来源，结束后在正文里找到会议语音块](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.9.0/docs/demos/meeting-lite.gif)

## ✍️ 已有功能

| 想做什么 | 从哪里开始 |
| --- | --- |
| 现场录音和导入 | 点声波图标 →「开始录音」录麦克风，也可以点「导入音频」，把录音和同名 SRT、VTT 字幕一起放进正文。中断的录音可从「恢复未保存录音」找回。 |
| 找到要听的几秒 | 点波形跳到原话，拖「缩放」看清细节，拖「浏览」看前后文。点「＋ 标记」给这一刻起个名字，回听时从标记列表跳回来。 |
| 只留有用的片段 | 「更多操作 → 音频与文件 → 裁剪录音」可保留或删除多个时间段。先试听接缝，再确认替换，指向保留内容的原音链接会跟着调整。 |
| 从笔记回到会议现场 | 勾选「同步正文笔记与音频」，边听边写。也可以按住 Ctrl（Mac 可用 Command）在波形上点出起止位置，用「复制所选音频链接」引用整句话。 |
| 整理逐字稿 | 在「显示转写」里点一句话的「批注与编辑」，改字、拆段、加标签，或把疑问写成批注。已有 TXT 文稿也能导入。 |
| 分清谁说了什么 | 会前可填参会人名单，录音中点「变更发言人」。回听时右键点人物色带，可改名或清除这一段的人物标注。 |
| 一次改好同一个错词 | 在「逐字稿与校对」里打开「本条录音附加词库」，填入原词和正确写法，逐段预览后确认替换。 |
| 导出和备份 | 「逐字稿与校对 → 导出逐字稿」可以附上时间戳和人物姓名。「信息 → 导出 VoiceKnowledge JSON」可带走标记、人物与批注，音频另存在思源工作空间的 assets 目录。 |

### 录一条声音，再把它放进笔记

开始录音，暂停后继续，结束录音后直接播放正文中生成的语音块。

![开始录音，暂停后继续，结束录音后直接播放正文中生成的语音块](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/record-lite.gif)

打开声波图标导入录音和同名字幕，正文里出现可播放的语音块和对应文字。

![打开声波图标导入录音和同名字幕，正文里出现可播放的语音块和对应文字](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/import.gif)

展开更多操作的四个分类，进入逐字稿与校对，打开导出选项。

![展开更多操作的四个分类，进入逐字稿与校对，打开导出选项](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/menu-lite.gif)

### 复听、标记与裁剪

播放指针停在实验说明附近，向右拖缩放滑块，40 秒的音轨逐步展开为几秒的细节。

![播放指针停在实验说明附近，向右拖缩放滑块，40 秒的音轨逐步展开为几秒的细节](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/zoom.gif)

在播放位置写下开始计时和实验备注，保存后从时间轴和列表找到标记。

![在播放位置写下开始计时和实验备注，保存后从时间轴和列表找到标记](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/mark.gif)

填写两段保留时间，生成试听文件并确认替换，40 秒的录音变为 11 秒。

![填写两段保留时间，生成试听文件并确认替换，40 秒的录音变为 11 秒](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/trim.gif)

### 让笔记指向原话

播放时写下两杯水要同时开始计时，再从这段正文旁的回听按钮打开原音。

![播放时写下两杯水要同时开始计时，再从这段正文旁的回听按钮打开原音](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/sync.gif)

在音轨上选定原话的起止位置，把原音链接附到实验结论上，再从正文打开播放器。

![在音轨上选定原话的起止位置，把原音链接附到实验结论上，再从正文打开播放器](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/link.gif)

### 整理文字和发言人

在批注与编辑中修改一句转写并加上实验准备标签，用标签找回这句话。

![在批注与编辑中修改一句转写并加上实验准备标签，用标签找回这句话](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/edit-lite.gif)

给实验准备这句话写一条提醒，保存后点开语段旁的计数重读批注。

![给实验准备这句话写一条提醒，保存后点开语段旁的计数重读批注](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/annotate.gif)

右键第二段发言区间，把同学改为助教，第一段仍显示林老师。

![右键第二段发言区间，把同学改为助教，第一段仍显示林老师](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/speaker.gif)

保存一条纠错规则，在逐段预览中确认替换，回到逐字稿查看修改后的句子。

![保存一条纠错规则，在逐段预览中确认替换，回到逐字稿查看修改后的句子](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/vocab.gif)

### 导出逐字稿与备份

选择时间戳和发言人，下载并打开 TXT，看到每段原话、姓名和时间。

![选择时间戳和发言人，下载并打开 TXT，看到每段原话、姓名和时间](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/export-lite.gif)

展开信息页的备份与恢复工具，导出并打开 JSON 查看录音路径、时长和人物数据。

![展开信息页的备份与恢复工具，导出并打开 JSON 查看录音路径、时长和人物数据](https://gcore.jsdelivr.net/gh/jiangeeeeee/siyuan-voice-notes-lite@v0.8.5/docs/demos/backup.gif)

[安装与版本切换](INSTALL.md) · [使用手册](docs/user/使用手册.md) · [许可证](LICENSE) · [第三方声明](THIRD_PARTY_NOTICES.md)

## 🕰 版本记录

| 版本 | 主要更新 |
| --- | --- |
| [0.9.0](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.9.0) | 新增会议录音，可单录系统声音，也可把麦克风一起录进去。 |
| [0.8.6](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.6) | 修正 GitHub 和思源集市里的动图链接。 |
| [0.8.5](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.5) | 文档录音入口和语音块有了同一枚声波图标。「更多操作」按用途收成四组，点开一组就能找到相关按钮。 |
| [0.8.4](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.4) | 可以试听并保留或删除多个时间段，已有引用会跟随裁剪重新定位。时间轴改为围绕播放位置按比例缩放。 |
| [0.8.3](https://github.com/jiangeeeeee/siyuan-voice-notes-lite/releases/tag/v0.8.3) | Lite 首次独立发布。可以录音、导入字幕、手工整理逐字稿，安装包不含识别模型。 |
