# html basic
> 标签可被分为替换标签和费替换标签,也可被分为块级标签和内联标签

#### p标签
> 块级标签/非替换标签,段落标签
```
<p>lorem</p>
```

#### div标签
>块级标签/非替换标签,盒子标签
```
<div>可以嵌套任何的标签</div>
```

#### h1~h6
> 块级标签/替换标签
```
<h1>标题</h1>
```

#### a标签
> 替换元素/行内元素
* 存放超链接
```
<a href= "https://www.baidu.com" target="_self">百度</a>
跳转属性: target
* _self
* _blank
```
* 发送邮件
```
<a href="mailto:2206553304@qq.com" target="_blank">点击给我发送邮件</a>
```
* 打电话
```
<a href="tel:10086">拨号</a>
```
* 页内跳转
```
<a href="#page_bottom" target="_self">跳转到本页的底部</a>
```
* 下载文件
```
<a href="./index.html" download="index.html">点我可以下载一个文件</a>
```

#### img标签
> 插入图片,替换标签
```
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRstLcDMlLZd42XhqnQLMgjKZNci9VLBW94_g&usqp=CAU" alt="葡萄">

```
#### hr标签
 用来分隔内容,单标签

#### 文本样式标签
* b标签/strong标签 (加粗文本)
* em标签/i标签 (斜体)
* u标签(下划线)

#### html实体
> 在网页显示特殊字符,ASC编码/Unicode编码;
```
&copy;      版权      
&reg;       注册商标
&trade;     商标
&nbsp;      空格
&amp;       和号
&quot;      引号
&apos;      撇号
&lt;        小于号
&gt;        大于号
&ne;        不等号
&le;        小于等于
&ge;        大于等于
&cent;      分
&pound;     磅
&euro;      欧元
&yen;       元
&sect;      节
&times;     乘号
&divide;    除号
&plusmn;    正负号
```
#### 列表
* 无序列表
```
<ul>
<li>lorem</li>
</ul>
```
* 有序列表
```
<ol>
<li>lorem</li>
</ol>
```
* 说明列表
```
<dl>
<dt>导演:</dt>
<dd>王小明</dd>
</dl>
```

#### pre 标签
> 不改变文本格式,通常和 code 标签一起使用

#### base 标签
> 放在head标签中,body中的标签属性**未定义**的以 base 标签的属性为基准

#### head 标签
> 此标签里的内容将不在网页中显示

#### form 标签
> 表单标签,通常和输入框标签(input)组合使用
* 单行输入框
```
<form action="https://www.google.com/search">
    <h3>Google搜索</h3>
      <input type="text" placeholder="请输入想要搜索的内容" name="q">
      <!-- <input type="submit" value="在新窗口打开">  -->
      <button>在新窗口打开</button>
  </form>
```
* 可选框
可以与label标签一起使用,让文字可选框联系起来
```
<input type="radio" name="render" id="male"><label for="male">男</label>
<input type="radio" name="render" id="famale"><label for="famale">女</label>
<!-- <label><input type="radio" name="render">男</label> 
```
* 限定选择框
```
<select name="old">
  <option value="" selected hidden>请选择</option>
  <optgroup label="少年">
    <option value="1-6">1-6岁</option>
    <option value="6-12">6-12岁</option>
  </optgroup>
  <optgroup label="青年">
    <option value="12-18">12-18岁</option>
    <option value="18-14">18-24岁</option>
  </optgroup>
  <optgroup label="中年">
    <option value="24-30">24-30岁</option>
    <option value="30-16">30-36岁</option>
  </optgroup>
</select>
```

