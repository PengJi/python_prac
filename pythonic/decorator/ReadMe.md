装饰器用于有切面需求的场景，比如：插入日志、性能测试、事务处理、缓存、权限校验等场景。
本质上是一个函数，这个函数接收其他函数作为参数，并将其以一个新的修改后的函数进行替换
概括的讲，装饰器的作用就是为已经存在的对象添加额外的功能。

# 使用场景
=========
1. 注入参数（提供默认参数，生成参数）
2. 记录函数行为（日志、缓存、计时）
3. 预处理/后处理
4. 修改调用时的上下文（线程异步或者并行，类方法）


# 使用装饰器需要注意的地方
=========
1. 函数的属性变化
2. 使用inspect获取函数参数
3. 多个装饰器的调用顺序
4. 给装饰器传递参数

# 参考
[python装饰器入门与提高](http://mingxinglai.com/cn/2015/08/python-decorator/)
