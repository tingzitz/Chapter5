# Chapter5
## 课后习题解答
---
* 5.1
  * 5.1.1
  * 5.1.2 调用RANDOM(0, 1), 实现RANDOM(a, b), 期望运行时间？
  
   	生成m个bit位(0 or 1), 共有n个数，b-a<=n
   	
	期望运行时间：`n/(b-a)`
  
  * 5.1.3 调用BIASED-RANDOM(0, 1) 0->p, 1->1-p, 实现RANDOM(0, 1), 即p=1/2, 期望运行时间？
	 
	 生成2个bit位(0 or 1), 若为 00 或 11，则舍弃并重新生成
	 
	 01 -> p(1-p)
	 
	 10 -> (1-p)p
   
   	期望运行时间：`1/2p(1-p)`
  
---
* 5.2
