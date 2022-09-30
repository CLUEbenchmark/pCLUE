
#### 四个文件：

    训练集（用于训练模型）                  train.json
    验证集                                dev.json
    公开测试集（用于自己内部测试，或学术评估） test_public.json
    测试集（用于提交到榜单）                 test.json

#### 合并文件 

使用如下命令将文件合并：
    
    训练集：
    cat pCLUE_train_1.json pCLUE_train_2.json pCLUE_train_3.json pCLUE_train_4.json pCLUE_train_5.json pCLUE_train_6.json pCLUE_train_7.json pCLUE_train_8.json >> pCLUE_train.json
    
    
    公开测试集：
    cat pCLUE_test_public_1.json pCLUE_test_public_2.json >> pCLUE_test_public.json
    
    测试集：
    cat pCLUE_test_1.json pCLUE_test_2.json >> pCLUE_test.json

项目地址：https://github.com/CLUEbenchmark/pCLUE