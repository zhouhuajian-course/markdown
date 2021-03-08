<!-- 
Markdown 6种强调写法 
https://daringfireball.net/projects/markdown/syntax#em 
-->

<!-- 
Markdown将星号（*）和下划线（_）视为重点指示。用*或_包裹的文本将带有HTML<em>标记；double*或_会被HTML<strong>标签包裹 。
-->

<!-- 两种斜体写法 em标签 -->

*这是斜体*

_这是斜体_

<!-- 两种粗体写法 strong标签 -->

**这是粗体**

__这是粗体__

<!-- 注意点：em strong标签是行内标签，在Markdown中通常会嵌入在块级标签里面。 -->

<!-- 两种粗斜体写法 strong标签 里面嵌入em标签 -->

***这是粗斜体***

___这是粗斜体___

<!-- 
注意点：
强调可以用在单词的中间：
un*frigging*believable
但是，如果用*或包围_空格，则将其视为文字星号或下划线。
要在原本会用作强调定界符的位置产生文字星号或下划线，可以反斜杠对其进行转义：
\*this text is surrounded by literal asterisks\*
-->

un*frigging*believable

un* frigging*believable

\*this text is surrounded by literal asterisks\*

<!-- 
注意点：有些Markdown解析器没有完全按照官网的解析逻辑，即使单词中间有下划线或双下划线包裹也不会解析成strong或em标签，而是解析成下划线本身。可使用星号语法进行替换。
-->

un_frigging_believable