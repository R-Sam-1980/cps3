# CPS3 街机游戏整理

1G1R 是 one Game one ROM 的缩写，意思是一个游戏只选取一个最佳版本的 ROM 文件。

下面表格里的 ROM 文件，是按照 1G1R 的策略筛选整理的，请使用 **Arcade (FB Alpha 2012 CPS-3)** 核心加载这些游戏：

序号 | ROM 文件 | CRC32 | 英文名 | 中文名
--- | --- | --- | --- | ---
1 | jojo.zip | 09565881 | JoJo's Venture | JOJO的奇妙冒险1
2 | jojoba.zip | 03A8E3D2 | JoJo's Bizarre Adventure - Heritage for the Future | JOJO的奇妙冒险2 未来遗产
3 | redearth.zip | F357FAC2 | Red Earth | 赤色大地
4 | sfiii.zip | 1F8CC35D | Street Fighter III - New Generation | 街头霸王3.1 新纪元
5 | sfiii2.zip | EF7FA548 | Street Fighter III 2nd Impact - Giant Attack | 街头霸王3.2 巨型打击
6 | sfiii3.zip | 36056B5E | Street Fighter III 3rd Strike - Fight for the Future | 街头霸王3.3 未来战斗

Wii 端最新版的 RetroArch 存在较明显的兼容性和稳定性问题，不过在加载以上 ROM 文件时，如果使用最新（1.22.2）版 RetroArch 里的核心文件（fbalpha2012_cps3_libretro_wii.dol），游戏流畅度会有明显改善。

首次加载游戏时，Arcade (FB Alpha 2012 CPS-3) 核心需要额外耗时，在 SD 卡的 retroarch\system\cache 目录里生成缓存文件，所有缓存文件的总大小约 460 MB。缓存文件生成完毕之后，后续每次加载游戏的耗时都会显著缩短。

Wii 虽比 CPS3 晚面世近 10 年，但受限于主机机能和模拟器当前的优化程度，仍无法做到“完美运行”。Wii 端的 RetroArch 可以借助跳帧（Frameskip）换取游戏流畅度，因此，如果只是想尝鲜，Wii 是可行的选择，但如果追求完整体验，建议还是选择性能更强的设备吧。
