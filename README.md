# tianshu
Usage of server
- 首先登录了服务器，根据使用操作指南完成了新用户的创建，并将ssh设置为新用户登录

![image](https://github.com/user-attachments/assets/04ec91ff-cd35-472e-980d-328510bc36a4)
- 链接好了ixsmi

![image](https://github.com/user-attachments/assets/4b38372a-2933-4695-8244-0e8748a5615b)
- git了CUDA作业的分支并且能够成功的make test

![image](https://github.com/user-attachments/assets/7eec3166-98b9-4449-b4d0-aabeb74186d9)
- 能够成功运行test

![image](https://github.com/user-attachments/assets/fa7afb06-5214-4699-a564-2d61622584c8)

- 延迟-发送请求到实现所需的时间
- 带宽-单位时间移动数据量
- 阿姆达尔定律用于探究最大加速比的实现
- 古斯塔法森定律用于探究工作量增加的加速实现
- 孙-倪定律用于表示非线性的加速比实现  
- <<<grid ,block>>>
- Dim是个数，Idx是序列数
- 原则上来说grid之间应该是不互通数据的，因此申请share可以互通
- 对于thread的计算就是利用for循环进行分配的！
- 规约含有交叉规约、交错规约、warp 和block reduce
- kernel里面的局部变量是存储在寄存器中
- 计算仿存比增加，那么kernel的时间就会减少
- float4是一种内在的数据类型，它能够连续存储四个float，因此能仿问次数

**已经看完了老师的视频，自己写了一段gather_cuda.cu的代码，但是效果不好，正在修正bug**
