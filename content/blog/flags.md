+++
title = "Flags"
date = 2023-11-25
+++
# How to create (country) Flags in <i>CSS</i> 
## To create a dutch flag we should do the following:
+ create a css file where you will put your flags
+  + mkdir css
+ + vim box.css

<center><strong>spaghetti code has been detected</strong></center>

>CSS
> ```css
>.box-flag-parent {
>   border: 1px solid black;
>   margin: 1rem;
>   padding: 2rem 2rem;
>   text-align: center;
>}

>```css
>.box-flag-child-dutch {
>   display: inline-block;
>   background: #fff;
>   max-width: 200px;
>   margin:  auto;
>   box-shadow: -11px 9px 0px 0px rgba(71,27,119,0.84);
>   border-top: 40px solid #fb2323;
>   border-bottom: 35px solid #5350ff;
>   padding: 1rem 4rem;
>   vertical-align: middle;
>}
>.box-flag-child-russian {
>   display: inline-block;
>   background: #5350ff;
>   max-width: 200px;
>   margin:  auto;
>   box-shadow: -11px 9px 0px 0px rgba(71,27,119,0.84);
>   border-top: 40px solid #fff;
>   border-bottom: 40px solid #fb2323;
>   padding: 1rem 4rem;
>   vertical-align: middle;
>}
>``` 
 
>HTML 
>```html
><br> 
><br>
>
><div class='box-flag-parent'>
>  <div class='box-flag-child-dutch'></div>
>     <br>
>     <br>
>     <hr>
>     <br>
>  <div class='box-flag-child-russian'></div>
></div>
>```

<br>
<br>

<div class='box-flag-parent'>
  <div class='box-flag-child-dutch'></div>
  <br>
  <br>
  <hr>
  <br>
  <div class='box-flag-child-russian'></div>
</div>

