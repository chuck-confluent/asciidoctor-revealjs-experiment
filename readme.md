# Asciidoctor RevealJS Example

## Create a presentation from an adoc

```bash
docker run --rm -it -v $PWD:/documents asciidoctor/docker-asciidoctor \
    asciidoctor-revealjs presentation.adoc -o index.html
```

## See result

Clone this repo and open presentation.html in a browser.

Notice it has a confluent branded theme, code highlighting, a copy button, and a navigation menu.

## Font size of code blocks

I thought the font size of code blocks was too small. I did some digging with the browser development tools and found that the knob for that appears to be `.codeblock pre` in `copycode.css` from the copycode extension. Fiddle with that to get the code blocks the size you want. I'm no frontend developer, so this might be the wrong way to go about it.