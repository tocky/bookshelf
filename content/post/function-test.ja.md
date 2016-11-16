+++
title = "Hugo の機能をテストするページ"
draft = false
date = "2016-11-16T14:32:24+09:00"
image = "502ca1ac68000babc9dbcbb4ced4e16e.jpg"
+++

{{< ref "terms.ja.md" >}}

{{< relref "terms.ja.md" >}}

{{< relref "terms.en.md#tldr" >}}

{{< tweet 666616452582129664 >}}

{{< speakerdeck 4e8126e72d853c0060001f97 >}}

{{< greet "Shin Tokiwa" >}}

``` html
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```
