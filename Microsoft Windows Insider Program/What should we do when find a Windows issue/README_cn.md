# 当发现 Windows 问题时，该如何处理？

[**English Documentation (英文版本)**](https://github.com/Lingggao/Microsoft-Insider-Program/tree/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue)

## 一、概述

Microsoft 为产品爱好者们提供 Windows 预览体验计划服务的目的是**获取更多关于 “用户对 Windows 预览体验计划服务的喜好以及期望进行的更改” 的信息**。用户通过注册 Windows 预览体验计划获得了使用最新版本 Windows、参与系统测试的**权利**，自然也应当履行向 Microsoft 提供反馈的**义务**。

综上所述，我认为，当一个 Windows 预览体验成员只是 “静默” 的使用 Windows 预览体验版本，而不向 Microsoft 提供任何反馈的话，他基本是没有价值的。**只有当越来越多数量的用户被 Windows 预览体验计划所吸引，进而向 Microsoft 提供越来越多数量的反馈，帮助 Microsoft 尽全力优化 Windows，使得 Windows 预览体验计划吸引越来越多的产品爱好者，形成了这样一个良性循环时，Windows 预览体验计划才能真正的发挥 “打造 Windows 10 未来的演变” 的根本目的。**

虽然说向 Microsoft 提供尽可能多数量的反馈是每个 Windows 预览体验成员的义务，但是我认为，每位预览体验成员都应当牢记：**我们应当提供高质量的反馈，尽量避免提供低质量的反馈**。Microsoft 每天都会接到**数以十万计**的用户反馈，为了尽可能的降低工程师们的工作量，转而将精力用于解决问题，努力提高反馈质量是非常有必要的。那么，现在就有了一个亟待解决的问题 —— **如何切实提高反馈的质量，避免向 Microsoft 提供低质量、不完整甚至毫无作用的反馈**？

以下是我关于这个问题的**个人见解**，希望可以帮助到各位预览体验成员们：

## 二、什么是高质量反馈？

若想为 Microsoft 提供高质量的 Windows 反馈，我们首先应当对 **“高质量”** 有一个完整的评判标准。**我认为，一个高质量的 Windows 反馈应当至少包含以下几点信息：**

### 问题反馈

1. 首先用**一句话**简明的描述出现了什么问题。
2. **正常情况下**此处应当是什么情况？
3. **目前**出现了什么错误的情况？
4. 提供**重现**这一错误的操作步骤。
5. 提供 **Windows 版本号**信息。
6. **[可选]** 提供**设备品牌与详细型号** (品牌机) 或**主板型号** (组装机)。
7. **[可选]** 提供出现这一问题时的**完整屏幕截图**。
8. **[可选]** 重启设备、使用任务管理器结束进程等**常规修复操作**能否暂时解决这一问题？
9. **[推荐]** 使用**感谢词**作为反馈结束语。

**举例 1：**  

Build 19564_OneDrive 突然无法正常使用，同时任务栏中的 “云朵” 形状图标消失。

更新至 Build 19564 版本后，OneDrive 突然无法正常使用。点击 OneDrive 应用后，无法弹出文件夹，同时任务栏中的 “云朵” 形状图标消失。与此同时，任务管理器中 “Microsoft OneDrive (32 位)” 进程持续占用 15% 左右的 CPU，导致设备风扇一直处于运转状态。

请调查此问题。Thanks very much.

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Feedback.png?raw=true" width = "80%" />

> 本举例选自于我个人提交的 Windows 反馈。

**举例 2：**

Build 19559_按 “Windows 徽标键+V” 快捷键启动 “剪贴板历史记录” 并将其关闭后，无法继续输入文字。

在 Build 19559 版本中，按下 “Windows 徽标键+V” 快捷键启动 “剪贴板历史记录” 后，如果不粘贴任何内容并直接将其关闭，将无法继续使用键盘输入文字。重启设备可以暂时解决这一问题。

请调查此问题。Thanks very much.

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Feedback_2.png?raw=true" width = "80%" />

> 本举例同样选自于我个人提交的 Windows 反馈。

---
### 建议反馈

1. 首先用**一句话**简明的描述需要提交的建议。
2. **目前**是什么情况？(对什么现象不满意？)
3. 您**希望发生**什么情况？(希望 Microsoft 作出哪些改进？)
4. 提供针对此建议可能可行的**解决方案**，以便 Microsoft 在处理时进行参考。
5. [**可选**] 提供有关这一建议的**屏幕截图**。
6. **[推荐]** 使用**感谢词**作为反馈结束语。

**举例 1：**

希望反馈中心添加 “重新选择反馈类别” 的功能。

在目前，如果用户在反馈中心中添加反馈时选择了错误的类别，在提交完毕后是没有办法修改的。希望反馈中心添加 “重新选择反馈类别” 的功能，如果用户选择了错误的类别，可以重新进行修改，以免负责此类别的 Microsoft 工程师无法接收到用户提交的反馈。

希望 Microsoft 考虑此建议。Thanks very much.

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Feedback_3.png?raw=true" width = "80%" />

> 本举例选自于我个人提交的 Windows 反馈。

## 三、如何决定是否应当提交反馈？

在上面的文章中我们提到过，Microsoft 每天都会接到数以十万计的用户反馈。为了更进一步的降低工程师们的工作量，我认为，**我们不应当在发现一个问题 (或想出一个建议) 时立即编写反馈，也不应当每发现一个问题 (或想出一个建议) 就编写一次反馈**。而是要进行详细的调查与分析，着力于研究 **“是否应当提交反馈”** 以及 **“如何提交更加详细的反馈”** 这两个问题。

我们首先研究第一个问题 —— **如何决定是否应当提交反馈？**

既然这个问题确实存在，那么一定可以说明**某些 Windows 问题或建议是不应当向 Microsoft 提交反馈的**。我们只要确定了哪些反馈是不应当提交的，剩下的反馈就全部是需要提交的。什么是 **“不应当提交反馈”** 的问题？我认为，**有关以下 3 种 Windows 问题或建议，是不应当向 Microsoft 提交反馈的**：

---
### 不要提交 “已经有 Windows 预览体验成员提交过” 的问题或建议。

Windows 预览体验计划荟聚世界各地的**数百万**人，共同打造 Windows 10 未来的演变。我认为，**每位预览体验成员所发现的问题或想出的建议，有不小的概率早已被其他的成员所发现或想出。因此，每位预览体验成员都不应当直接认定自己是某反馈的 “第一作者”**。根据 Microsoft 官方文档，Windows 预览体验计划团队不鼓励提交 “过去已经有用户提交过的反馈”。因此，**我们在发现问题或想出建议时，应当首先通过反馈中心进行搜索，确认是否已有相似的反馈被其他预览体验成员所提交**。如果已有相似反馈的话，我们应当放弃提交此反馈，转而选择使用 **“投赞成票”、“添加类似反馈”、“撰写评论”** 等功能以向 Microsoft 提供个人见解。

*在记录新反馈之前，请检查其他人是否已请求或报告了相似的反馈。如果您发现有类似的问题或建议，请“点赞 ”并添加评论以使现有信息更清晰，或添加要查看的方案。如果您未在 “反馈中心 ” 发现与您的反馈类似的问题或建议，请单击 “反馈中心 ” 搜索栏旁边的 “+ 添加新反馈 ” 来添加新反馈*。

> 摘自 Windows 预览体验计划官方文档。

---
### 不要提交 “仅适用于已经停止支持 Windows 版本” 的问题或建议。

**现代生命周期策略**涵盖连续提供服务和支持的产品和服务。在此策略下，如果满足以下条件，产品或服务将持续获得支持：

1. 客户必须按照对产品或服务发布的服务和系统要求保持最新。
2. 若要使用产品或服务，客户必须获得授权。
3. Microsoft 当前必须为产品或服务提供支持。

Windows 10 系统也受到**现代生命周期策略**的约束。Microsoft 会在每年的 3 月与 9 月发布一次 Windows 10 功能更新，**对于家庭版与专业版用户，支持周期截止至功能更新发布日期起第 18 个月**。如果用户未在支持截至前将 Windows 更新至下一次功能更新的话，则 Windows 会转变为 **“已经停止支持”** 状态。

例如：Windows 10 1809 版本于 **2018 年 11 月 13 日**发布，将会于 18 个月后的 **2020 年 5 月 12 日**停止支持。如果用户未能在 **2020 年 5 月 12 日**前将 Windows 更新至 **1903** 或 **1909** 版本的话，则系统将会转变为 **“已经停止支持”** 状态。

某个 Windows 版本停止支持后，Microsoft 不会再为此版本系统提供后续的产品或服务。也就是说，**即使已停止支持的 Windows 系统中仍然存在问题，或者用户希望提出针对此版本 Windows 的功能建议，Microsoft 将大概率不会进行任何的改进或修复**。因此，提交 “**仅**适用于已经停止支持的 Windows 版本” 的问题或建议是没有价值的。

我认为，**每名 Windows 预览体验成员都应当做到每周或每两周检查一次 Windows 更新，并在检查到新版本后尽快执行下载与安装。如果确实无法做到的话，也应当至少每个月检查一次更新**。不应当出现数月乃至一年以上未检查过 Windows 更新以致系统进入停止支持状态的情况。

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Windows%20lifecycle.png?raw=true" width = "80%" />

---
### 不要提交 “不合逻辑” 或 “带有强烈主观色彩” 的建议

在浏览反馈中心的过程中，大家经常会看到诸如 **“请 Microsoft 收购 XXX 中国公司”** 或者 **“Windows 快点倒闭吧！”** 一类的建议反馈。我认为，无论是对 Microsoft 还是其他的 Windows 预览体验成员，这种反馈都是**没有价值**的。诚然，Windows 或其他 Microsoft 产品确实存在影响用户使用体验的问题，但预览体验成员应当保持**理性**与**客观**，针对问题开展细致的的调查与研究，并尽快向 Microsoft 进行报告，而不应当直接提出**不合逻辑**或**带有强烈主观色彩**的建议。

但是，对于 **“长久以来一直存在、用户们习以为常的现象”**，如果 Windows 预览体验成员认为这种现象不应存在的话，也是**应当提交反馈的**，因为这并不属于 “不合逻辑”。如同 Windows 更新功能，过去 Microsoft 不允许用户自行暂停 Windows 更新，系统经常会在用户的工作时段自动重启更新，对用户们的工作和生活造成了严重影响。虽然这是 **“长久以来一直存在”** 的问题，但是广大 Windows 预览体验成员们仍然坚持不懈的向 Microsoft 提交反馈与观点，最终使得 Microsoft 在 1903 版本 Windows 10 系统中添加了 “暂停更新” 的功能。

我认为，**“长久以来一直存在、用户们习以为常的现象” 的现象不一定是合理的，Windows 预览体验成员们更要针对此类问题进行思考与分析，要设身处地的站在用户角度看待问题。正如同中国伟大的文学家、思想家鲁迅先生在《狂人日记》中所写的一样，*“从来如此，便对么？”***

> 注：如果确实无法确认是否应当提交反馈的话，则一律提交。

## 四、如何获得有关 Windows 问题更详细的信息？

在本文档的上一部分，我们完整的讨论了有关 **“如何决定是否应当提交反馈”** 的问题，接下来，我们要解决掉第二个问题 —— **如何提交相比于 “高质量反馈” 更加详细的 Windows 问题反馈？**

Windows 预览体验成员们应当非常清楚，**我们向 Microsoft 提交的反馈中添加了越多详细信息，对问题的调查与处理工作就越有帮助**，这是理所应当的。既然我们已经决定向 Microsoft 提交反馈，不如就在这一基础之上对问题进行更加细致的研究，争取让反馈对工程师解决问题起到**最大化**的帮助。

第**五**章节是我个人总结的 [**“Windows 问题通用调查研究流程”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E4%BA%94windows-%E9%97%AE%E9%A2%98%E9%80%9A%E7%94%A8%E8%B0%83%E6%9F%A5%E7%A0%94%E7%A9%B6%E6%B5%81%E7%A8%8B)。经过了长时间的测试工作，我确认此流程能够有效达成 **“帮助用户获得有关 Windows 问题更详细的信息”** 的需求。我将会把完整的流程毫无保留的分享给预览体验成员们，希望可以对大家参与 Windows 测试工作起到帮助。

## 五、Windows 问题通用调查研究流程

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/General%20Investigation%20and%20Research%20Process.png?raw=true" width = "80%" />

> 点击 [此处](https://www.processon.com/view/link/5e6089cae4b03ecc75214492) 前往 ProcessOn 查看完整流程图。  
> 注：此流程图是我过去绘制的，内容比下方的文字流程要少一些，请大家以下方的文字说明为准。  
> 注 2：此流程图并没有按照规范标准进行绘制，同时也很简陋。我会尽快重新绘制此图，希望大家可以理解。

---
### 发现问题

编写并提交一个 Windows 问题反馈的首要前提自然是 **“我们需要先发现一个 Windows 问题”**。我认为，**作为一名 Windows 预览体验成员，不仅要在自己使用 Windows 10 设备的过程中发现问题，还要在日常的工作生活中主动的在社交媒体 (例如知乎、微博、贴吧等) 探寻其他 Windows 用户所发现并提供的问题。即使用户使用的是不雅词汇，我们也要理解并重视用户提供的任何 Windows 问题线索**。

---
### 记录至待办清单

一旦我们发现 (或在社交媒体中探寻到) 了任何 Windows 问题，我们的首要任务就是**记录**。根据我的个人经验，当我们 **“突然”** 发现问题或产生灵感时，如果不尽快将其加以记录，大概率会很快忘记。我认为，**将突然发现的问题或产生的灵感记录至待办清单可以有效的避免遗忘，同时也可以在一定程度上避免 “拖延症” 的出现**。

> 推荐使用 “Microsoft To Do” 作为首选的待办清单应用。Microsoft To Do，让您从工作到娱乐都保持专注。  
> 点击 [此处](https://todo.microsoft.com/tasks/) 以了解有关 Microsoft To Do 应用的详细信息。

如果我们是在**社交媒体中探寻到**了 Windows 问题线索，则应当依次执行下方的 [**“第 1 次测试”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E7%AC%AC-1-%E6%AC%A1%E6%B5%8B%E8%AF%95) 与 [**“第 2 次测试”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E7%AC%AC-2-%E6%AC%A1%E6%B5%8B%E8%AF%95)。而如果我们是在**自行使用 Windows 10 设备**时发现了问题的话，则仅需执行 [**“第 2 次测试”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E7%AC%AC-2-%E6%AC%A1%E6%B5%8B%E8%AF%95)。

---
### 第 1 次测试

如果我们是通过社交媒体获取到的其他用户有关 Windows 10 的问题报告的话，**不应当**立即向 Microsoft 提交反馈，因为这种由非 Windows 预览体验成员所提供的问题线索很可能是**带有强烈主观色彩的、并不准确**的。因此，我们首先需要执行 **“第 1 次测试”** 流程，确认用户所报告的问题是否属实存在。

**第 1 次测试要求：**

1. 使用**真机**，使用与用户**相同**版本的 Windows 系统，内部版本号**尽量保持一致** (如果用户没有提供 Windows 版本号的话，则使用 Windows 10 最新正式版本)。
2. 执行与用户**完全相同**的操作 (如果用户只是报告了问题，没有提供重现步骤的话，Windows 预览体验成员应当自行猜测用户可能执行的操作)，确认问题能否成功重现，**以判断问题是否属实存在**。预览体验成员尝试重现问题时的操作不能与用户实际执行的操作出现过大的偏差，否则将会影响测试结果的准确。
3. 如果用户使用的 Windows 系统版本**已停止支持**，则直接**结束通用调查研究流程**，无需再进行测试。

看到这里，很多 Windows 预览体验成员应该会有这样的想法 —— 我是一名预览体验成员，那么电脑中安装的自然是 Windows 预览体验版本，我没有办法去测试正式版本 Windows 10 系统中的问题。我认为，**每一位专业的 Windows 预览体验成员都应当拥有至少两台 Windows 10 设备，其中一台运行 Windows 10 Insider Preview Fast ring (或 Slow ring) 版本，另一台设备运行 Slow ring (或最新正式版本) Windows，这种双设备配置可以让预览体验成员更高效的为 Microsoft 做出贡献**。

如果第 1 次测试确认问题属实存在，则应当继续执行[**第 2 次测试**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E7%AC%AC-2-%E6%AC%A1%E6%B5%8B%E8%AF%95)流程。如果第 1 次测试无法成功重现问题，则应当执行 [**“问题无法成功重现”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E9%97%AE%E9%A2%98%E6%97%A0%E6%B3%95%E6%88%90%E5%8A%9F%E9%87%8D%E7%8E%B0) 流程。**不能跳过第 2 次测试流程而直接执行 “问题可以成功重现” 流程，这样是不严谨的**。

---
### 第 2 次测试

如果第 1 次测试确认用户报告的问题属实存在，或者问题是由 Windows 预览体验成员自行发现的话，都应当执行**第 2 次测试**。第 2 次测试是帮助我们 **“获得有关 Windows 问题更详细的信息”** 的最重要流程，可以让我们编写出更有价值的反馈，这一流程**不能跳过或敷衍执行**。

**第 2 次测试要求：**

1. 在**不同版本的 Windows 系统**中进行测试，确认问题是否仍然可以成功重现 (**例如**：如果问题是在 Windows 预览体验版本中发现的，那么测试一下在正式版本 Windows 中问题是否仍然存在)。
2. 执行与可行的重现步骤**类似**的操作，确认问题是否仍然可以成功重现 (**例如**：如果此问题是在使用浏览器输入文本时发现的，那么测试一下在本地 txt 文档中输入文本时问题是否仍然存在)。

在执行第 2 次测试的过程中，要尽可能的**多想、多做**，努力发掘有关 Windows 问题更详细的信息。对于发掘到的详细信息，要尽快**记录至待办清单**。第 2 次测试流程结束后，应当继续执行 [**“问题可以成功重现”**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E9%97%AE%E9%A2%98%E5%8F%AF%E4%BB%A5%E6%88%90%E5%8A%9F%E9%87%8D%E7%8E%B0) 流程。

---
### 问题无法成功重现

普通 Windows 用户在社交媒体中报告的问题通常是**不全面、不客观**的。即使在**第 1 次测试**流程中我们无法成功重现问题，也无需气馁，因为这是非常正常的。**问题无法成功重现通常是由于用户所提供的线索不足导致的，而并非是 Windows 预览体验成员们的工作出现了失误**。

如果问题确实无法重现，那么预览体验成员们要做的有以下三点：

1. **暂时终止测试工作**。
2. **继续保持对问题的跟踪**。
3. **考虑第三方应用程序干扰的可能性**。

我们要明确的是：**可以暂时终止测试，但是不能终止对问题的跟踪**。Windows 10 是一套庞大的计算机软件，无法保证所有新的功能在每一台设备上都可以正常使用，也无法保证所有的 Bug 在每一台设备上都可以成功重现。

我认为，**我们应当对无法重现的问题保持 14 天时间的跟踪，跟踪期间每 7 天再次执行一次测试，每次测试应当更换不同的 Windows 版本或操作步骤，以最大面积覆盖问题可能情况，这样可以提高问题成功重现的概率**。

如果问题**在跟踪期间成功重现**，或者**短时间内有多名 Windows 用户报告了同样的问题** (即使 Windows 预览体验成员的个人设备仍然未能成功重现问题)，应当针对此问题恢复执行[**第 2 次测试**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E7%AC%AC-2-%E6%AC%A1%E6%B5%8B%E8%AF%95)流程。同时，如果情况如**后者**的话，反馈应当**尽快**编写与提交，以便 Microsoft 在第一时间接收到相关情况并开展调查与处理。

我认为，**“短时间内有多位用户报告”** 的判定原则应当为 **“每 14 天发现 >= 5 名用户报告相同的 Windows 问题，并且他们使用的系统版本号相差较小”**。**“尽快”** 应当为 **“在 ‘短时间内有多位用户报告’ 情况判定成立的 24 小时向 Microsoft 提交反馈”**。

出现问题无法成功重现的情况时，也要考虑此问题是否是由于用户设备中安装的**第三方应用程序干扰**所导致的，必要时可以以 Windows 预览体验成员的身份 **(不能冒充 Microsoft 工程师或其他任何人)** 直接建议用户执行 [**干净启动**](https://support.microsoft.com/zh-cn/help/929135/how-to-perform-a-clean-boot-in-windows) 操作。

---
### 问题可以成功重现

当 Windows 问题在执行**第 2 次测试**流程获得了足够多的详细信息后，我们就可以进入**反馈的编写、校对与提交**流程了。编写反馈要严格按照上述的 [**高质量反馈**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E4%BA%8C%E4%BB%80%E4%B9%88%E6%98%AF%E9%AB%98%E8%B4%A8%E9%87%8F%E5%8F%8D%E9%A6%88) 要求，尽可能的做到**符合 “高质量反馈” 要求**。

反馈编写完毕后即可进入 **“校对”** 流程。通常情况下，需要校对的有以下 3 点：

1. 编写的反馈中是否存在**错字**或**语法使用不当**的现象？
2. 反馈的文本内容是否采用了**多段式**的分布？(**不建议将所有文字挤在一个段落**)
3. 反馈的整体语气是否做到了**平和而不偏激，尊重而不讽刺**？

校对结束后，我们即可通过 Windows 10 内置的 **Feedback Hub (反馈中心)** 应用提交反馈。在提交过程中，应当**选择合适的反馈类别，提供足够的截图与重现步骤**。至此，Windows 问题的调查与研究流程结束，我们只需要静待 Microsoft 做出响应即可。

> 注：Feedback Hub 应用仅适用于提交有关 **Windows 10 系统、Windows 应用、Windows Phone、HoloLens、开发人员平台、Windows 社区 / 论坛*等* 产品**的反馈。其余使用 Windows 10 系统执行其他的操作 (**例如查看 Microsoft 文档**) 时发现的问题，应当选择其他合适的反馈渠道 (**例如通过 GitHub 提交 Issue**)，而不应当全部在 Feedback Hub 应用中提交。

## 六、使用 Feedback Hub (反馈中心) 应用的注意事项

Feedback Hub (反馈中心) 应用曾经存在着数量较多的问题，这些问题可能会严重影响 Windows 预览体验成员们的反馈提交体验。**我在两年多时间的 Windows 反馈提交工作中，也针对反馈中心应用存在的问题编写过几条注意事项，这些注意事项可以最大程度的避免预览体验成员遭受这些异常问题的困扰**。目前，反馈中心应用曾经存在的异常问题已经基本修复完毕，但是我认为，将这些注意事项分享给大家是有必要的，它们仍然可以用于解决大多数预览体验成员关于反馈中心应用的**使用疑惑**。

1. 不建议在**连接至 VPN** 的状态下使用反馈中心，此时反馈中心会弹出 **“我们在连接时遇到问题”** 提示。在这种情况下，我们提交的反馈可能既不会上传至 Microsoft 服务器，也不会保存在本地端，大概率会出现**反馈丢失**的情况。

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Error.png?raw=true" width = "80%" />

> “我们在连接时遇到问题” 提示

2. 编写完毕反馈并点击了 **“提交”** 按钮后，建议在下方的 Thanks 页面**停留一分钟左右的时间**，不建议立即点击 **“继续使用反馈中心”** 按钮直接返回。如果快速点击了返回按钮的话，小概率会出现**反馈丢失**的情况。

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Thanks.png?raw=true" width = "80%" />

> Thanks 页面

3. 提交反馈时，如果在添加附件时选择了 **“重现问题”** 的话，会有一个 **“记录的诊断数据 - 数据尚在收集中。这可能需要一点时间”** 的过程。不建议在数据收集尚未完成时直接点击 **“提交”** 按钮，这可能会导致 Microsoft 无法收集到完整的诊断数据，不利于工程师针对问题开展调查与研究。**建议在 “数据尚在收集中” 的提示消失后再提交反馈**。

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Collecting.png?raw=true" width = "80%" />

> 数据尚在收集中。这可能需要一点时间。

<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/Collected.png?raw=true" width = "80%" />

> 数据已收集

4. 经常使用反馈中心的 Windows 预览体验成员们会注意到，经常会出现 **“在提交了一条反馈之后，‘我的反馈’ 中找不到刚刚提交的反馈”** 的现象，这是正常现象。反馈一般需要 **2 分钟**左右的时间才能在 **“我的反馈”** 中刷新出来，有时可能需要**数个小时**甚至**一天**的时间。因此，如果大家找不到自己刚刚提交的反馈的话，请不要着急，一般最多一天时间即可恢复正常。**同时，大家也不必立即重新提交反馈，避免出现同一反馈重复提交的情况**。

5. 在反馈中心内重现问题时，建议**完整的执行与记录从电脑桌面到出现问题时的所有步骤**，而不建议仅执行能让问题重现的操作步骤。例如，如果我们希望报告 **“设置”>“显示”** 中的某个按钮按下后没有响应的问题，在重现问题时，建议完整的执行以下操作：

    ***“在反馈中心中点击 ‘开始记录 ’ 按钮 ”>“启动开始菜单 ”>“点击 ‘齿轮 ’ 图标 ”>“点击 ‘显示 ’ 选项卡 ”>“点击无响应的按钮 ”>“返回反馈中心 ”>“点击 ‘停止记录 ’ 按钮 ”***。

    而**不建议**仅仅记录下面这个**独立**的操作：
	
    ***“在反馈中心中点击 ‘开始记录 ’ 按钮 ”>“点击无响应的按钮 ”>“返回反馈中心 ”>“点击 ‘停止记录 ’ 按钮 ”***。
 
    前者可以让 Microsoft 接收到更加完整的诊断数据。

6. 善用 **“将此项设为高优先级”** 选择框。不建议各位 Windows 预览体验成员**滥用**这个优先级选择框 (即提交任何反馈时都将其勾选)，但是在需要的时候，我们应当**毫不犹豫的将其勾选**。一般情况下，以下 4 种 Windows 问题是应当勾选 **“将此项设为高优先级”** 选择框的：

	- **常用 Windows 功能** (例如 Windows 更新、设置、开始菜单、操作中心等) **无法正常使用**。
	- **Microsoft 旗下其他应用程序** (例如 OneDrive、Office) 在 Windows 系统中**无法正常使用**。
	- 电脑无法正常开机、性能受到严重影响、系统冻结或无响应、大量应用无法启动等**严重 Windows 故障**。
	- 其他**严重影响预览体验成员使用体验**的 Windows 系统问题 (大家可以自行斟酌)。
	
<img src="https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/HighPriority.png?raw=true" width = "80%" />

> 将此项设为高优先级

---
[**回到顶部**](https://github.com/Lingggao/Microsoft-Insider-Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E5%BD%93%E5%8F%91%E7%8E%B0-windows-%E9%97%AE%E9%A2%98%E6%97%B6%E8%AF%A5%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86)
