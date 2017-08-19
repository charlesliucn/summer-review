# 电磁场与波 知识梳理

## 矢量分析相关

1. 叉乘使用右手坐标系
2. 梯度是矢量，和切线方向成90度关系
3. 散度是标量，散度为0则表明该点无源
	- 高斯散度定理

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/01.png?token=AYGNCLaHJrvISHBaFwNzMhw148ki-Kfsks5ZoRUnwA%3D%3D)
4. 旋度是矢量，旋度为零，则为无旋场或保守场，环路积分为0
	- 斯托克斯定理

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/02.png?token=AYGNCKmHxr3QPEVKuDj3TSqrunUgHklvks5ZoRU7wA%3D%3D)
5. 亥姆霍兹定理：
	- 对于一个在无限远处有界、完全正则的矢量函数，一定可以分解为两个矢量函数的和，一个矢量函数散度恒等于0，另一个是两函数旋度恒等于0：矢量函数=无旋场+散度为0的场
	- 另一种解释：若一矢量场的散度和旋度在有限区域内不为0，且处处已知，则该矢量场能够唯一求得。

## 静电场基本知识

6. 库伦定律和电场强度的定义
7. 高斯定律：对静电场、时变场均成立
	- 积分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/03.png?token=AYGNCIwTpn4mT53k8Byhi7evaqP7lFCzks5ZoRVMwA%3D%3D)
	- 微分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/04.png?token=AYGNCCYd0QfjZoXMvyVf-E2eUsK4WB0Fks5ZoRVawA%3D%3D)
8. 静电场的保守性(无旋场)：
	- 积分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/05.png?token=AYGNCHpvBhrezJrEkhRgJDwpRFd5Ap94ks5ZoRVswA%3D%3D)
	- 微分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/06.png?token=AYGNCBeMREAszZ_S9HER5ycHjIDp3NUeks5ZoRV7wA%3D%3D)
9. 地面平均电场强度为120V/m，海平面为130V/m，为什么不能电死人？
10. 电偶极子，远场条件：
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/07.png?token=AYGNCJoLmWafuNHfEp3KI894MWTS16X3ks5ZoRWMwA%3D%3D)
	- 电势与距离的二次方成反比
	- 电场强度与距离的三次方成反比
11. 静电场中介质的极化：
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/08.png?token=AYGNCGgDc3I79WYeRZrKMnMpx5Vm330Wks5ZoRWkwA%3D%3D)
	- 介质极化使得电场强度降低
	- 极化强度定义：介质在给定点上单位体积内的偶极矩
12. 有介质存在时高斯定律：
	- 积分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/10.png?token=AYGNCKPfPrspEJZ_vQRPqmPxyOgKiF9Mks5ZoRXDwA%3D%3D)
	- 微分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/09.png?token=AYGNCBurOs7z462HAdXXCAwEcHtTPz5gks5ZoRWywA%3D%3D)
13. 通常极性分子的介电常数比非极性分子高
14. 电介质的分类：
	- 均匀/非均匀
	- 线性/非线性
	- 各向同性/非各向同性
15. 静电场的边界条件：
	- 电位移矢量：
		
		* ![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/11.png?token=AYGNCESxHiSjXCQKsEtCUGYZlXIvGtThks5ZoRXUwA%3D%3D)
		* 自由电荷密度
	- 静电场的环流定理：
		
		* ![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/12.png?token=AYGNCBNTMujdytPg6AMXBcKr9SZo7fMQks5ZoRXxwA%3D%3D)
	- 介质表面后角度变化的规律：
		
		* ![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/13.png?token=AYGNCPUrgW4S8zpvNzb1-bkquylTM24Sks5ZoRX6wA%3D%3D)
	- 金属分界面的边界条件：
		
		* ![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/14.png?token=AYGNCBufSuhuaG_aBn2RtBf7u9M7HW1Hks5ZoRYCwA%3D%3D)
	- 标量电位的边界条件：
		* 介质分界面(两个强制条件)：
		
		![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/15.png?token=AYGNCA40JqOmxN06TRE74I0jCpmeOfuKks5ZoRYNwA%3D%3D)
		
		![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/16.png?token=AYGNCMPKfgYWUGqYyBnxkXVpzt6lsYm1ks5ZoRYWwA%3D%3D)
		* 金属分界面(只有第1个是强制条件)
		
		![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/17.png?token=AYGNCFCKuBvj5T0Sn49PNB1zskgbssbXks5ZoRYfwA%3D%3D)
16. 静电场的能量：
	- 点电荷系能量：用电荷密度表示
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/18.png?token=AYGNCJ9C1gxHJhj87I42Qvlk4uWmjfHVks5ZoRZHwA%3D%3D)
	- 用场强表示：
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/19.png?token=AYGNCB_KB27VQFzwhKF3DyvXns93OPNVks5ZoRZPwA%3D%3D)
	- 求静电场中的力，常用的方法：虚位移法

## 静电场边值问题求解

17. 真空中：
	- 泊松方程：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/20.png?token=AYGNCAUZwJvkFIhBO1D47t3er0EASgO2ks5ZoRZbwA%3D%3D)
	- 拉普拉斯方程：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/21.png?token=AYGNCG5fStmFxApbjbxxv56PTK8U30C6ks5ZoRZmwA%3D%3D)
18. 线性各向同性的均匀介质中：
	- 泊松方程：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/22.png?token=AYGNCIMGJ-Ua1lq627vLCqJ4rwYNZkynks5ZoRZ1wA%3D%3D)
	- 拉普拉斯方程：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/23.png?token=AYGNCMIZJjVDXHqsTPfS2YeYLI1n5CB8ks5ZoRaBwA%3D%3D)
19. 边值问题的分类：
	- 第一类边值问题：全部边界的φ都已知
		* 例：电偶极子
	- 第二类边值问题：全部边界的φ的偏导都已知
		* 例：同极性电荷
	- 第三类边值问题：部分边界的φ的和剩余边界的φ的偏导已知
20. 静电场中解的唯一性定理：
	- 满足泊松方程或拉普拉斯方程及所有边界条件的**解是唯一的**
	- 求解方法1：镜像法
		* 加镜像电荷，消除边界，将问题转换到自由空间内
		* 点电荷的镜像：无限大导体平面(感应电荷)、导体球、无限大介质平面(极化电荷)
		* 线电荷的镜像：导体圆柱面
	- 求解方法2：分类变量法
		* 一维问题：双曲正弦、双曲余弦
		* 二维问题：矩形区域为例
		
		![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/24.png?token=AYGNCFRIhxgcNiW8J67ktZ3sEapt4OUbks5ZoRaJwA%3D%3D)
		* 圆柱坐标系：第一类、第二类n阶贝塞尔/虚宗量贝塞尔函数
		* 球坐标系：第一类、第二类勒让德函数
	- 求解方法3：有限差分算法
		* 矩阵+迭代
		* 如何处理第一、二类边界条件？
	- 求解方法4：格林函数法
		* 点电荷密度的δ函数表示
			+ 点电荷的密度表达式：
			
			![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/25.png?token=AYGNCKX1tTScMjMkc-AiEWP9qZLkZp1wks5ZoRaTwA%3D%3D)
		* 三类边值条件：
		
		![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/26.png?token=AYGNCFz_yWSaGRw-lZ6cVW-H0up8thXeks5ZoRabwA%3D%3D)
		* 求解格林函数的方法：镜像法、本征函数展开法

## 稳恒磁场

21. 安培定律(C1回路对C2回路的作用力)：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/27.png?token=AYGNCBlWvDLsOmg_HCFbAZn6AeiAOyiaks5ZoVX7wA%3D%3D)
22. 毕奥·萨伐尔定律

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/28.png?token=AYGNCF1k-eP2_JCyW8VKJrNtmYE5_Fekks5ZoVYpwA%3D%3D)
	- 例：无限长直线恒定电流I1产生的磁感应强度：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/29.png?token=AYGNCGm9UeiQ_hjb4WEzVlh5RCgVbFNJks5ZoVYrwA%3D%3D)
23. 洛伦兹力：
	- 磁场的洛伦兹力和电场力的合力：
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/30.png?token=AYGNCIHu8NobA2bmbn8kukw0mEGgdvZ0ks5ZoVYtwA%3D%3D)
24. 磁场的高斯定律：
	- 积分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/31.png?token=AYGNCM4pWPpKL9BxFWMEXWyfbeOR3Dq6ks5ZoVYvwA%3D%3D)
	- 微分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/32.png?token=AYGNCNr_YZ9HtGG0LtglbXsXpmxTSxweks5ZoVYxwA%3D%3D)
25. 安培环路定律：
	- 积分形式：磁感应强度切线分量大小相等

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/33.png?token=AYGNCFjoF3QYpoDZr2U_B9pNK00Tw6Ewks5ZoVYzwA%3D%3D)
	- 微分形式：

	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/34.png?token=AYGNCBkeJaifKBYI_yeBJGW32ycGd5rtks5ZoVY1wA%3D%3D)	
26. 稳恒磁场的矢量磁位：
	- 与稳恒电场中的电位对比
	
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/35.png?token=AYGNCMBQk8G_Ds02oNBDsXGjg67UScY_ks5ZoVY2wA%3D%3D)
	- 泊松方程
	
	![image](36)
27. 电偶极子和磁偶极子的场型：
	
	![image](37)

	![image](38)
28. 磁偶极子的磁矩有三个来源：
	- 电子自旋
	- 电子绕核做轨道运动
	- 原子核自旋
29. 磁介质的分类：
	- 顺磁性
	- 抗磁性
	- 铁磁性
30. 磁场强度、磁化率和相对磁导率
	- 磁场强度：

	![image](39)

	![image](40)
	- 磁化率和相对磁导率

	![image](41)
31. 磁场的边界条件：
	- 磁感应强度法向连续

	![image](42)
	- 磁场强度切向连续

	![image](43)
	- 矢量磁位连续
32. 磁场的边值问题：
	- 镜像电流法
	- 安培环路定律

## 准静态场、电感和磁场能

33. 法拉第电磁感应定律
	- 静止系统中的感生电动势

	![image](44)
	- 运动系统中的感生电动势

	![image](45)
34. 准静态场近似的电路理论：
	- 基尔霍夫结点电流定理：

	![image](46)
	- 基尔霍夫环路电压定理：

	![image](47)
35. 电感
	- 自感

	![image](48)
	- 互感

	![image](49)
36. 磁场中存储的能量：
	
	![image](50)


## 时变电磁场
37. 麦克斯韦方程组
+ 微分形式：

![image](51)
+ 积分形式：

![image](52)
+ 复数形式(时谐电磁场)：

![image](56)
+ 关系式：
	- 自由空间：

	![image](53)
	- 介质：

	![image](54)
+ 边界条件：

	![image](55)

38. 时变电磁场的波动性和波动方程
	
![image](57)

![image](58)

+ 时谐场：

![image](59)

39. 时变场的坡印亭定理:
+ 能量密度：

![image](60)
+ 一般时变场坡印亭矢量：

![image](61)
+ 时谐场的坡印亭矢量：

![image](62)

## 平面电磁波
39. 无限大无损媒质中的均匀平面波：
+ 属于TEM波，不存在z分量
+ 均匀平面波：
	- 均匀：波前面上各点场强相同
	- 平面波：波前等相位面是一个平面
	- 电场强度及磁场强度传播方向两两垂直
	- 电场储能密度和磁场储能密度在任意场点相等
+ 无损媒质的波阻抗：(电场和磁场的正交分量的瞬时值之比)

![image](63)

40. 有损媒质中的均匀平面波：
+ 仍是TEM波
+ 有损媒质中波长变短
+ 有损媒质中波的传播速度不再是常数，与频率有关，称为色散现象→有损媒质是色散媒质
+ 电场储能和磁场储能密度不再相等
+ 有损媒质会造成幅度衰减
	- 衰减到原来1/e的距离称为衰减长度
	- 对于良导体，衰减长度→趋肤深度

41. 电磁波的极化

![image](64)
+ φ1对应x方向电场，φ2对应y方向电场
+ φ1-φ2 = π/2，右旋圆极化波
+ φ1-φ2 = - π/2，左旋圆极化波

42. 波的相速和群速

![image](65)

43. 平面电磁波的反射与折射：
+ 概念
	- 垂直极化波
	- 平行极化波
	- 功率反射系数
	- 功率传输系数
+ 无反射→布儒斯特角：

![image](66)

+ 全反射→临界角：

![image](67)

+ 垂直极化波投射到导体平面：
	* TE波特性
	* 法向驻波，切向快波
+ 平行极化波透射到导体平面：
	* TM波特性
+ 补充：电磁波方程的一种数值解法：
	* **时域有限差分算法**


## 波导与谐振腔
44. 金属的边界条件：

![image](68)

45. 各种模式的电磁波：
+ 横电磁波(TEM模)：电磁场均无纵向(传输方向)分量
	* 无损/有损均匀平面波
	* 同轴线：电容越大，特性阻抗越小
+ 横磁波(TM模)：磁场无纵向分量，电场有纵向分量
	* 矩形波导：基模为TM11模
+ 横电波(TE模)：电场无纵向分量，磁场有纵向分量
	* 矩形波导：基模为TE10模，截止波长为2a
+ 混合波：电场磁场的纵向分量均不为0

![image](69)

46. 纵向分量法→用于求解柱形传输结构中的场的关系

47. 波导中的相速度与群速度及波导波长

![image](70)

48. 谐振腔：110模式

![image](71)

50. 电磁波的辐射：
+ 电偶极子的辐射场：
	- 近区场：和静电场偶极子产生的电场表达式一致
	- 远区场：

	![image](72)

		* 正比于频率的四次
	- 天空是为什么是蓝色的？晚霞为什么是红色的？

+ 磁偶极子的辐射场
	- 坡印亭矢量大小同样正比于频率的四次方