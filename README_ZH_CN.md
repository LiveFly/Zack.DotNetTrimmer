# Zack.DotNetTrimmer
����һ��������.NET Core������������Ӧ�ó��򡣾���.NET Core���С�����δʹ�õĴ��롿�Ĺ��ܣ�������������ʹ�þ�̬������ʵ�ֵģ�������ļ���Ч�����������ŵġ�������������ȱ�㣺
1) �޷�ɾ������ʱû�б�ʹ�õĳ��򼯡����磬���ǵĳ�����ʹ����A���򼯣�A������������B��C�������򼯣�A������ֻ��M1����ʹ����B���򼯣���A������ֻ��M2����ʹ����C���򼯡����ǵĳ�����ֻ������A�е�M1����������δ����A�е�M2��������ȻC����û�б����ǵ��ù����������ڡ�����δʹ�õĴ��롿����ֻ������̬�����ü�飬���C������Ȼ���ᱻ���õ���
2) ������δʹ�õĴ��롿�޷��ܺõ�֧�ַ��䡣��������ʹ�þ�̬������ʵ�ֵģ���������ܻ���õ�����ʱ�Żᱻͨ��������صĳ��򼯡�
3) ������δʹ�õĴ��롿��֧��Windows Forms��WPF�������ڳ�����ù���������ǿ�ҵ���ʵ�������������Ŀ����ߡ�

Zack.DotNetTrimmer����Խ����Щ���⣬��֧��Windows Forms��WPF�ȣ�����������ʱ����������صĳ��򼯣��Ӷ���֪��Щ����û�б�ʹ�ã������������ɾ������û�б�ʹ�õĳ��򼯣���������Ȼ��֧�ַ��䡣��Ȼ���κ����ﶼ������ֻ���ŵ㣬û��ȱ�㡣Zack.DotNetTrimmer��ȱ���ǣ���Ҫ�����д����õ���Ŀ�����Ұѳ��������й��ܶ�ȫ�������һ�飬�������ܼ�⵽���κ�����¶����ᱻʹ�õĳ��򼯡�

�������Ч���Աȣ�
|				             | ԭʼ�ߴ�|������δʹ�õĴ��롱��ߴ�| Zack.DotNetTrimmer��ߴ�|
|  ----                      | ----    | ----                     | ----                    |
| ��ASP.NET Core MVC6��Ŀ    | 97MB    |  50.3MB                  | 43.6MB                  |
| ��ASP.NET Core WebAPI6��Ŀ | 93MB    |  46.3MB                  | 34.5 MB                 |
| ��WPF(.NET Core 6)��Ŀ     | 152 MB  |  ��֧��                  | 75.2 MB                 |
| ��WinForms(.NET Core 6)��Ŀ| 152 MB  |  ��֧��                  | 50.0 MB                 |


�÷���
1) ����Zack.DotNetTrimmer�Ŀ�ִ�г��򣬲��ҽ�ѹ���򵽴���

[windows x86](https://github.com/yangzhongke/Zack.DotNetTrimmer/raw/main/Binaries/windowsx86.zip)


[windows x64](https://github.com/yangzhongke/Zack.DotNetTrimmer/raw/main/Binaries/windowsx64.zip)


[linux x64](https://github.com/yangzhongke/Zack.DotNetTrimmer/raw/main/Binaries/linux_x64.zip)

2)��������������Zack.DotNetTrimmer���Ѵ��ü��ĳ����ȫ·����Ϊ�������ݸ�Zack.DotNetTrimmer�����к�Zack.DotNetTrimmer���Կ���̨����ʼ���У����ü��ĳ���ᱻ�Զ�������
3) ִ�д��ü��ĳ��������еĹ��ܣ��������еĴ���·����������й��ܵ�ִ�к���Zack.DotNetTrimmer�Ŀ���̨��ִ��Ctrl+C����Ctrl+Break����ü��ĳ���ķ���ر������Ե�һ��ʱ�䣬�����ü��ĳ����Zack.DotNetTrimmer�����н�����Zack.DotNetTrimmer�Ὺʼ���з����Ͳü������ü����������ʽ��Trimming done.������������Ͳü�����ˡ�����ͼ��ʾ;
![������ý��](https://raw.githubusercontent.com/yangzhongke/Zack.DotNetTrimmer/main/images/1.png)

���⣺
1) ��θ����ü����򴫵������в�����
�Ѳ��������ŵ����ü��ĳ����ȫ·���󼴿ɣ�����

```
Zack.DotNetTrimmer.exe d:\a\ASPNETCore6WebAPI1.exe --urls=http://localhost:8888/
```

2) ��λָ���ɾ�����ļ���
Zack.DotNetTrimmer�˳�ǰ������ʾ����·������ȥ�Ǹ�·����ȡ�ü�ǰ�ı��ݰ汾��