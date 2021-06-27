### 简易FaaS(Function as a Service)的实现
为了确保函数之间的安全性，避免它们互相干扰，应使它们具有良好的隔离性，可以采用沙箱技术。
实现沙箱的隔离方法有两种
- 一种是使用Docker实现容器级别的隔离，实现较为复杂。
- 一种是基于进程的隔离，实现简单、轻便、灵活。但是隔离性仍然具有一定的不足