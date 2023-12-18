# gobang（升级中...）
## 井字棋
https://github.com/liuzhen910201/tiktaktoe
## 五子棋
### 运行效果图
<br>初始<br>
![](https://github.com/liuzhen910201/gobang/blob/main/gobang1.png)
<br>
运行
<br>
![](https://github.com/liuzhen910201/gobang/blob/main/gobang2.png)

### 设定
1，MCTS计算次数设定为10000
<br>
```

for _ in range(10000):

```
 <br>
2, 电脑设定位置设定为已落子的临近位置 (上，下，左，右，左上，左下，右上，右下)
<br>
对应函数：get_legal_moves
<br>
```
1 2 3
4 5 6
7 8 9
```
 <br>
若落子在5，则电脑候选落子位置1，2，3，4，6，7，8，9
