
# CEF Fonts CJK

#### CEF Fonts CJK是一个完全用鼠标构建字形的“仿”手写体。目前版本为公开测试版（最新版本号：Alpha 0.1 With 3rd Fix）。
 **若上方版本号数字后面出现其他内容，则该内容也属于版本号（仅限冒号和右括号之内的区域）** 

## 介绍
 
本字体最大的特点就是里面的绝大部分字形均由鼠标绘制。目前已对CJK统一汉字区块（20989个字）、谚文音节（常用2350个）提供主要支持，
可以为简繁中文、日语、韩语、英语、希腊语、俄语、泰语（仅字符）、阿拉伯语（待改进）等部分语言提供基本显示。

## 特色 

- 连字（好像也不能算什么特色吧）
通过.liga脚本，fi、ff、fl、ffi、ffl这五个组合将会被连接在一起。
![连字效果 如图所示](https://images.gitee.com/uploads/images/2021/0727/161727_457d5a49_9504356.png "Eg01.png")

- 拒绝一切装饰
为使字符更容易被辨认，拒绝任何字符上的装饰，一目了然。
 _（注：变音符号不能算装饰，在实际应用中，您依然可以对字符进行装饰，但不是直接修改字体源文件。）_ 
![无装饰 如图所示](https://images.gitee.com/uploads/images/2021/0727/163957_d0394bdf_9504356.png "Eg02.png")

- 支持CJK统一汉字区块最后面的一些汉字
位于Uni9FA6~Uni9FFF的“神秘汉字”在此字体被支持。
![神秘汉字](https://images.gitee.com/uploads/images/2021/0919/182358_9aadfd44_9504356.jpeg "EG07.jpg")
** 最后三个字符为 Unicode 14.0 新增的字符 **

- Kerning 调节字符间距
基本技术，通过添加Pair Adjustment来调整字偶距。（后续会添加更多）
![间距调节 如图所示](https://images.gitee.com/uploads/images/2021/0727/172027_eb498ad5_9504356.png "EG04.png")

- biang
在电脑端按住Alt，输入200413（简体）或 200414（繁体），即可召唤。Unicode位置分别为Uni30EDD、Uni30EDE。
![两个biang 如图所示](https://images.gitee.com/uploads/images/2021/0727/172626_077f4d2d_9504356.png "Eg05.png")

- 化学反应方程式功能[Beta]
在私用区添加了一些化学反应方程式可能会用到的符号。告别凌乱格式，直接输入该符号即可表示化学方程式。
下面是一些使用的例子：
![使用例](https://images.gitee.com/uploads/images/2021/0919/183506_8fbba1b5_9504356.png "EG08.png")

在未来将可能会有更多特色呈现。

## 使用说明

1. 本字体可以商用，可以转载至受大多群众信任的网站提供下载。但在未正式决定开源之前，**您不得修改、贩卖本字体的源文件或从源文件提取的子集**。
2. 若您发现了字体中存在的问题，或者是对字体开发有建议，均可以在此以issue提出或者去B站账户（派对大魔王）私信反馈。
3. **强烈建议您不要使用此字体去写三维世界的作业，若被老师等人批评，本作者不承担任何责任。** 
4. 在正式版发布后将会把许可证改为OFL许可。

