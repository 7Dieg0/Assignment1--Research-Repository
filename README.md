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

 - The Python crawler architecture is mainly composed of five parts, namely scheduler, URL manager, web page downloader, web page parser, and application (valuable data crawled).
   - Scheduler: Equivalent to the CPU of a computer, it is mainly responsible for scheduling the coordination among the URL manager, downloader, and parser.
   - URL Manager: It includes the URL address to be crawled and the URL address that has been crawled to prevent repeated URL crawling and loop crawling of URLs. There are three main ways to implement the URL manager: memory, database, and cache database.
   - Web page downloader: Download a web page by passing in a URL address and convert the web page into a string. The web page downloader has urllib2 (Python official basic module), including the need for login, proxy, and cookies, requests (third-party package).
   - Web page parser: By parsing a web page string, we can extract our useful information according to our requirements, or parse it according to the parsing method of the DOM tree. The web page parser has regular expressions (intuitively, convert web pages into strings to extract valuable information by fuzzy matching, when the document is more complex, this method will be very difficult to extract data), html. parser (that comes with Python), beautifulsoup (a third-party plugin, which can be parsed using html.parser that comes with Python, or lxml, which is more powerful than others), lxml (third-party plugins) , can parse xml and HTML), html.parser and beautifulsoup and lxml are all parsed in the way of DOM tree.
   - Application: an application consisting of useful data extracted from web pages.





這是一門當下最流行且非常有前景的技術，在以後的學習當中，我會放更多的注意力在網絡爬蟲學習上。
