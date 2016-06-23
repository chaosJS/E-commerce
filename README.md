# E-commerce#
@chaos_JS
<hr>
一个小的电商项目

### 项目杂记： ###
1. IE6双边距问题
	1. 为浮动元素添加display: inline
2. IE8中input元素文字偏上偏下
	1. 设置inlineheight 和height

3. 3像素问题 使用float引起的 使用dislpay:inline -3px
4. 下一个兄弟元素：+

		.product_info .btn_num +span{
		line-height: 45px;
		}

5. 图片居中：

		img{display:block; margin:0 auto;}
		//仅仅是多种方法之一

6. 善用width：20%；百分比宽度，在均分时很方便
7. 看一下bootstrap是怎么清除前后浮动的

		div:before{
		    display: table;
		    content: " ";
		}

		div:after {
		    clear: both;
		}

		------------------------常用的清除浮动方法
		.clearfix:after{content:'\0020';display:block;height:0;clear:both;visibility:hidden}
		.clearfix{*zoom:1}


8. b:nth-of-type(3){}//特定类型的第 N 个子元素