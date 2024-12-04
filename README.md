# 用法
cscript.exe QRCode.vbs [options] [file]  
options:  
/data:数据  
/out:<图片，扩展名png、bmp>  
/filelength:<最大处理的文件长度>  
/maxlength:<最大输出的二维码字符长度>  
/monochrome:  
/transparent:  
/forecolor:  
/backcolor:  
/ecr:  
/scale:  
# 示例
```
cscript.exe QRCode.vbs /data:"Hello World" /out:"qrcode.png"
cscript.exe QRCode.vbs /out:qrcode.png QRCode.vbs
cscript.exe QRCode.vbs /out:qrcode.png /filelength:14000 QRCode.vbs
```

# 解码
https://cli.im/deqr  
