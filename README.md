好，其實呢
我的GiveQuestion用的方法有點笨.....
而且非常爛，種類不多
就是亂數加上原本的東西，然後零跟負一不動
我本來還想要加上一些方法利用亂數隨機挖空格
再用我的solve去檢查我做出來的題目會不會挖成無限多或多重解
但是後來我的Solve寫得有點慢.....
所以後來就這樣了 -.-

我的ReadIn就是很普通的把輸入的東西存成一個global陣列

我的Solve，首先就是去檢查說現在輸入的陣列是不是無解的狀況
有個陣列存-1跟1~9的個數，然後去檢查行宮列
如果-1的個數不是3個就會有問題，如果某個數字用兩次甚至以上也有問題 
以上就是會造成無解的狀況，如果無解就印出0
解出答案有兩種不同的順序，一種是從前面一種是從後面
如果前後解出來答案相同代表只有唯一解，如果不同的話就是有多重解，就印出2
在解的同時，如果這個空格解不出來代表前面的格子有填錯
所以，如果有錯就會利用我之前暫存位置的陣列，回到之前的位置做
額，以上大概就是我的想法跟概念

寫完這次的project我覺得還滿有成就感的
感覺自己好像第一次做出可以給別人玩的東西(雖然是黑白的而且非常醜非常簡陋..)
而且這是我第一次遇到可以編譯成功卻在執行的時候跑出一個莫名其妙的網址(超奇怪==)
各種奇幻冒險啊，而且這個作業的有趣程度比上個學氣要高出太多太多了
雖然同樣是黑白介面，卻讓我有想要去研究的感覺
希望每一次交作業的自己都比上一個我進步許多

還 
煩請手下留情 QAQ 
