# Assignment 01 - Research Repository

Recently I started to learn Python by myself. I found Python is very powerful which has been widely used for Web development, Automated operation and maintenance，Web Crawler，Data analysis, scientific computing, AI, finance, games and other fields.I have big interest in Python, and tried to learn coding.

## A collection of your own code


The attached codings named *01 Practise coding of the course* I created are based on the Roman's questions through lectures, such as *calculate Human's year to dog's age*.


## Code that you've been inspired by 


After practicing Python continuously, I found that writing code in Python can actually draw some simple images. I am paricularly interested in this. I learned how to draw images in Python on the Internet and YouTube, and learned how to draw a python by 'importing turtle' in Python. Please see the files named *02 Draw a python with Python* and *output-Drawing a python with Python*.


Then I tried to draw a cute panda in Python which I really enjoyed. Please find the attached coding named *03 Draw Panda Using Turtle Graphics* and *03 output-Draw Panda Using Turtle Graphics*.


## Things that you think are interesting or just don't understand (with comments) 

The other thing I'm most interested in with Python is the **web crawler**.


I searched on google, web crawler (also known as web spider) is a program or script that automatically crawls information on the World Wide Web according to certain rules.

The Python crawler architecture is mainly composed of five parts, namely scheduler, URL manager, web page downloader, web page parser, and application (valuable data crawled).
调度器：相当于一台电脑的CPU，主要负责调度URL管理器、下载器、解析器之间的协调工作。
URL管理器：包括待爬取的URL地址和已爬取的URL地址，防止重复抓取URL和循环抓取URL，实现URL管理器主要用三种方式，通过内存、数据库、缓存数据库来实现。
网页下载器：通过传入一个URL地址来下载网页，将网页转换成一个字符串，网页下载器有urllib2（Python官方基础模块）包括需要登录、代理、和cookie，requests(第三方包)
网页解析器：将一个网页字符串进行解析，可以按照我们的要求来提取出我们有用的信息，也可以根据DOM树的解析方式来解析。网页解析器有正则表达式（直观，将网页转成字符串通过模糊匹配的方式来提取有价值的信息，当文档比较复杂的时候，该方法提取数据的时候就会非常的困难）、html.parser（Python自带的）、beautifulsoup（第三方插件，可以使用Python自带的html.parser进行解析，也可以使用lxml进行解析，相对于其他几种来说要强大一些）、lxml（第三方插件，可以解析 xml 和 HTML），html.parser 和 beautifulsoup 以及 lxml 都是以 DOM 树的方式进行解析的。
应用程序：就是从网页中提取的有用数据组成的一个应用
這是一門當下最流行且非常有前景的技術，在以後的學習當中，我會放更多的注意力在網絡爬蟲學習上。
