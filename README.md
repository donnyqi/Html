# HTML

标签（空格分隔）： HTML 标签 元素 属性

Html介绍，基础知识

---
## Html历史 ##


## Html基础 ##
Html是用来描述网页的一种语言：超文本标记语言(Hyper Text Markup Language)

- 标记语言是一套标记标签，Html使用标记标签来描述网页

    ### Html标签 ###
    Html标记标签通常被称为Html标签(Html tag)
    - Html标签有尖括号包围的关键字
    - Html标签通常成对出现
    - 标签中第一个标签是开始标签，第二个标签是结束标签
    - 开始标签——开发标签，结束标签——闭合标签
    
    ### Html元素 ###
    Html元素是从开始标签到结束标签的所有代码
    - Html元素以开始标签起始，以结束标签终止
    - 元素的内容是开始标签与结束标签直接的内容
    - 某些Html元素具有空内容——空元素(空标签)：空元素在开始标签中进行关闭
        `在 XHTML、XML 以及未来版本的 HTML 中，所有元素都必须被关闭。
        在开始标签中添加斜杠，比如 <br />，是关闭空元素的正确方法，HTML、XHTML 和 XML 都接受这种方式。
        即使 <br> 在所有浏览器中都是有效的，但使用 <br /> 其实是更长远的保障。`
    - Html元素(标签)可拥有属性
    
    ### Html属性 ###
    - Html标签可以拥有属性。属性提供了有关Html元素更多的信息
    - 属性是以key/value 的形式出现 name="value"
    - 属性总是在Html元素的开始标签中规定
    
    ### Html格式化 ###
    Html可以直接定义很多格式化输出的元素，例如粗体、斜体等等
    - 文本格式化：b,strong,big,em,i,small,sub,sup
    - 预格式文本：pre
    - 计算机输出：code,kbd,tt,samp,var
    - 地址：address
    - 项目、缩写、首字母缩写：dfn,abbr,acronym
    - 块引用：blockquote,q
    - 删除字、插入字：del,ins
    - 著作标题：cite
    - 定义文本方向：bdo `<bdo dir="rtl">This text will be written from right to left</bdo>`
    
    ### Html注释 ###
    - `<!-- *** -->`
    - `条件注释:
    <!--[if IE 8]>
    .... some HTML here ....
    <![endif]-->
    `
    
    ### Html常用标签 ###
    - 链接 
        `<a href="url" name="anchor" target="_blank">**</a>
        href定义指向另一个文档的链接
        name定义指向文档内的书签-锚点
        href="mailto:173256928@qq.com" 邮件
        href="tel:18352774833" 电话`
    - 图像 
        `<img src="url" alt="**" />`
    - 表格
        `table 
        caption 标题
        th 表头
        tr 行
        td 列
        thead
        tbody
        tfoot
        col
        colgroup`
    - 列表
        `无序列表ul li
        有序列表ol li
        定义列表dl dt dd`
    
    ### Html块级元素与内联元素 ###
    - 块级元素 block level element:块级元素显示时以新行开始与结束 div,h1,p……
    - 内联元素 inline element:内联元素显示不会以新行开始与结束 span……
    

    
    `注：
    Html标签可以分为两类：
    基于内容的样式：表示它所包含的文本具有特定的含义、上下文或者用法
    物理样式：表示对文本产生的强烈效果
    `

    testtest
    111
    222





