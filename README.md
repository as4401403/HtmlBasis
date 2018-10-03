# HtmlBasis
HTML基础，HTML表格，HTML表单，网页整体结构
~~~
<!DOCTYPE html> 用于声明文档类型
<head></head> 网页头部信息
<title></title> 用于命名网页标题
<body></body> 用于显示内容
<meta http-equiv="Content-Type" content="text/html; charset=utf-8;"/>   告诉网页是内容是使用什么语言，什么编码形式，在国内使用比较多的编码是：utf-8, GB2312, gbk编码
<h1></h1> ~ <h6></h6>   标题标签
<p></p> 段落标签
<p></p>的align属性值：
                    left：左对齐内容
                    right：右对齐内容
                    center：居中显示
                    justify：伸展显示，这样头部和尾部内容长度保持一致
换行标签：<br/>
&nbsp 空格
<pre></pre> 不格式化标签，不对文字进行格式化
<hr/> 水平线
<hr/>水平线标签的属性：
                    width：设置水平线宽带，可以是像素或者是百分比，
                    color：设置水平线的颜色
                    align：设置水平线居中对齐
                    noshade：设置水平线无阴影
修饰标签：
        文字斜体：<i></i> 、<em></em>
        加粗标签：<b></b> 、<strong></strong>
        下标标签：<sub>
        上标标签：<sup>
        下滑线标签：<ins>
        删除线标签：<del>

特殊符号：
        属性      显示结果                描述
        &lt;        <         html小于号显示在文本中的标记
        &gt;        >         html大于号显示在文本中的标记
        &reg;       ®         已注册标记
        &copy;      ©         版权标记
        &trade;     TM        商标标记
        &nbsp;      Space     不断行的空白

列表标签：
        无序列表：<ul>
                    <li>可以有多个li</li>
                 </ul>
        无序列表ul的type属性：
                          值         描述
                         disc       表示圆点,默认样式
                         square     表示正方形
                         circle     表示空心圆

        有序列表：<ol>
                    <li>可以有多个li</li>
                 </ol>
        有序列表ol的type属性：
                            值       描述
                            1       数字1，2，3，4...
                            a       小写字母a，b，c...
                            A       大写字母A, B, C...
                            i       小写罗马数字i
                            I       大写罗马数字I
        定义列表：<dl>
                    <dt>定义列表项</dt>
                    <dd>列表项描述</dd>
                    <dd>列表项描述</dd>
                    <dt>定义列表项</dt>
                    <dd>列表项描述</dd>
                    <dd>列表项描述</dd>
                 </dl>
~~~