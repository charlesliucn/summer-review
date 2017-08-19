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

1. 库伦定律和电场强度的定义
2. 高斯定律：对静电场、时变场均成立
	- 积分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/03.png?token=AYGNCIwTpn4mT53k8Byhi7evaqP7lFCzks5ZoRVMwA%3D%3D)
	- 微分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/04.png?token=AYGNCCYd0QfjZoXMvyVf-E2eUsK4WB0Fks5ZoRVawA%3D%3D)
3. 静电场的保守性(无旋场)：
	- 积分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/05.png?token=AYGNCHpvBhrezJrEkhRgJDwpRFd5Ap94ks5ZoRVswA%3D%3D)
	- 微分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/06.png?token=AYGNCBeMREAszZ_S9HER5ycHjIDp3NUeks5ZoRV7wA%3D%3D)
4. 地面平均电场强度为120V/m，海平面为130V/m，为什么不能电死人？
5. 电偶极子，远场条件：
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/07.png?token=AYGNCJoLmWafuNHfEp3KI894MWTS16X3ks5ZoRWMwA%3D%3D)
	- 电势与距离的二次方成反比
	- 电场强度与距离的三次方成反比
6. 静电场中介质的极化：
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/08.png?token=AYGNCGgDc3I79WYeRZrKMnMpx5Vm330Wks5ZoRWkwA%3D%3D)
	- 介质极化使得电场强度降低
	- 极化强度定义：介质在给定点上单位体积内的偶极矩
7. 有介质存在时高斯定律：
	- 积分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/10.png?token=AYGNCKPfPrspEJZ_vQRPqmPxyOgKiF9Mks5ZoRXDwA%3D%3D)
	- 微分形式：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/09.png?token=AYGNCBurOs7z462HAdXXCAwEcHtTPz5gks5ZoRWywA%3D%3D)
8. 通常极性分子的介电常数比非极性分子高
9. 电介质的分类：
	- 均匀/非均匀
	- 线性/非线性
	- 各向同性/非各向同性
10. 静电场的边界条件：
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
11. 静电场的能量：
	- 点电荷系能量：用电荷密度表示
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/18.png?token=AYGNCJ9C1gxHJhj87I42Qvlk4uWmjfHVks5ZoRZHwA%3D%3D)
	- 用场强表示：
	![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/19.png?token=AYGNCB_KB27VQFzwhKF3DyvXns93OPNVks5ZoRZPwA%3D%3D)
	- 求静电场中的力，常用的方法：虚位移法

## 静电场边值问题求解
12. 真空中：
	- 泊松方程：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/20.png?token=AYGNCAUZwJvkFIhBO1D47t3er0EASgO2ks5ZoRZbwA%3D%3D)
	- 拉普拉斯方程：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/21.png?token=AYGNCG5fStmFxApbjbxxv56PTK8U30C6ks5ZoRZmwA%3D%3D)
13. 线性各向同性的均匀介质中：
	- 泊松方程：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/22.png?token=AYGNCIMGJ-Ua1lq627vLCqJ4rwYNZkynks5ZoRZ1wA%3D%3D)
	- 拉普拉斯方程：![image](https://raw.githubusercontent.com/charlesliucn/summer-review/master/07-%E7%94%B5%E7%A3%81%E5%9C%BA%E4%B8%8E%E6%B3%A2/figures/23.png?token=AYGNCMIZJjVDXHqsTPfS2YeYLI1n5CB8ks5ZoRaBwA%3D%3D)
14. 边值问题的分类：
	- 第一类边值问题：全部边界的φ都已知
		* 例：电偶极子
	- 第二类边值问题：全部边界的φ的偏导都已知
		* 例：同极性电荷
	- 第三类边值问题：部分边界的φ的和剩余边界的φ的偏导已知
15. 静电场中解的唯一性定理：
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
