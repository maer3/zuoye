# 作业
import matplotlib.pyplot as plt
import numpy as np
import math
def a(x):
    if x>0.5 and x<=1:
        return np.log10(pow(2,x))
    if x>0 and x<=0.5:
        b=-abs(x)
        return -np.power(math.e,b)+1
    if x<0 and x>=-1:
        return -2*x
x=np.linspace(-1,1,1000)
y=[]
for m in x:
    y1=a(m)
    y.append(y1)
plt.plot（X，Y）
![结果]https://github.com/maer3/zuoye/blob/master/QQ%E6%88%AA%E5%9B%BE20181025134213.png
