
# ReadIn: 
1. save input as a global array

# Solve: 
1. check the array have answer or not
  * 一陣列存-1跟1~9的個數，然後去檢查行跟列
  * 如果-1的個數不是3個就會有問題，如果某個數字用兩次甚至以上也有問題 
  * 以上就是會造成無解的狀況，如果無解就印出0
2. find the answer 
  * 解出答案有兩種不同的順序，一種是從前面一種是從後面
  * 如果前後解出來答案相同代表只有唯一解，如果不同的話就是有多重解，就印出2
  * 在解的同時，如果這個空格解不出來代表前面的格子有填錯
  * 若有錯就會利用之前暫存位置的陣列，回到之前的狀態繼續做
