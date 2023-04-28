# rtfm
Asciidoc sources for doc-site http://rtfm.emc/

Compile to HTML for single file:
```
asciidoctor --backend=html5 -o ./index.html ./index.adoc
```



For multipage use this [extention](https://github.com/owenh000/asciidoctor-multipage) and the next command:

```
asciidoctor-multipage -D ./html ./index.adoc
```



AsciiDoc Language Documentation [here](https://docs.asciidoctor.org/asciidoc/latest/)