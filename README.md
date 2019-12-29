# mimaxue_hw3  
1901210593 张宇驰  
1.	计算祖冲之密码算法中置换表S0和S1的DDT和LAT  
代码见[hw3.py](https://github.com/zhangyuchi1996/mimaxue_hw3/blob/master/hw3.py)  
输出文件见[tables](https://github.com/zhangyuchi1996/mimaxue_hw3/tree/master/tables)  
2.	为什么最后需要异或轮密钥？  
答：因为S盒可逆，如果不在最后一轮加入与轮密钥的异或操作，攻击者拿到密文之后可以轻松破解最后一轮S盒加密，降低了安全性。
