# OpenGL_Super_Bible_DLL_and_LIB

OpenGL的的超级宝典 vs2017 的配置环境库文件， 但是gltools只有32位的(64位的编译就报错，不知道什么原因，c++小白，错误也看不懂，gltools真是难搞)


如果想自己手动编译试试的   可以根据这个教程来：

https://blog.csdn.net/JW__fu/article/details/83476071

最后编译gltools时，会报一大堆库链接不到的warning，但是最后还是会生成lib，不知道有没有影响，有知道的大佬可以告诉我一下。

还有时编译会报一些问题，记得把GTLoos.h里关于window的预定义#define里的WIN32改为_Win32就好了(GLBatch.h和GLShaderManager.h),具体什么错误不记得了  好像是好多未定义还有一些其他的错
