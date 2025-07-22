# BypassAv

# 中文说明
本项目仅供网络安全爱好者在合法授权的环境下进行渗透测试、红队研究与技术学习之用。  
严禁将本项目或其衍生工具用于任何非法活动，包括但不限于：  
1.黑产行为（黑帽攻击、数据盗窃等）  
2.未经授权的内网渗透或漏洞利用  
3.扰乱公共网络或侵犯第三方权益的行为  

请牢记：互联网不是法外之地！  
使用本项目即表示您已理解并同意上述要求。因非法使用本项目所引发的任何法律责任与后果，均由使用者个人承担。  

# 作者初心
🧰 为了让红队和渗透测试人员少踩坑，这个 EXE 做了免杀处理优化，节省你反复调试的时间。  
🚫 没有加壳，方便你逆向、调试和改造。  
🔒 源码因特殊原因暂不开放，但后续会持续维护使用说明。  

如果本项目对您的工作有所帮助，欢迎给予⭐️支持，感谢您的鼓励！  

# 工具使用说明
1.只需将生成的 bin 文件重命名为 2.txt。，将2.txt与压缩包解压后的Xor.exe和BypassAv.exe放入同一个目录。   
2.运行第一个 Xor.exe，程序会自动对2.txt内的Shellcode进行混淆，并覆盖掉原本未加密的Shellcode。  
eg：加密前后对比   
<img width="373" height="872" alt="image" src="https://github.com/user-attachments/assets/0fd53511-4813-4d26-875c-29fc68b80140" />
<img width="406" height="894" alt="image" src="https://github.com/user-attachments/assets/91a65cad-8107-4ac8-859f-32c2f6776bee" />

3.在目标环境中，只需要将 2.txt 与BypassAv.exe文件放在同一目录下即可正常使用。【BypassAv.exe可以随意改名】    
<img width="132" height="204" alt="image" src="https://github.com/user-attachments/assets/fc97f9d8-dede-4903-9877-b2479d3334ce" />

解压密码:leek  


# 更新日志  
更新说明，免杀失效可在问题中留言，作者会留意并更新，持续更新.....  
2025.7.23  ----  增加Hook
2025.7.20  ----  增加导入表隐藏处理
<img width="1419" height="605" alt="image" src="https://github.com/user-attachments/assets/2525f15f-55f6-4c59-9d4c-103b8553f4a6" />


# 免杀效果  
支持 360安全卫士，Windows Defender，腾讯安全管家以及火绒等杀软一键上线并执行命令  
<img width="1713" height="1193" alt="image" src="https://github.com/user-attachments/assets/1a6e10e1-79fe-43d9-a163-fbb1c0869c5a" />
<img width="1933" height="1270" alt="image" src="https://github.com/user-attachments/assets/f0ffe380-dcab-4236-b3e1-1946f28a5c85" />
<img width="1133" height="589" alt="image" src="https://github.com/user-attachments/assets/c6f030ae-1265-4350-955b-7d0d10fa5507" />
