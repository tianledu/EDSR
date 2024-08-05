# 说明文档

**代码采用Jupyter Notebook编写，实验记录均在代码ipynb文件中保存**
原论文：[pdf](https://arxiv.org/pdf/1707.02921))

## Configuration Environment
```
pip install -r requirements.txt
```

## **EDSR_NAF**：

edsr_nafblock-盲超分.ipynb:盲超分代码

edsr_nafblock.ipynb：ResBlock替换为NAFBlock的代码，训练了2000个epoch，也是最终ppt展示的效果代码

edsr_nafblock_DIV2K.ipynb：ResBlock替换为NAFBlock的代码，更换了测试集，训练了500个epoch

BSRGAN_py：盲超分退化模型代码

checkpoints：模型保存文件夹

​	edsr_NAF.pth：NAFBlock最终模型

​	edsr_NAF_non.pth：盲超分最终模型

0811x2.png：用于模型测试的图片

result_NAF.png：基础NAFBlock测试结果图

result_NAF_non.png：盲超分测试结果图

## EDSR_Res：

edsr_resblock.ipynb：ResBlock代码

checkpoints：模型保存文件夹

​	edsr_res.pth：ResBlock最终模型

0811x2.png：用于模型测试的图片

result_Res.png：ResBlock测试结果图

#### 实验数据.md

最终实验结果记录

