# Python依赖规范

<!--
整理到开发者手册Serverless部分约定此方案、还需要协调serverless-pyreqs库的实现。
-->

[PEP582](https://www.python.org/dev/peps/pep-0582/)，在[文章](https://zhuanlan.zhihu.com/p/467243613)提到，是一种管理本项目依赖的方案，和`__pypackages__`有关。

可能用于规范Django微服务的依赖管理，以及云函数的依赖管理。

- Django服务容器化了，所以影响不大。
- 云函数必须要打包依赖，可以考虑把打包依赖的地址指定到这里，代替原本的根目录同文件，提高云端文件列表可读性。
