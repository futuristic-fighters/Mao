# Mao

![](https://github.com/dxiaoqi/Mao/blob/master/mao.png)


  Mao是一款个人简历快速部署工具，采用json配置的方法，可以快速将HTML模版页进行数据填充与模块伸展，这将意味你只需要简短的HTML代码与布局方式，就可以快速   获取到精美的个人简历。
  
  
```json
	". ban":[{
			"说明":["$1里的内容" ,"$2里的内容","$3里的内容","$4的"]
			},
			{
			"说明":["#name  +title -**** -*****","",""]
			}]
```
  通过使用.或者#来获取到DOM中的class与id,并且获取
```html
<div class="ban">
  <h2>$1</h2>
  <p>$2</p>
  <blockquote>$3$4</blockquote>
</div>
```
#优势
Mao是专门处理单页面的工具，暂不支持多页面配置，相较与Vue React,Mao更加小巧，而且最主要的是，根本不需要什么API，你就可以很快上手使用，并且制作出精美的个人简历或者单页面产品。
