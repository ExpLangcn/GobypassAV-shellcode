# GobypassAV-shellcode
2023/04/18 使用go写的shellcode免杀加载器，免杀主流杀软，bypass火绒、360、def等

食用方法：

1、生成c的payload

![image](https://user-images.githubusercontent.com/88339946/232708666-a8e28b1b-2502-4bbc-91a9-d88e5ff44e9d.png)

2、加密后的结果填到代码里编译运行 `go build -ldflags="-s -w"`

![image](https://user-images.githubusercontent.com/88339946/232708833-9709b6c6-59b3-455a-aaa5-e4a92e549c3b.png)


免杀效果：

![image](https://user-images.githubusercontent.com/88339946/232709153-3e45970a-a0ae-409b-bfdc-f9db0209d0ce.png)

![image](https://user-images.githubusercontent.com/88339946/232708175-24667b5d-09c5-4c43-b8d5-ebb193b17335.png)

![image](https://user-images.githubusercontent.com/88339946/232708290-e8f5c3cb-52cb-45bf-a7ea-43615bae0e9d.png)

![image](https://user-images.githubusercontent.com/88339946/232708368-37c6bd82-8a56-4b15-a298-4576a95fd5ee.png)

项目仅供进行学习研究，切勿用于任何非法未授权的活动，如个人使用违反安全相关法律，后果与本人无关

站在巨人的肩膀上学习，参考借鉴以下师傅的项目，特别感谢
https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-virtualalloc

https://github.com/7BitsTeam/EDR-Bypass-demo 

https://www.yuque.com/aufeng/aufeng_good/aq09p0#yNorm

https://mp.weixin.qq.com/s/xiFbSE6goKFqLAlyACi83A

https://github.com/timwhitez/Doge-Loader

https://github.com/TideSec/GoBypassAV

https://www.crisprx.top/archives/515

https://github.com/Ne0nd0g/go-shellcode

https://github.com/piiperxyz/AniYa

https://github.com/safe6Sec/GolangBypassAV
