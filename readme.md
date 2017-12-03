#### 毛雷 本周汇报

### 本周TO DO LIST回顾

* 1 car_googlenet_split5实验复现

> 1.1 解析训练日志，提取车品牌的测试精确度，生成曲线图：
    
![201705031514.png](https://github.com/AllenMao/Demo/blob/master/vgg_faceemotion_transferlearning/results/201705031514.png?raw=true)
    
> 1.2 在含有10544张测试集中，运行投票测试结果：

    main acc 0.958175265554
    
    mid acc 0.943000758725
    
    mid_main acc 0.966426403642
    
    sub acc 0.913505311077 
    
    sub_main acc 0.968038694992
    
    super acc 0.97591047041
    
    main_voting_acc 0.96652124431
    
    mid_voting_acc 0.945845978756
    
    super_voting_acc 0.978566009105
    
    time 25.9265402124 ms (每8张)
    
    img_idx 10544

* 2 实现了goognet Inception v1网络的prototxt文件生成器，并在原有框架基础上，能够正常实现一条命令式训练网络。

### 下周TO DO LIST

1 测试生成的goognet Inception  v1网络文件，能否与原来的实验能够达到一致的效果。
