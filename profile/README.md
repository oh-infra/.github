<p align="center">
  <img src="https://raw.githubusercontent.com/oh-infra/.github/main/profile/assets/banner.svg" alt="Oh My Infra — Learn the system. Build it together." width="100%" />
</p>

<h1 align="center">Oh My Infra · 开源学习与实践计划</h1>

<p align="center">
  <strong>贯穿 CS Infra 与 AI Infra，在实践中理解系统，在协作中成为贡献者。</strong>
</p>

<p align="center">全年持续开放 · 按个人进度学习 · 人与人协作</p>

<p align="center">
  <a href="https://github.com/oh-infra/oh-my-infra"><strong>学习与实践</strong></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/oh-infra/blogs"><strong>技术博客</strong></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/oh-infra/website"><strong>网站建设</strong></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/oh-infra/oh-my-infra/issues"><strong>参与讨论</strong></a>
</p>

---

Oh My Infra 由[格维开源社区](https://github.com/gevico)发起，延续 [QEMU 训练营](https://github.com/qemu-camp)的课程与实验经验，面向现代计算基础设施建设长期开放的学习与实践路径。我们希望帮助初学者掌握系统开发的方法，建立参与开源的信心，并在共同解决问题的过程中结识伙伴、建立信任，持续参与社区和项目建设。

**筹备中 · 计划于 2027 年启动。** 课程、实验、项目任务与参与规则正在建设，正式开放信息将在本组织发布。

## 从这里开始

<table width="100%">
  <tr>
    <td width="34%" valign="top">
      <h3><a href="https://github.com/oh-infra/oh-my-infra">01 / 学习与实践</a></h3>
      <p>课程、讲义、实验与项目任务的建设入口。围绕真实系统问题，学习构建、调试、验证与提交代码的方法。</p>
      <a href="https://github.com/oh-infra/oh-my-infra"><strong>查看主仓库 →</strong></a>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/oh-infra/blogs">02 / 技术博客</a></h3>
      <p>实验报告与技术博客的建设入口。记录实现过程、调试依据和自己的理解，让实践经验可以交流和传承。</p>
      <a href="https://github.com/oh-infra/blogs"><strong>查看博客仓库 →</strong></a>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/oh-infra/website">03 / 网站建设</a></h3>
      <p>学习与实践网站的建设入口。共同完善内容展示与参与体验，让学习资料和社区成果更容易被找到。</p>
      <a href="https://github.com/oh-infra/website"><strong>查看网站仓库 →</strong></a>
    </td>
  </tr>
</table>

## 沿着一个系统问题深入

一次计算任务如何经过编译、运行时、操作系统与设备，最终在硬件上执行？我们从这样的具体问题出发，把 CS Infra 与 AI Infra 放在同一条学习实践路径中，理解各个部分的接口、依赖与协作方式。

| 观察系统的角度 | 学习与实践内容 |
| :--- | :--- |
| **构建与调试** | Linux 开发环境、C / Rust、Git、编译链接、调试工具与测试方法 |
| **程序与系统** | 操作系统、内存管理、设备驱动、编译器与运行时 |
| **设备与计算** | CPU / GPU、异构计算、AI 运行时、任务提交与数据传输 |
| **模拟与验证** | 虚拟化、QEMU、gem5、设备建模、联合仿真与性能分析 |

具体课程和实验以主仓库发布的内容为准。学习者可以按照自己的节奏推进，围绕选定方向积累实践成果。

## 从自主学习进入项目协作

整个计划全年不间断运行，并持续跨年度开展。参与者从自己加入时开始，经过**自主学习阶段**与**项目阶段**，到完成项目结束，走完自己的学习实践周期。加入时间和推进速度可以各不相同。

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>01 / 自主学习阶段</h3>
      <p>按照个人进度学习课程与讲义，完成实验、提交代码，并公开发表实验报告或技术博客。在学习过程中参与讨论，与社区成员交流问题和经验。</p>
      <p><strong>进阶要求：</strong>实验与总结均达标，经过人工提交审查、方向面试和综合评估。</p>
    </td>
    <td width="50%" valign="top">
      <h3>02 / 项目阶段</h3>
      <p>根据学习方向与维护者共同确定项目任务，参与真实开源协作，完成设计、实现、测试和文档，通过项目约定的验收要求。</p>
      <p><strong>完成周期：</strong>项目完成后结束本次学习实践周期，也欢迎继续贡献、分享经验和帮助新的参与者。</p>
    </td>
  </tr>
</table>

进入项目阶段前，**实验完成情况**与**实验报告或技术博客**都需要达标：

- **实验完成情况**：实现要求的功能，达到规定分数，通过 CI 验证；由社区成员人工检查 commit、代码与实现过程。
- **实验报告或技术博客**：公开说明实验目标、实现思路、问题定位、验证结果与自己的理解，并能够解释关键技术选择。

两项达标后，社区根据学习方向和实验内容安排面试，结合提交记录、实践过程及社区参与情况进行综合评估。面试通过技术交流确认参与者对成果的理解，以及独立分析和解决问题的能力。

社区参与情况包括有效提问、技术讨论、帮助他人、问题复现和代码审查等，是综合评估的参考依据。进入项目阶段后，参与者与维护者共同确定任务，完成设计、实现、测试和文档，参与真实开源协作。

## 持续学习，定期相聚

社区通过学习计划启动仪式、阶段性交流会议和项目分享，让不同进度的参与者有机会相识、讨论和互相支持。每年的总结报告记录课程建设、学习实践与项目成果，也为后续参与者留下可以参考的经验。

这些共同活动贯穿长期运行的计划。参与者按照自己的学习和项目进度完成个人周期，具体会议安排与年度报告将在组织中发布。

## 与人一起学习，与人一起贡献

我们重视学习者、贡献者与维护者之间的直接交流。清楚描述一个问题、认真回应一次审查、分享一段调试经验，都能帮助彼此建立信任。计划采用长期运行、灵活加入与退出的方式，让参与者按照自己的时间持续学习和贡献。

**AI Agent 可以辅助学习和开发，参与者需要理解、解释并对自己的成果负责。** 技术判断、面试交流和社区协作由参与者本人完成。

欢迎从[主仓库的 Issue](https://github.com/oh-infra/oh-my-infra/issues)开始交流，提出课程与实验建议、分享学习中的问题，或者认领公开的建设任务。技术写作和网站建设也欢迎通过对应仓库的 Issue 与 Pull Request 参与。

---

<p align="center">
  <strong>Learn the system. Build it together.</strong><br />
  <sub>理解系统，一起建设。</sub>
</p>

<p align="center">
  <a href="https://github.com/gevico">格维开源社区</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/qemu-camp">QEMU 训练营</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/oh-infra?tab=repositories">全部仓库</a>
</p>
