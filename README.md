### <p align="center" style="color.red">ljx</p>

## PDF文件编辑权限加密python解密代码  

> - 安装python环境
> - 在终端上使用`pip install pikepdf`安装pikepdf库
> - python中导入该库`import pikepdf` 

常规破解代码：
```python   
  import pikepdf
 
  pdf =pikepdf.open("file_path")#输入待解密pdf文件  
  pdf.save("filename.pdf")#另存为pdf文件  
  print("解密完成")   
```
mrakdown画个表
| t1 | t2 | t3 |
|---|---|---|
| k1 | k2 | k3 |  
|k4|k5|k6|
