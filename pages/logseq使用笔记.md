- {{renderer :tocgen2}}
- # Markdown 相关
	-
	- 粗体 __粗体__ ； 斜体 *斜体*；高亮 ==高亮== 删除线 ~~删除线~~
	  id:: 65bcc416-aaaa-4495-84cd-4e1ca7bf0927
	- 下划线 <u>下划线         </u> `<u></u> ` or <ins>23213        </ins> `/underline`
	- emoji表情 `win+.`或者`/emoji picker`
		- <https://www.emojiall.com/zh-hans>
	- 代码  `C:\Users\XXX\.logseq`）
		- 代码块
			- ```json
			  QWE
			  
			  
			  ```
	- 数学表达式 #.v-kanban
		- 上标  <sup>2</sup> `<sup></sup>`
		  id:: 65bcc7f9-4f7b-42a0-ab1d-ec3a463ca898
		  X^{super} `X^{super}`
		- 下标  <sub>2</sub> `<sub></sub>`
		  X_{sub} `X_{sub}`
	-
	- \$E=mc^2$   $E=mc^2$
	- 嵌套引用
		- >1
		  >>2 ==此处块内换行==
	- 转义 \
	- 链接 \[名称](地址)"title"; <URL>;
		- 引用链接绝对路径：[[书名模板]]
	- ------
	- 有序  列表
	- 3423
	  logseq.order-list-type:: number
	- 121424
	  logseq.order-list-type:: number
	- ds
	  logseq.order-list-type:: number
	- sdas
	  logseq.order-list-type:: number
	- logseq.order-list-type:: number
	- >逆天
	-
	- 无序 列表
	  + First item
	  + Second item
	  + Third item
	  + Fourth item
	  * f
	- >必须^^块内换行^^,且第一行不会作为无序
-
- # 快捷键部分 (可在软件内修改)
	- ## 格式部分 #.v-kanban
		- `Ctrl+B` **加粗**
			- `Ctrl+s` ~~删除线~~
			- `Ctrl+i` *斜体*
				- `Ctrl+shift+H`  ==高亮==
		- `Ctrl+L` [微软微软](https://baidu.com "逆天")  \[微软微软](https://baidu.com "逆天") ==html链接==
			- >记得切换输入法 防止快捷键冲突
	- ## 切换/关闭部分
		- 左边栏 `tl`  ;右边栏`tr`;目录 `f12`
		- 切换块为序数: 选中块,`tn`;
		- 切换宽屏 `tw`；切换文档模式 `td`
	- ## 触发
		- 页面引用/新建页面
			- > [[]]
		- 块引用/新建块
			- >(())
-
- # 模板使用
  collapsed:: true
	- `/template`
	- [[看板模版1]] #.v-kanban
	  template:: 看板模版
	  id:: 65bc9ba8-ddc8-4534-8dd4-c345fdca054c
		- A
			- 1
			  collapsed:: true
				- 1.1
			- 2
			  collapsed:: true
				- 2.1
			- 3
			  collapsed:: true
				- 3.1
		- B
			-
			- 1
			- 2
			- 3
		- C
	- template:: 223
	  collapsed:: true
	  232424
		- 2332
	- \[[书名]](file:///)
	  template:: 书名模版
-
-
- # 插件使用
	- logseq-bullet-threading
	- logseq-agenda
	- logseq-heatmap
	- logseq-emoji-picker-fork
	- logtools
	- logseq-tags
	- logseq-mark-map crtl+shift++alt+m
	- logseq-luckysheet
	- logseq-wordcount-plugin
	- logseq-tocgen
	- logseq-toc-plugin
	- logseq-tabs
	- logseq-wrap
	- logseq-live-math:`Ctrl+shift+m`