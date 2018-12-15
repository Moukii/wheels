## base64隐写工具

>deStego(stegoFile)

从隐写文件stegoFile提取字符串

>enStego(sourceFile,setgoFile,message)

根据源文件sourceFile隐写字符串message,base64保存到stegoFile

##### Example:
```
In [249]: %run b64EnStego.py
0101001101101001011011010111000001101100011001010100110101100101011100110111001101100001011001110110010100001010
Remaining 0 bits!

In [250]: %run b64DeStego.py
SimpleMessage
```