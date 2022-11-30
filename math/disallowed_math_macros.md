## Things we don't allow users to do

## HTML

### Input tag:
$$\<script>{&lt;input&gt;<!--}$$

`$$\<script>{&lt;input&gt;<!--}$$`

### Button tag:
$$\<script>{&lt;button&gt;Test Button&lt;/button&gt;<!--}$$

`$$\<script>{&lt;button&gt;Test Button&lt;/button&gt;<!--}$$`

### Textarea tag:
$$\<script>{&lt;textarea&gt;Write something...&lt;/textarea&gt;<!--}$$

`$$\<script>{&lt;textarea&gt;Write something...&lt;/textarea&gt;<!--}$$`

### Svg tag:
$$\<script>{&lt;svg&gt;&lt;rect x=&quot;50&quot;&gt;&lt;/svg&gt;<!--}$$

`$$\<script>{&lt;svg&gt;&lt;rect x=&quot;50&quot;&gt;&lt;/svg&gt;<!--}$$`

$$ <svg>&lt;div class="something" data-url="url">hi&lt;/div></svg> $$

`$$ <svg>&lt;div class="something" data-url="url">hi&lt;/div></svg> $$`

### sneaky function
<p>I am evil $" onerror=\"alert(\'muahaha\')\"$</p>

```
<p>I am evil $" onerror="alert(\'muahaha\')"$</p>
```

### Image injection
$$
\\style{background-image:url("//i.imgur.com/nUwut25.jpeg");}{a}
$$

```
$$
\\style{background-image:url("//i.imgur.com/nUwut25.jpeg");}{a}
$$
```

### Cat wallpaper takes over the entire screen
$$
\\class{\\<style>* { display: none; } body, html { display: block !important; width:50%; height:50%; background: url(//raw.githubusercontent.com/cxcorp/test-2/main/cheezburger.jpg?token=GHSAT0AAAAAABPFR4MS6GAEVHASBFYWGSFUYUHVT5Q);}</style>}{a}
$$

```
$$
\\class{\\<style>* { display: none; } body, html { display: block !important; width:50%; height:50%; background: url(//raw.githubusercontent.com/cxcorp/test-2/main/cheezburger.jpg?token=GHSAT0AAAAAABPFR4MS6GAEVHASBFYWGSFUYUHVT5Q);}</style>}{a}
$$
```

### Invisible anchor
$$
\style{opacity:0;cursor:default;}{\href{//example.com/pwned}{\style{position:fixed;top:0;left:0;right:0;bottom:0;z-index:9999;}{\text{a}}}}
$$

```
$$
\style{opacity:0;cursor:default;}{\href{//example.com/pwned}{\style{position:fixed;top:0;left:0;right:0;bottom:0;z-index:9999;}{\text{a}}}}
$$
```

$$
\style{position:fixed;top:0;left:0;right:0;bottom:0;position:relative;box-shadow:0 0 500px 500px rgba(0,0,0,0.5);z-index:9999;}{
\begin{align}
\style{height:129px;font-family:sans-serif;}{\
\class{Box Box--overlay d-flex flex-column anim-fade-in fast}{\
\begin{align}
\style{position:absolute;left:0;right:0;}{\class{Box-header Box-title markdown-body}{\text{Account security compromised}}} \\
\style{position:absolute;left:0;right:0;top:24px;margin: 50px;}{\class{markdown-body}{\text{\href{\#}{\class{btn-primary btn}{Review security details}}}}} \\
\end{align}
}
}
\end{align}
}
$$

```
$$
\style{position:fixed;top:0;left:0;right:0;bottom:0;position:relative;box-shadow:0 0 500px 500px rgba(0,0,0,0.5);z-index:9999;}{
\begin{align}
\style{height:129px;font-family:sans-serif;}{\
\class{Box Box--overlay d-flex flex-column anim-fade-in fast}{\
\begin{align}
\style{position:absolute;left:0;right:0;}{\class{Box-header Box-title markdown-body}{\text{Account security compromised}}} \\
\style{position:absolute;left:0;right:0;top:24px;margin: 50px;}{\class{markdown-body}{\text{\href{\#}{\class{btn-primary btn}{Review security details}}}}} \\
\end{align}
}
}
\end{align}
}
$$
```

## newcommand

$\newcommand{\water}{H_2O}$

$\water$

```
$\newcommand{\water}{H_2O}$

$\water$
```

## def

$\( \def\sum_{{\bf R}} \def\bold#1{{\bf #1}} \)$

$\sum_{5}$

```
$\( \def\sum_{{\bf R}} \def\bold#1{{\bf #1}} \)$

$sum_$
```

## Physics


$\abs{5}$

`$\abs{5}$`


$\sine$

`$\sine$`


$\smallmatrixquantity$

`$\smallmatrixquantity$`


$\qty\Bigg{1}$

`$\qty\Bigg{1}$`


$\eval{x}_0^\infty$

`$\eval{x}_0^\infty$`


## Too many macros

$$\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{\sqrt{x}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}$$
