# jspshellbypass
jsp进程注入上线cs过360核晶

![图片](https://github.com/user-attachments/assets/a549e340-2943-49a3-bb5d-d0e335276ce2)

使用动态加载技术实现。

![图片](https://github.com/user-attachments/assets/9fcbd086-ba5e-47ad-ba83-180fe4435ef2)

使用的注入方法，常规手段：

HANDLE hThread = CreateRemoteThreadEx(hProcess, null, new DWORD(0), remoteMemory, null, new DWORD(CREATE_SUSPENDED), null);


