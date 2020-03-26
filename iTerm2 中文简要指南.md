# iTerm2 中文简要指南

iTerm2具有很多功能。以下只是主要功能！

## 拆分窗格

将一个选项卡分成多个窗格，每个窗格显示一个不同的会话。您可以垂直和水平地进行拆分，并以任何方式创建任意数量的窗格。

```
水平切分 shift + command + D
垂直切分 command + D
```

![](https://www.iterm2.com/img/screenshots/split_panes.png)

请注意非活动窗格是如何稍微变暗的，这样就很容易看出哪个是活动的。

##热键窗口

设置一个热键，当你在另一个应用程序中时，它会把iTerm2打开，并置于最前面。您可以选择让热键打开一个专用窗口。这给你提供了一个随时可用的终端。

![](https://www.iterm2.com/img/screenshots/hotkeywindow.png)

## 搜索

iTerm2具有强大的页面查找功能。所有匹配都会立即高亮显示。甚至支持正则表达式！

```
查找 command + F
```

![](https://www.iterm2.com/img/screenshots/search.png)

## 自动补全

只需键入窗口中出现过的任何单词的开头，然后输入

```
command+;
```

会弹出一个包含建议的窗口。你要找的单词通常在列表的顶端！

![](https://www.iterm2.com/img/screenshots/autocomplete.png)

## 无鼠标拷贝

使用“查找”功能开始搜索文本。按tab向右扩展选择，或按shift+tab向左扩展选择。Option + enter粘贴当前匹配。

![](https://www.iterm2.com/img/screenshots/mouselesscopy.gif)

## 粘贴历史

```
shift + command + H
```

粘贴历史允许您重新访问最近复制或粘贴的文本。您甚至可以选择将历史记录保存到磁盘，这样就不会丢失。

![](https://www.iterm2.com/img/screenshots/pastehistory.png)

## 即时回放

```
option + command + B
```

即时回放让你回到过去。这就像是为你的终端录制的视频！并且支持导出功能。

![](https://www.iterm2.com/img/screenshots/instantreplay.gif)

## 可配置

将任意键映射到任意功能。为每个option键分配单独的功能，甚至重新映射所有的修饰键。您可以定制iTerm2的外观以满足您的需求:启用透明度、背景模糊、背景图像等等。

![](https://www.iterm2.com/img/screenshots/v2-screen-shots/general.jpg)

## Unixyness

来自Unix世界？你会有宾至如归的感觉，焦点跟随鼠标、选择时复制、中间按钮粘贴和避免鼠标移动的键盘快捷键。

## 256 种颜色 (或者更多!)

在256色模式下，Vim带有逼真的效果：终端中各种各样的颜色让代码变得生动起来。版本3支持24位颜色。

![](https://www.iterm2.com/img/screenshots/256colors.png)

## 可读性

当存在许多不同的颜色或程序显示难以理解的颜色组合时，您会失去光标吗？使用“智能光标颜色”和“最小对比度”功能，可以确保这些问题永远消失。

## 鼠标报告

您可以使用鼠标报告功能，在Vim和Emacs等程序中使用鼠标来定位光标，高亮文本并执行其他功能。

### Growl支持

您可以选择接收有关活动，铃声等的怒吼（Growl）通知。 随时让长时间的工作在后台运行，以确保您会在完成后知道。

![](https://www.iterm2.com/img/screenshots/growl.png)

## Exposé标签

```
option + command + E
```

与macOS的Exposé功能一样，iTerm2在一个屏幕上显示所有选项卡。更好的是，您可以一次搜索所有内容。继续并根据需要打开任意数量的标签-您始终可以找到所需的内容。

![](https://www.iterm2.com/img/screenshots/expose.png)

## 标记的个人资料

您是否需要为许多不同的主机存储单独的配置？iTerm2提供了可标记和可搜索的配置文件数据库，因此您可以轻松找到所需的配置文件。

![](https://www.iterm2.com/img/screenshots/profiles1.png)

![](https://www.iterm2.com/img/screenshots/profiles2.png)

## 多种语言

iTerm2具有出色的国际化支持，包括对Unicode组合标记，全角字符和所有Unicode planes的支持。

![](https://www.iterm2.com/img/screenshots/utf8.png)

## 触发器

iTerm2支持用户定义的触发器，这些触发器是在收到与正则表达式匹配的文本时运行的操作。 您可以使用它突出显示单词，自动响应提示，在发生重要事件时通知您，等等。

![](https://www.iterm2.com/img/screenshots/v2-screen-shots/triggers.png)

## 智能选择

通过识别光标下方的内容并选择要选择的文本量，iTerm2可以执行“智能选择”以突出显示URL、电子邮件地址、文件名等。

# 版本3中的新功能

## Shell 集成

iTerm2可以与您的Shell集成在一起，因此它知道您的Shell提示符在哪里，您正在输入什么命令，您在哪个主机上，以及当前目录是什么。这启用了各种很酷的功能：您可以使用⇧⌘↑和⇧⌘↓轻松导航到以前的shell提示。您会记住最常用的目录。您可以自动完成以前使用的命令。以及更多！

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-shell-integration-navigation-demo.gif)

## 自动配置文件切换

使用命令行管理程序集成功能，您可以根据自己的操作使用iTerm2开关配置文件。例如，您可以定义一个ssh到某个主机名时始终使用的配置文件。 或者您的用户名是root。 甚至当您在特定目录中时。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-automatic-profile-switching.gif)

## 内嵌图片

iTerm2具有自定义转义序列，可以在终端中直接显示图像。甚至是GIF动画！

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-inline-images-demo.gif)

在iTerm2菜单中，只需单击“安装Shell集成”，就可以安装上述功能。

```
curl -L https://iterm2.com/shell_integration/install_shell_integration_and_utilities.sh | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  4434  100  4434    0     0    391      0  0:00:11  0:00:11 --:--:--   981
Downloading script from https://iterm2.com/shell_integration/zsh and saving it to /Users/user/.iterm2_shell_integration.zsh...
Checking if /Users/user/.zshrc contains iterm2_shell_integration...
Appending source command to /Users/user/.zshrc...
Downloading imgcat...
Downloading imgls...
Downloading it2api...
Downloading it2attention...
Downloading it2check...
Downloading it2copy...
Downloading it2dl...
Downloading it2getvar...
Downloading it2git...
Downloading it2setcolor...
Downloading it2setkeylabel...
Downloading it2ul...
Downloading it2universion...
Adding aliases...
Done.
--------------------------------------------------------------------------------

The next time you log in, shell integration will be enabled.

You will also have these commands:
imgcat filename
  Displays the image inline.
imgls
  Shows a directory listing with image thumbnails.
it2api
  Command-line utility to manipulate iTerm2.
it2attention start|stop|fireworks
  Gets your attention.
it2check
  Checks if the terminal is iTerm2.
it2copy [filename]
  Copies to the pasteboard.
it2dl filename
  Downloads the specified file, saving it in your Downloads folder.
it2setcolor ...
  Changes individual color settings or loads a color preset.
it2setkeylabel ...
  Changes Touch Bar function key labels.
it2ul
  Uploads a file.
it2universion
  Sets the current unicode version.
```

## 时间戳

您可以在终端中看到每行的最后修改时间。了解工作完成需要多长时间，正在查看的数据是否新鲜，或者在周末之前尝试整理一下工作，这很有用。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-timestamps.png)



## 密码管理

```
option + command + F
```

您是否发现自己一遍又一遍地输入密码？您需要记住一堆密码吗？使用iTerm2的内置密码管理器。它将您的数据安全加密地存储在macOS的钥匙串中，并受到用户帐户密码的保护。iTerm2包含一种安全机制，可确保仅在密码提示下输入密码。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-password-manager.png)

## 高级粘贴

```
option + command + V
```

使用“高级粘贴”功能，您可以在粘贴文本之前对其进行编辑，将其转换为base64，转换特殊字符等。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-advanced-paste.png)

## 注释

您可以在终端中选择文本，然后在iTerm2中为其添加注释。如果您困惑于一个大的日志文件，则用您所学的内容对其进行标记非常有用。正在进行反汇编？记下每个寄存器的作用。放飞你的想法！

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-annotations.png)

## 徽章

您可以在终端的右上角放置一个徽章，以显示有关当前会话的信息。 它可以显示您的用户名，主机名，甚至是自定义数据，例如当前的git分支。

可以在会话的设置中填写信息。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-badges.png)

## 捕获的输出

使用iTerm2作为您的IDE。在构建大型项目时，您通常不得不仔细查看其输出以查找警告和错误。不用再这样了！通过捕获的输出功能，iTerm2可以找到这些消息（基于您定义的正则表达式）并将其显示在工具栏中。您可以向右导航到每个消息。双击将运行您选择的协同处理，该协同处理可以（例如）在您喜欢的编辑器中打开出现错误的行的右侧。

![](https://www.iterm2.com/img/screenshots/v3-screen-shots/iterm2-captured-output.gif)

参考文献：

https://www.iterm2.com/features.html

https://www.iterm2.com/documentation-images.html

https://www.iterm2.com/documentation-utilities.html