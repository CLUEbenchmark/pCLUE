train/dev/test_public/test

使用如下命令将文件合并：

训练集：
cat pCLUE_train_1.json pCLUE_train_2.json pCLUE_train_3.json pCLUE_train_4.json pCLUE_train_5.json pCLUE_train_6.json pCLUE_train_7.json pCLUE_train_8.json >> pCLUE_train.json

测试集：
cat pCLUE_test_1.json pCLUE_test_2.json >> pCLUE_test.json

公开测试集：
cat pCLUE_test_public_1.json pCLUE_test_public_2.json >> pCLUE_test_public.json

项目地址：https://github.com/CLUEbenchmark/pCLUE