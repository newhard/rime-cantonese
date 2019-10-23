# Rime 粵語拼音方案

配方：℞ `sgalal/rime-cantonese`

本配方為 [rime/rime-jyutping](https://github.com/rime/rime-jyutping) 嘅帶聲調版同 IPA 顯示版。配方入邊 `jyut6ping3` 係聲調顯示版方案，`jyut6ping3_ipa` 係 IPA 顯示版方案。

**配方目前仲處於開發階段，歡迎 PR 或響 Issue 區反饋意見**

## 拼音方案

- [Jyutping 粵拼 | lshk](https://www.lshk.org/jyutping)
- [香港語言學學會粵語拼音方案](https://zh.wikipedia.org/wiki/香港語言學學會粵語拼音方案)

## 用法

| 聲調版                     | IPA 版                    |
| -------------------------- | ------------------------- |
| ![示例 1](./demo/tone.gif) | ![示例 2](./demo/ipa.gif) |

本方案默認唔兼容任何模糊音同懶音，即區分泥來、疑影等常見懶音。

輸入嗰陣可以忽略聲調，如果想輸入聲調，對應鍵位係：

1. 陰平 `v`；如要輸入「詩」則鍵入 `siv`
2. 陰上 `x`；如要輸入「史」則鍵入 `six`
3. 陰去 `q`；如要輸入「試」則鍵入 `siq`
4. 陽平 `vv`；如要輸入「時」則鍵入 `sivv`
5. 陽上 `xx`；如要輸入「市」則鍵入 `sixx`
6. 陽去 `qq`；如要輸入「事」則鍵入 `siqq`

撳 <kbd>Ctrl</kbd> 同 <kbd>`</kbd> 開啟方案選單後可以打開地區用字轉換功能，支援香港繁體、臺灣正體同大陆简体。

## 數據來源

### 字音

- LSHK 字音表 - [資料 (laubonghaudoi/cantonese_orthography)](https://github.com/laubonghaudoi/cantonese_orthography/blob/master/LSHK%20Jyutping%20-%20Char%20-%20JP.csv)
- 粵音小鏡 - [資料 (laubonghaudoi/cantonese_orthography)](https://github.com/laubonghaudoi/cantonese_orthography/blob/master/%E7%B2%B5%E9%9F%B3%E5%B0%8F%E9%8F%A1(20160723).xls)
- 廣州話正音字典 - [資料來源 (jyutnet/cantonese-books-data)](https://github.com/jyutnet/cantonese-books-data/tree/master/2004_%E5%BB%A3%E5%B7%9E%E8%A9%B1%E6%AD%A3%E9%9F%B3%E5%AD%97%E5%85%B8)
- 常用字廣州話讀音表 - [資料來源 (jyutnet/cantonese-books-data)](https://github.com/jyutnet/cantonese-books-data/tree/master/1992_%E5%B8%B8%E7%94%A8%E5%AD%97%E5%BB%A3%E5%B7%9E%E8%A9%B1%E8%AE%80%E9%9F%B3%E8%A1%A8)
- 粵語審音配詞字庫 - [原網站](https://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/) - [資料來源 (sgalal/lexi_can_crawler)](https://github.com/sgalal/lexi_can_crawler)

### 詞語

- 香港語言學學會粵拼詞表 - [原網站](https://corpus.eduhk.hk/JPwordlist/) - [資料來源 (sgalal/lshk-word-list-crawler)](https://github.com/sgalal/lshk-word-list-crawler)

## 詞庫製作流程

本方案詞庫製作流程詳見本倉庫 [`build`](https://github.com/sgalal/rime-cantonese/tree/build) 分支。
