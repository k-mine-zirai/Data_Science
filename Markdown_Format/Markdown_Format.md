# 基本構文
|名称              |記法                 |備考                  |
|------------------|--------------------|----------------------| 
|ヘッダー（見出し）      |  `# 文字列 `        |#の数で6段階設定できる     |
|太字               |  `**文字列** `      | `__ __ `でも可         |
|斜体               |  `*文字列* `        | `_ _ `でも可           |
|斜体               |  `~~文字列~~ `      |                      |
|全体太字            |  `***文字列*** `    |                      |
|テキストの引用        |  `> `              |                      |
|コードの引用          |  ｀コード｀        　 | 半角のバッククォート       |
|コード複数の引用       |  ` ```コード ``` `   |                      |
|コード複数の引用(強調)  |  ` ```python コード ``` `| 言語ごとに文法を強調できる |
|リンク               |  `[文字列](URL)`    |                      |
|箇条書き（記号）        |  `- 文字列 `       | 入れ子の時は上位の文字のすぐ下に来るようにスペースを調節する   |
|箇条書き(番号)        |  `1. 文字列 `      | 入れ子は↑と同じ        |
|改行                |  `半角スペース2つ または<br>`|         |


# 表の作り方
```
|no.1 |no.2 |no.3 |
| :----  | :----: | ----:   | 
|:左寄せ | :中央: | 右寄せ: |
```
|no.1 |no.2 |no.3 |
| :----  | :----: | ----:   | 
|:左寄せ | :中央: | 右寄せ: |

