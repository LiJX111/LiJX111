## <p align="center" style="color.red">每天学习一点点，工资涨的快一点--Ljx</p>

### PDF文件编辑权限被加密使用python解密  

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
### bat脚本运行需要管理员权限
> 添加下方代码至脚本开头
> ```bat
> %1 mshta vbscript:CreateObject("Shell.Application").ShellExecute("cmd.exe","/c %~s0 ::","","runas",1)(window.close)&&exit
> cd /d "%~dp0"
> ```
