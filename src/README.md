## Python-CTP PyCTP 接口

```
看穿调用参考 https://github.com/shizhuolin/PyCTP/blob/master/src/test_PyCTP.py#L660
已经编译好文件,内附调用示例.具体参数可参考ctp头文件.
支持python3.4/linux, python3.4/windows
PyCTP_build_20170122

这是程序化期货交易上期ctp接口版本. 为方便数值计算. 将其包装为python版本. 支持python3.4.3, win64/32/vs2010/centos7.2/gcc4.8.5上调试和编译
编译需求:vs2010,
https://github.com/shizhuolin/PyCTP

为了省事, 绝大部分代码是直接从ctp源码转换而来.
所有char[x] 均用 pybytes代替, 数据结构用pydict代替,char用pybyte代替,bool使用pybool或int
调用示范: http://www.shizhuolin.com/2015/11/07/1120.html
```
