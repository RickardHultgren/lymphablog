<script>
document.getElementById("indexsmall").style.backgroundColor="#EFAB00";
document.getElementById("indextext").style.color="#000000";
document.getElementById("index").className="menu2active";
</script>
A blog about the development of the programming language [LYMPHA](https://lympha.readthedocs.io/en/latest/). Two interpreters are being designed: an [on-line](http://rickardhultgren.github.io/lymphaonline/index) and an [off-line](https://lympha-interpreter.readthedocs.io/en/latest/).<br><br>
<span id="Rss" style="display:table;"> [<i class="material-icons" style="background-color:#EFAB00;color:#ffffff;font-size:1.5em;margin-top:.5em; margin-bottom:-.5em;display: table-cell;vertical-align: middle;">&#xE0E5;</i><span style="vertical-align: middle;display:table-cell;">&nbsp;atom feed </span> ]({{site.baseurl}}/atom.xml)</span>
<br><br>
<a href="{{site.baseurl}}/tags">tag list</a>
<br><br>
{% for post in site.posts %}
{{ post.date | date_to_string }} &raquo; <a href="/lymphablog{{post.url}}">{{ post.title }}</a>
{% endfor %}

