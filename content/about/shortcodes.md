+++
title = "Shortcodes"
date = 1925-02-04
+++
Here is a YouTube video:
<center>
{{youtube(id="tDqTXipQmBU", autoplay=true)}}
</center>


As someone said:

{% quote(author="Castro,Henrique") %}
Blah Blah Blahh
{% end %}

<table>
  <tr>
    <th></th>
    <th>Tables</th>
    <th>Are</th>
    <th>Cool</th>
  </tr>
  <tr>
    <th>Zebra</th>
    <td>Stripes</td>
    <td>Are</td>
    <td>Pretty</td>
  </tr>
  <tr>
    <th>Body</th>
    <td>Is</td>
    <td>Another</td>
    <td>Row</td>
  </tr>
</table>
<p style="cursor: url(https://raw.githubusercontent.com/riggraz/no-style-please/master/logo.png), context-menu;">The cursor is pointing at this paragraph!</p>
<nb-admonition type="tip" role="group" aria-labelledby="admonition_1">
    <nb-admonition-title id="admonition_1">
        Title
    </nb-admonition-title>
    <p>
    	<b>Body</b> body body
    </p>
</nb-admonition>


>### Usage  ![rust](/rust-16x16-en.png)
>```rs
>{%/* katex(block=false) */%} e^{i\pi}+1=0 {%/* end */%}
>```
>### Output 
>```html
>{% katex(block=false) %} e^{i\pi}+1=0 {% end %}
>```
>{% katex(block=false) %} e^{i\pi}+1=0 {% end %}

  <div class="box-purple">
