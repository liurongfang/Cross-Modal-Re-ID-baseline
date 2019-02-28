**修改记录**

#test.py
`--model_path`:修改为对应路径


#train.py
`--batchsize`:内存跑满了，从32修改为4

bugfix:https://github.com/martinarjovsky/WassersteinGAN/pull/69,must add code as follow on windows machine:
```python
if __name__=="__main__":
    pass
```






