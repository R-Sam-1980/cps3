# CPS3 街机游戏兼容性列表

以 Widows 版的 RetroArch 为例，支持 CPS3 街机游戏的核心不止一个：
- Arcade (FB Alpha 2012 CPS-3)
- Arcade (FB Alpha 2012)
- Arcade (FinalBurn Neo)
- Arcade (MAME...) 系列核心

1G1R 是 one Game one ROM 的缩写，意思是一个游戏只选取一个最佳版本的 ROM 文件。

下面这份 CPS3 街机游戏列表，是根据 FBNeo - Arcade Games.rdb 数据库里 ROM 文件描述，按照 1G1R 的策略收集整理的，每个 ROM 都支持以下三种核心：
1. Arcade (FB Alpha 2012 CPS-3)
2. Arcade (FB Alpha 2012)
3. Arcade (FinalBurn Neo)

序号 | ROM 文件 | CRC32 | 依赖于 | 游戏名称
--- | --- | --- | --- | ---
1 | jojobaner1.zip | DBE72E53 | jojoba.zip | J - JOJO的奇妙冒险2 未来遗产
2 | jojon.zip | D1FB9FFE | jojo.zip | J - JOJO的奇妙冒险1
3 | redearth.zip | F357FAC2 | | C - 赤色大地
4 | sfiii2.zip | EF7FA548 | | J - 街头霸王3.2 巨型打击
5 | sfiii3.zip | 36056B5E | | J - 街头霸王3.3 未来战斗
6 | sfiiin.zip | 9C57FA04 | sfiii.zip | J - 街头霸王3.1 新纪元

**建议优先使用 Arcade (FinalBurn Neo) 核心加载游戏。**

游戏手柄和街机摇杆的玩家，可以参考下面的做法，避免更换控制器时来回修改按键映射的麻烦：
- 使用游戏手柄的时候，选择 Arcade (FinalBurn Neo) 核心，采用游戏手柄的按键映射方案；
- 使用街机摇杆的时候，选择 Arcade (FB Alpha 2012) 核心，采用街机摇杆的按键映射方案。
