---
layout: post
title:  "Python texto vs shell"
author: "Iury Xavier"
date:   2016-07-28
categories: python
---

**Markdown**

``` python
1 print "hello word!"
```

{% highlight python %}

>>> def print_hi(name):
>>>     return "Hi," + name
>>> print_hi('Tom')
 Hi, Tom
>>>

{% endhighlight %}

{% highlight python linenos %}

def print_hi(name):
    return "Hi," + name
print_hi('Tom')

{% endhighlight %}