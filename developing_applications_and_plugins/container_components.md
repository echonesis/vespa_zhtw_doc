# 容器元件

本文件解釋開發所有容器層元件的基本概念。
那對於Vespa容器需要有基本的認識。

基本上都需要去繼承Vespa基本類別，比如說開發一個Searcher就要去繼承`com.yahoo.search.Searcher`。
主要可使用的五大元件類別包括：
- [處理器](https://docs.vespa.ai/documentation/jdisc/processing.html)
- [搜尋器](https://docs.vespa.ai/documentation/searcher-development.html)
- [文件處理器](https://docs.vespa.ai/documentation/document-processing.html)
- [搜尋結果渲染器](https://docs.vespa.ai/documentation/result-rendering.html)
- [提供者](https://docs.vespa.ai/documentation/jdisc/injecting-components.html#special-components)

## 並行性
Vespa的特點(之一)，反正每個元件可平行處理。

## 資源管理
TODO
