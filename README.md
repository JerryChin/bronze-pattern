本项目目的是将上海博物馆青铜馆所展示的青铜器纹饰照相拷贝转换为数字版本（此处特指 SVG 矢量格式），以便使其适用于计算机 UI/UX 场合。

本项目已从网络上收集到上海博物馆青铜馆所展示育成期、鼎盛期、转变期、更新期青铜器纹饰数字图像，图像来源于 http://blog.sina.com.cn/s/blog_5376a2770102vjwe.html，尚未取得授权。

项目组织结构如下：

- /images/original 从网络收集而来的原始图片，一共四张图片，分别为育成期、鼎盛期、转变期、更新期青铜器纹饰数字图像
- /images/ages/incubating 育成期纹饰切图
- /images/ages/golden 鼎盛期纹饰切图
- /images/ages/transiting 转变期纹饰切图
- /images/ages/updating 更新期纹饰切图

| 时期           | 分类 | 编号  | 切图进度 | 矢量化进度 |
|----------------|---------------|----------------|-----------|-----------|
| 育成期 | 兽面纹  | I-AF-L1 |  [ ] ![Alt text](images/ages/incubating/I-AF-L1.png?raw=true "Title")| - [ ] |

编号方式如下：

{AGE}-{TYPE_OF_PATTERN}-{LEFT_COLUMN}/{RIGHT_COLUMN}{NO}

AGE 为各时期英语大写首字母：

- I - 育成期 Incubating Age
- G - 鼎盛期 Golden Age
- T - 转变期 Transiting Age
- U - 更新期 Updating Age

TYPE_OF_PATTERN 为纹饰分类名称英语的大写首字母：

- AF - 兽面纹 Animal Face Pattern
- DP - 龙纹 Dragon Pattern
- GP - 几何纹 Geometry Pattern
- FP - 火纹 Fire Pattern
- PP - 凤鸟纹 Phoenix  Pattern
- BP - 变形兽体纹 Bianxing Animal Pattern (Cannnot find proper translation for this, use pinyin instead.)
- SP - 鳞纹 Scale Pattern
- LP - 画像纹 Landscape Pattern
- AP - 动物纹 Animal Pattern

LEFT_COLUMN/RIGHT_COLUMN 为左栏或者右栏

- L - 左栏
- R - 右栏

只有一栏可以为空

{NO} 为编号，从 1 开始递增
