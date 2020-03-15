# 当发现 Windows 异常问题时，该怎样去做？

[**English Documentation (英文版本)**](https://github.com/Lingggao/Microsoft_Insider_Program/tree/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue)

## 简介

Microsoft 为产品爱好者们提供 Windows 预览体验计划服务的目的是**获取更多关于 “用户对 Windows 预览体验计划服务的喜好以及期望进行的更改” 的信息**。用户通过注册 Windows 预览体验计划获得了使用最新版本 Windows、参与系统测试的**权利**，自然也应当履行向 Microsoft 提供反馈的**义务**。

综上所述，我认为，**当一个 Windows 预览体验成员只是 “静默” 的使用着 Windows 预览体验版本，而不向 Microsoft 提供任何反馈的话，他是基本没有价值的。只有当越来越多数量的用户被 Windows 预览体验计划所吸引，进而向 Microsoft 提供越来越多数量的反馈，帮助 Microsoft 尽全力优化 Windows，使得 Windows 预览体验计划吸引越来越多的产品爱好者，形成了这样的一个良性循环时，Windows 预览体验计划才能真正的发挥 “打造 Windows 10 未来的演变” 的根本目的。**

虽然说向 Microsoft 提供尽可能多的数量的反馈是每个 Windows 预览体验成员的义务，但是我认为，每位预览体验成员都应当牢记：**我们应当提供高质量的反馈，同时尽量避免提供低质量的反馈**。Microsoft 每天都会接到**数以十万计**的用户反馈，为了尽可能的降低工程师们的工作量，转而将精力用于解决问题，我们努力提高反馈的质量是非常有必要的。那么，我们就需要面对一个亟待处理的问题 —— **如何切实提高反馈的质量，避免提供低质量、不完整甚至是毫无作用的反馈**？

以下是我关于这个问题的**个人见解**，希望可以帮助到各位朋友们：

## 什么是高质量反馈？

要想做到为 Microsoft 提供高质量的 Windows 反馈，我们首先应当对 **“高质量”** 有一个初步的评判标准。我认为，一个高质量的 Windows 反馈应当至少包含以下几点信息：

### 问题反馈
1. 首先用**一句话**简明的描述发生了什么错误。
2. **正常情况下**应当是什么情况？
3. **目前**出现了什么错误情况？
4. 提供**重现**这一错误的操作步骤。
5. 提供 **Windows 版本号**信息。
6. **[可选]** 提供**设备品牌与详细型号** (品牌机) 或**主板型号** (组装机)。
7. **[可选]** 提供出现这一错误时的**屏幕截图**。
8. **[可选]** 重启设备、使用任务管理器结束相关进程等**常规修复操作**是否可以暂时的解决这一错误？
9. **[可以没有，但是推荐有]** 使用**感谢词**作为反馈的结束语。

**举例 1：**  

Build 19564_OneDrive 突然无法正常使用，同时任务栏中的 “云朵” 形状图标消失。

更新至 Build 19564 版本后，OneDrive 突然无法正常使用。点击 OneDrive 应用后，无法弹出文件夹，同时任务栏中的 “云朵” 形状图标消失。与此同时，任务管理器中 “Microsoft OneDrive (32 位)” 进程持续占用 15% 左右的 CPU，导致设备风扇一直处于运转状态。请调查此问题。Thanks very much.

> 这个例子选自于我个人提交的 Windows 反馈。

**举例 2：**

Build 19559_按 “Windows 徽标键+V” 快捷键启动 “剪贴板历史记录” 并将其关闭后，无法继续输入文字。

在 Build 19559 版本中，按下 “Windows 徽标键+V” 快捷键启动 “剪贴板历史记录” 后，如果不粘贴任何内容并直接将其关闭，将无法继续使用键盘输入文字。重启设备可以暂时解决这一问题。请调查此问题。Thanks very much.

> 这个例子同样选自于我个人提交的 Windows 反馈。

### 建议反馈
1. XXX
2. //To Do

[**回到顶部**](https://github.com/Lingggao/Microsoft_Insider_Program/blob/master/Microsoft%20Windows%20Insider%20Program/What%20should%20we%20do%20when%20find%20a%20Windows%20issue/README_cn.md#%E5%BD%93%E5%8F%91%E7%8E%B0-windows-%E5%BC%82%E5%B8%B8%E9%97%AE%E9%A2%98%E6%97%B6%E8%AF%A5%E6%80%8E%E6%A0%B7%E5%8E%BB%E5%81%9A)
