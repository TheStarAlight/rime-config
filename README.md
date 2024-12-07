# RIME 配置文件

本人正在使用的rime (Windows)配置文件，仅包含Clover全拼方案（[clover-pinyin](https://github.com/fkxxyz/rime-cloverpinyin)及[rime-pure](https://github.com/SivanLaai/rime-pure)）。

## 实现功能

- LaTeX符号输入（以`\`触发）（参考自[rime_latex](https://github.com/shenlebantongying/rime_latex)）
- 拆字（以`u`触发，挂载反查模式）（参考自[rime-radical-pinyin](https://github.com/mirtlecn/rime-radical-pinyin)）
- 输入`date`,`time`可获得当前日期和时间（利用`rime.lua`实现）

## 词库

- Clover基本词典（clover.base）
- 华宇输入法词库（huayu）（取自[rime-pure](https://github.com/SivanLaai/rime-pure)）
- THUOCL词库（目前仅启用部分词库，可在`clover.dict.yaml`中修改）
