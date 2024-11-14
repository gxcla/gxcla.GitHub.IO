---
layout: default
title: GXC.LA
---

Hi there, I  am an open-source enthusiast, an [Open Source][oss] enthusiast. This site is
dedicated to providing information about [me](resume.html) and [what I do](/work).

I am a screencastr at <https://GXC.LA>.


<p><br /><b>My Note:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><b>Find me on:</b></p>

<ul>
<li><a href="https://github.com/gxcla/">Github</a></li>
</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>
Life is short, enjoy it in time
</blockquote>

[oss]:http://en.wikipedia.org/wiki/Open_source
