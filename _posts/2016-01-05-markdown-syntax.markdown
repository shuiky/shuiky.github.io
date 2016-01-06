---
layout: post
title:  "Markdown Syntax"
date:   2016-01-05 23:50:00 +0900
categories: jekyll development
comments: True
---

plain text로 웹사이트나 블로그를 만들 수 있는 [jekyll](http://jekyllrb.com){:target="_blank"} 에서 사용하는 Markdown.   
[Markdown](https://en.wikipedia.org/wiki/Markdown){:target="_blank"}은 John Gruber(1973년생)가 2004년 만든 lightweight markup language 이다.   
일반 텍스트 문법으로 설계되어 읽거나 쓰기 쉽고 Markdown Tool(Markdown은 일반 텍스트 문법과 소프트웨어 툴이라는 2가지의 의미가 있음)을 이용해서 HTML이나 다른 포맷으로 전환이 가능하다.      
종종 readme 파일 등에 쓰인다.  

Markdown의 최대 장점은 가독성이다. tag가 포함된 Markup이나 폰트, 글자크기 등 서식을 위한 부분이 포함된 포맷보다 Markdown은 가독성이 한층 향상된다
전환하는 툴은 Perl 스크립트로 작성되었다.   


다음은 일부 문법들이다.

Header
----
---
<br/>

{% highlight text %}
A First Level Header
====================
{% endhighlight %}

위 내용은 아래와 같이 표시된다.

A First Level Header
====================

<br/>
<br/>

List
----
---
<br/>
{% highlight text %}
*   Red
*   Green
*   Blue
{% endhighlight %}

*   Red
*   Green
*   Blue

{% highlight text %}
1.   Red
2.   Green
3.   Blue
{% endhighlight %}

1.   Red
2.   Green
3.   Blue

<br/>
<br/>

Code Syntax Highlight
----
---
<br/>

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

<br/>

---
<br/>
더 자세한 문법들은 [링크](http://daringfireball.net/)를 통해 확인해보세요

<br/>

####Makrdown Tutorial
<iframe width="560" height="315" src="https://www.youtube.com/embed/6A5EpqqDOdk" frameborder="0" allowfullscreen></iframe>

<br/>
<br/>
<br/>

####참고
[kramdown syntax](http://kramdown.gettalong.org/syntax.html){:target="_blank"}   
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines){:target="_blank"}