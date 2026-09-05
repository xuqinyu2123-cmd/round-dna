[V11 更新]
- 封面重新排版，弱化“大字压满屏”，改成更完整的电竞产品首屏
- 主视觉直接使用真实游戏地图场景图，战术标记只做轻量叠加
- 答题页右侧主图改为真实地图画面，下面两个小卡继续给站位/路线参考
- 官方稳定地图图源优先：Inferno、Nuke、Ancient、Dust II、Anubis、Train；其他地图使用官方 CS 视觉作为兼容回退
- 手机端继续保留一列式布局

[V10 更新]
- 封面改为更有层次感的 cinematic map 风格，视觉更完整、更吸引人
- 答题右侧地图面板进一步美化，强调“地图画面 + 站位 + 路线 + 道具 + 残局处理”
- 优化问题区排版与信息层级，整体更像成熟网页产品
- 继续保留 GitHub Pages 直接部署结构

[V9 更新]
- 继续弱化旧背景图思路，主视觉改成更接近雷达原图观感的地图板块
- 每张地图使用更细的区域形状、点位名称、T/CT 站位、推进路线、烟雾与 BOMB 点
- 题目页面强化“地图雷达 + 已知信息 + 判断重点”结构
- 保留 CS2 饰品元素，但主次关系改为：地图与残局判断优先

[V8 更新]
- 重做为更专业的 top-down 战术板风格，不再使用旧宣传背景图当残局底图
- 右侧主视觉改为地图俯视布局，直接标出 T / CT 站位、推进路线、烟雾与 BOMB 点
- 题目区改为“问题 + 已知信息 + 判断重点”结构，更适合残局处理测试
- 收紧杂乱元素，整体布局更偏职业复盘面板

[V7 更新]
- 主视觉与答题页加入“地图原图 + 战术叠层图”双层显示，残局图片更细节化
- 新增人物站位标记、烟雾点、BOMB 点、推进路线，残局信息更直观
- 首页与答题页新增饰品卡片，提升整体 CS2 内容密度
- 继续保留地图情境题，不再只有抽象题干

[V6 更新]
- 首页封面重做：主视觉 + 3 张地图情境卡，避免右侧空和构图不完整
- 答题页强化地图特点：Mirage / Inferno / Nuke / Ancient / Dust2 / Anubis / Vertigo / Train
- 每题加入地图情境、已知站位、处理重点，不再只有抽象题干
- 右侧主图与缩略图改成地图战术视图，更贴近“人物站位 / 残局思路 / 某点位怎么打”

[V5 更新]
- 答题页新增 IN-GAME HUD 布局
- 新增更多 CS 本体场景图（主图 + 两张额外图）
- 新增雷达/Round Intel/武器栏/Kill Feed

ROUND//DNA V4 · PEAK ERA EDITION

部署方法（与之前 AEVEMORA 一样）：
1. 新建 GitHub 仓库，建议 round-dna。
2. 把本压缩包解压后的所有文件上传到仓库根目录（index.html 必须直接在根目录）。
3. GitHub → Settings → Pages → Build and deployment → Deploy from a branch。
4. Branch 选 main，目录选 /(root)，Save。
5. 等待 GitHub Pages 发布，访问 https://你的用户名.github.io/round-dna/

V4 重点：
- 20 位选手全部绑定“代表巅峰期”年份、说明和对应时期海报。
- 结果页优先展示 Peak Era 海报，不再使用随机/近期肖像当主海报。
- 首页缩短并重排，CTA 更靠前；手机端首屏不再被大图拖长。
- 答题页以题目/选项为核心，手机端场景图降为辅助横幅。
- 结果页改成巅峰海报 + Post Match Report 双栏，手机端自动纵向。
- Top 5 与选手池都显示对应 Peak Year。

巅峰期选择口径：优先年度最高世界排名，其次结合 Major/MVP、该时期代表性和角色影响力。对于 karrigan/apEX 这类 IGL，重点参考冠军与指挥影响力，而不是个人年度 Top20。

图片与版权：
- 部分年度巅峰海报来自 HLTV 年度 Top 20 文章图片。
- karrigan/apEX 使用 Wikimedia Commons 对应 Major 时期照片。
- Counter-Strike 2 场景视觉来自 Steam/Counter-Strike 2 官方公开页面。
- 如果项目准备商业化，请在正式上线前逐张确认第三方图片再发布/商用的许可范围；当前包更适合作为产品原型与内部测试。

提示：外部海报是在线加载的，因此测试“巅峰海报”时需要网络。若个别网络环境无法访问第三方图片，程序会尝试对应选手肖像作为兜底。

20 位选手的代表巅峰期：
ZywOo — 2023 · HLTV #1 / Paris Major MVP
donk — 2024 · HLTV #1
ropz — 2023 · HLTV #3
m0NESY — 2024 · HLTV #2
sh1ro — 2022 · HLTV #3
NiKo — 2017 · HLTV #2
XANTARES — 2025 · HLTV #14（生涯最高）
Twistzz — 2019 · HLTV #9 / Liquid Grand Slam era
KSCERATO — 2025 · HLTV #9（追平生涯最高，冠军赛季）
frozen — 2025 · HLTV #8（生涯最高）
flameZ — 2025 · HLTV #7 / Vitality dominance
YEKINDAR — 2021 · HLTV #8
device — 2018 · HLTV #2 / 7 MVP season
s1mple — 2021 · HLTV #1 / Major breakthrough
karrigan — 2022 · PGL Major Antwerp champion / IGL peak
apEX — 2023 · BLAST Paris Major champion / IGL peak
FalleN — 2016 · HLTV #2
b1t — 2021 · HLTV #9 / rookie Major era
jL — 2024 · HLTV #5 / big-match peak
rain — 2017 · HLTV #4 / individual rifling peak
