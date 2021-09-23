# Asciidoctor RevealJS Example

## Create a presentation from an adoc

```bash
docker run --rm -it -v $PWD:/documents asciidoctor/docker-asciidoctor \
    asciidoctor-revealjs presentation.adoc -o index.html
```

## See result

Clone this repo and open presentation.html in a browser.

Notice it has a confluent branded theme, code highlighting, a copy button, and a navigation menu.