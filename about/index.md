---
title: 关于
layout: page
comments: no
---

{{ site.about }}

----

###其他

{% if site.qq %}
ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
{% endif %}
网站：[{{ site.name }}]({{ site.url }})

邮箱：[{{ site.email }}](mailto:{{ site.email }})

GitHub : [http://github.com/{{ site.github }}](http://github.com/{{ site.github }})

----


[![新浪微博](http://service.t.sina.com.cn/widget/qmd/{{ site.weibo }}/f78fbcd2/1.png)](http://weibo.com/u/{{ site.weibo }})
