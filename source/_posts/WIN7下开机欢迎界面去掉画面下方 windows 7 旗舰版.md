---
title: WIN7下开机欢迎界面去掉画面下方 windows 7 旗舰版
date: 2017-12-06 14:49:33
tags: 
        - Win
        - 美化
---
### 操作步骤如下：

1.  修改系统文件

    - 打开路径“C:/Windows/BrandingBasebrd/zh-CN”目录(C盘为Win7所在的系统盘，下同)，从目录中找到“basebrd.dll.mui”文件并复制到桌面备用;然后再将桌面的系统文件“basebrd.dll.mui”拖到ResHacke<绿色汉化版的“ResHacker”>r的主界面中，此时就可以看到该系统文件所包含的各种资源了;接着在“位图”分支下，展开找到“120→2052”分支并右击之，在右键菜单中选择“替换资源”，将右边显示区域中的Win7图片Logo信息替换为自己事先准备好的一张BMP格式“350×50”像素的透明图片(亦可为纯白色的图片)即可。
    - 上述操作完成后，再依次展开“位图”下面的“2120→2052”和“1120→2052”分支、将右边显示区域中的默认Win7图片Logo替换为相同大小的透明图片;最后单击菜单“文件→保存”按钮，保存对系统文件basebrd.dll.mui所做的修改就可以了。

2.  系统文件替换

鼠标右击“C:WindowsBrandingBasebrdzh-CN”目录中的“basebrd.dll.mui”文件，在右键菜单中选择“管理员取得所有权”，就可以获取对该文件进行处理的管理员权限;然后将桌面的“basebrd.dll.mui”替换“C:WindowsBrandingBasebrdzh-CN”目录下的同名文件就可以了。

3.  在运行中输入CMD，打开后输入mcbuilder.exe并执行，等待执行结束重启。
