# 句子：让读者读一遍就懂

这一页的骨架来自 Joseph M. Williams 的 *Style: Lessons in Clarity and Grace*，以及 George Gopen 和 Judith Swan 1990 年发表在 *American Scientist* 上的 “The Science of Scientific Writing”。它们讲的是英文，但核心观察在中文里同样成立：读者读句子时，在找**谁**做了**什么**，并期待新东西出现在句尾。中文特有的问题见 [languages/chinese.md](../languages/chinese.md)。

## 1. 让角色做主语，动作做动词

读者心里的故事是“谁做了什么”。句子的语法主语恰好是那个“谁”、谓语恰好是那个“做”时，读起来最省力。动作被藏进名词里（Williams 叫 nominalization，Helen Sword 叫它 zombie nouns），句子就开始发僵。

> The implementation of the new review process resulted in a reduction in errors.
> → After we introduced the new review process, errors fell.

> 通过本次会议的召开，使大家对项目进展有了进一步的了解。
> → 开完这次会，大家更清楚项目进展到哪了。

> 对系统性能进行了全面的优化。
> → 我们把首页加载从 4 秒压到了 1.5 秒。（如果你知道具体做了什么）

第一个例子顺带提醒：改成主动句时，因果强度别跟着变。“resulted in” 本来就在声称因果；如果原文只知道先后，改写成 “errors fell after…” 比 “the process cut errors” 更忠实。

名词化不全是坏事。它能把前文的一个动作打包成后文的话题（“这次迁移花了三个月。迁移的难点在于……”），也是专业概念的正常形态（“通货膨胀”“随机化”）。问题在于它被拿来制造“正式感”。

## 2. 旧信息在前，新信息在后

一句话开头放读者已经知道的（上一句提到的、常识里的），结尾放新的、要强调的。Gopen 和 Swan 把句首叫 topic position，句尾叫 stress position：读者自然会把重音放在句末。

> 弱：A 15% drop in churn followed the redesign of the onboarding flow last quarter.
> 强（如果上一句在谈改版）：Last quarter we redesigned the onboarding flow. Churn dropped 15% afterward.

中文同理，句末是落点：

> “贵是这个方案最大的问题。”——强调落在“问题”，像是在给问题定性。
> “这个方案最大的问题是贵。”——强调落在“贵”，读者记住的是贵。

想让读者记住什么，就把它放到句尾。

## 3. 主干先到，修饰后挂

主语和谓语离得太远，读者得一直把主语攥在手里。先给主干，再挂修饰。

> The committee, which had spent most of the meeting debating the budget and raising concerns about the vendor's track record, approved the plan.
> → The committee approved the plan after a long debate about the budget and the vendor's track record.

中文的长定语是同一种病：

> 由市场部牵头、联合产品和销售两个部门、历时三个月完成的用户调研报告已经发布。
> → 用户调研报告已经发布。这份报告由市场部牵头，产品和销售一起参与，做了三个月。

## 4. 一句一个重心

一句话里塞了三件同样重要的事，读者不知道该记哪件。拆开，或者分出主次：主要的放主句，次要的放从句或下一句。

## 5. 用有力的动词

| 弱 | 强 |
|---|---|
| 做出决定 / make a decision | 决定 / decide |
| 进行讨论 / have a discussion about | 讨论 / discuss |
| 起到了重要的推动作用 | 推动了 |
| 存在一定的问题 / there are issues with | （说出问题本身） |
| is able to | can |
| in order to | to |

“进行”“作出”“加以”在公文和法规里有时是惯例，照规矩用。在其他地方，它们多半是在给动词垫一层棉花。

## 6. 管好限定词的范围

“只”“都”“仅”“only”“just”“not…all”放在哪，意思就跟着变。

> We only tested the API.（只做了测试这一件事？）
> We tested only the API.（测试范围只有 API。）

> 所有用户都没有收到通知。（一个都没收到）
> 不是所有用户都收到了通知。（有人收到了，有人没有）

润色时最容易无意中改坏的，就是这类词。

## 7. 平行结构

并列的东西用相同的语法形式，读者能一眼看出它们是同类。

> We need to hire two engineers, the budget approval, and finishing the migration.
> → We need to hire two engineers, get the budget approved, and finish the migration.

反过来，不要为了节奏把不并列的东西硬排成排比。那是腔。

## 8. 能正说就别反说

“不是不重要”“not uncommon”“并非没有可能”让读者多绕一道弯。除非这层迂回本身就是你想要的语气（克制、反讽、谨慎的让步），否则直接说是什么。

## 9. 长句可以很清楚

长句不是罪。问题在于读者在句子里迷路。好的长句有几个特征：主干早出现；从句按逻辑或时间顺序排开；每个插入成分都短；读到句末，读者知道自己走到了哪。

> If the migration finishes before the holiday freeze, we can launch in December; if it doesn't, we'll wait until the freeze lifts in mid-January rather than ship on a partial dataset.

这句 40 多个词，但每一段都在推进同一个决策，读者不会迷路。

## 10. 短句的位置

短句用来下判断、拐弯、制造停顿。一段铺陈之后接一个短句，读者会感到分量：

> 我们试了三种缓存策略，换了两次数据库，加了一倍的服务器。延迟没变。

连续的短句会失去这种力量，变成电报。

## 11. 抽象词什么时候没问题

当它命名了一个读者需要的概念，并且后文会用到它时，抽象词就是工具。“技术债”“边际成本”“叙事视角”都是好词。抽象词变成雾，是因为它们代替了本该说出的具体东西：“优化体验”“提升效能”“相关问题”。

## 12. 删掉重复的意思

| 赘 | 改 |
|---|---|
| 过去的历史、未来的计划 | 历史、计划 |
| 完全彻底地解决 | 解决（或者说清解决到什么程度） |
| 目前正在进行中 | 正在 |
| end result, past experience, free gift | result, experience, gift |
| currently in the process of | now |
| due to the fact that | because |

## 修改一个句子的顺序

1. 找出谁是角色，什么是动作。
2. 让角色做主语，动作做动词。
3. 把读者已知的放前，新的放后。
4. 检查限定词和否定有没有被改坏。
5. 读出来。
