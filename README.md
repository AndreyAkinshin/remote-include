remote-include
==============

A remote include plugin for Jekyll.

It's like {% include file.html %} but instead of grabbing files from your _includes directory it gets the file from a remote URL.

```
{% remote_include http://static.2inspire.co.uk/img/articles/vector.svg %}
```

I personally use this for embedding SVGs that we host on a static domain (as you can see).

## Pull requests welcome

I did the bare minimum to get this working, plus it's the only thing I've ever written in Ruby so I have no idea what I'm doing.
