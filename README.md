# snownlp
SnowNLP sentiment for Traditional Chinese

說明:

[SnowNLP](https://github.com/isnowfy/snownlp) 專案的情緒分析 (sentiment) 缺少繁體中文的訓練資料，將該專案上的文件 (`'neg.txt'`, `'pos.txt'`) 簡轉繁，產生訓練文件 (`'sentiment_zhtw.marshal.3'`)。

如何產生訓練文件:

```python
# from snownlp import sentiment
# sentiment.train('neg.txt', 'pos.txt')
# sentiment.save('sentiment_zhtw.marshal')
```

如何使用:

* 修改 `snownlp/sentiment/__init__.py`的`data_path`指向訓練文件 `'sentiment_zhtw.marshal'` 注意檔名不需要加上 `.3`


