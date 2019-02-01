+++
date = "2017-04-10T16:42:50+01:00"
draft = false
weight = 180
description = ""
title = "Empty struct in golang"
bref = "A demo to collapsable elements"

+++


<h3 class="section-head" id="h-base"><a href="#h-base">Empty struct has no memory foot print</a></h3>
<pre class="prettyprint">
emptyStruct := struct{}{}
println(unsafe.Sizeof(emptyStruct))

output: 0
</pre>
