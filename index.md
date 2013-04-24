---
layout: page
title: FKL2000
---
<p id="top"></p>
{% include JB/setup %}
<table width="100%">
    <tr>
        <td><a href="#posts">文章</a></td>
        <td><a href="#links">链接</a></td>
        <td><a href="./Downloads">下载</a></td>
        <td><a href="#contact">联系方式</a></td>
    </tr>
</table>
----------------------------------

<p id="posts"></p>
<a name="posts"></a>
## 我的文章 


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



<p id="links"></p>
<a name="links"></a>
##Links 

- [Google][1]
- [Downloads][4]


  [1]: http://google.com/         "Google"
  [4]: ./Downloads                "Downloads"

<p id="contact"></p>
<a name="contact"></a>
##Contact Info   
- [E-Mail: fkl2000@gmail.com][11]
  [11]: mailto:fkl2000@gmail.com    "E-mail"
- [Phone: +1(289)588-7111][12]
  [12]: tel:+1(289)588-7111        "Phone"
******************************
<!-- BEGIN: Powered by Supercounters.com -->
<script type="text/javascript" src="http://widget.supercounters.com/texthit.js"></script>
<script type="text/javascript">var sc_texthit_var = sc_texthit_var || [];sc_text_hit(548097,"","000000");</script>
<!-- END: Powered by Supercounters.com -->
<!-- END: Powered by Supercounters.com -->
<p id="bottom"></p>
+ [Top](#top)
