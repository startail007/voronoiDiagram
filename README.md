# 沃羅諾伊圖 voronoi diagram

### 參考來源

##### 1.Delaunay triangulation：https://zh.wikipedia.org/wiki/%E5%BE%B7%E5%8B%9E%E5%85%A7%E4%B8%89%E8%A7%92%E5%8C%96

##### 2.Voronoi Diagram：https://zh.wikipedia.org/wiki/%E6%B2%83%E7%BD%97%E8%AF%BA%E4%BC%8A%E5%9B%BE

### 內容

##### 1.迴圈所有的點進行從左至右排列，以一個點一個點的方式加入進行三角形連接運算(三個點的外心圍成的半徑中不能再有其他的點在其中)，會得到最外圈的圍繞的點

##### 2.將以連接的三角形的每個外心依照編號去加入給每個點對應的多邊形資料，分出外圈圍繞的點設圍未封閉多邊形與其他封閉多邊形

##### 3.將所有多邊形進行矩形框裁切

### DEMO

[線上觀看](https://virtools.github.io/voronoiDiagram/)
