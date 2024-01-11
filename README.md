# 電腦用漢字粵語拼音表

《電腦用漢字粵語拼音表》（下稱「粵拼表」）為二萬九千幾個中文字編訂粵語拼音，當中包括 ISO/IEC 10646-1:2000 嘅 27,484 個中文字同埋《香港增補字符集－2001》內嘅 4,384 個字符。
粵拼表以[《香港語言學學會粵語拼音方案》](https://lshk.org/jyutping)標注漢字粵音。該表原載於[此網站](http://www.iso10646hk.net/jp/document/download.jsp) 上免費供市民參考同使用。原檔案淨得 PDF 版，使用上相當不便，香港語言學學會粵拼小組喺徵詢原作者意見後，決定接手維護粵拼表，並提供更方便電腦處理嘅格式，同埋喺 GitHub 不定期發佈更新。

粵拼表以 [CC BY 4.0 權限](https://creativecommons.org/licenses/by/4.0/deed.en) 發佈。

## 檔案

### TSV
`list.tsv` 係經過香港語言學學會粵拼小組編輯嘅最新版本。
舊版本嘅 TSV 檔案都喺 `versions` 入面。

### JSON

原檔案 `JPTableFull.pdf` 嘅內容，我哋用咗 [parse-jyutping-table-full](https://github.com/cantonese/parse-jyutping-table-full) 提取並轉換做 `.json` 格式，日後我哋會 放喺 `versions` 資料夾入面。
另外2023年版嘅 `.json` 都可以喺 `versions` 揾到。


## 鳴謝
- 陸勤教授（香港理工大學）
- 張群顯博士（香港理工大學）
- 香港語言學學會粵拼小組
- Nathan Hammond (@nathanhammond)

***

# Cantonese Pronunciation List of the Characters for Computers

The Cantonese Pronunciation List of the Characters for Computers (hereafter, the List) contains the Cantonese pronunciation of over 29,000 Chinese characters, including the 27,484 characters of the ISO/IEC 10646-1:2000 and 4,384 characters of the HKSCS-2001. 

The List uses [Cantonese Romanization Scheme published by the Linguistic Society of Hong Kong (Jyutping)](https://lshk.org/jyutping) for the transcription of Cantonese pronunciation. The List is available on [this website](http://www.iso10646hk.net/jp/document/download.jsp) for public reference. Only PDF was originally provided, which is difficult to use. Jyutping Workgroup of LSHK, after consulting the creators of the list, decided to take up the maintenance of the List, and provide a more machine-friendly format for the public, and release updates on GitHub from time to time.

The List is released under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/deed.en).

## Files

### TSV
`list.tsv` is the latest version edited by Jyutping Work Group, LSHK. Older versions of the list can be found in the `versions` directory.
### JSON
Content from `JPTableFull.pdf` has been extracted and saved as `.json` under the `versions` directory using the [parse-jyutping-table-full](https://github.com/cantonese/parse-jyutping-table-full) tool. A JSON file based on the 2023 version can also be found in the same directory.
## Acknowledgement
- Dr Cheung Kwan Hin (PolyU)
- Prof Lu Qin (PolyU)
- Jyutping Workgroup, LSHK
- Nathan Hammond (@nathanhammond)
