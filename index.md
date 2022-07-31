---
layout: default
---
# Abstract
Controllable speech synthesis has made great progresses over the last decades. State-of-the-art systems can provide flexible interfaces for configuring the style of generated speech for targeted audience. However, for a specific audience group, e.g., the older adults, the selection of style that is favored by the group using the available configuration interfaces still needs to be investigated. Two main questions of such a style selection are (i) how to provide various options for the targeted audience to pick; and (ii) how to effectively obtain the opinions from the targeted audience. Since these two questions are highly correlated which makes it difficult to solve them separately, we propose a holistic framework to consider these two questions together by involving the targeted audience in an iterative loop. We demonstrate by experimental results that the proposed framework can successfully select a better speaker style for the older adults than the neural default setting. Analysis results show that the selected style has slower speaking rate, which coincides with previous auditory perception study results. 

# Proposed HILvoice Framework
<img src="./wavs/fig2.pdf" width="60%">

# Preference tests

|   |Cantonese text|$\lambda_0$|$\lambda_2(explicit)$|$\lambda_2(implicit)$|
|:--|:----------------------------------------------|:------|:------|:------|
|1|冇#1大块#1横条石#1压镇#3，墓碑#1可以#1讲系#1一挖#1就倒#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|2|例如#1宴會#3、音樂#1演奏會#3、受勳#1儀式咁#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|3|希望#1为啲#1新书#1宣传#1速销#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|4|包括#1蝶式#3、背泳#3、蛙泳式#3、自由式#1四種#1泳式#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|5|劉千石#2響立法會#1政改方案#3投下#1棄權票#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|6|呢的#1古本#3比較#1現在#1呢三個#1流通#1版本#3多咗#1或#1小咗#1一的#1經卷#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|7|佢確立#2揸住#1朱印#1狀者#3先准做#1貿易嘅#1朱印船#1制度#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|8|荣华#1东街#3、旧豆栏#3、拱日门#3、鸡栏#1之庙#4；|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|9|亦有啲#1卡巴#2係以#1薯條#1取代#1土耳其#1麵包#1當餸#1嚟食嘅#4；|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|10|透過#1唔同心法#3令#1敵人#1勁氣#1落空#3又或#3將之#1引乜#4，|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|11|小葉#1嚟到#1坐咗喺#1劃畫#1老師#1後面#1個位#1預備#1郁手#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|12|家下#1拍烏蠅#3未必要#1拍死佢#1咁暴力#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|13|严防#1极端#1分子#3威胁#1负责#1选务#1官员#1安全#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|14|计划嘅#1路线#1分为#1三大#1部份#4。|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|
|15|水裏#1便嘅#1鹽#2就#1搞到#1鋼筋#2好快#1生鏽#1變弱#4，|<audio controls><source src="./wavs/0-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2x-01.wav" type="audio/wav"></audio>|<audio controls><source src="./wavs/2y-01.wav" type="audio/wav"></audio>|

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ISCSLP2022/HILvoice/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ISCSLP2022/HILvoice/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
