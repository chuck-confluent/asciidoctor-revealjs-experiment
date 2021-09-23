# Asciidoctor RevealJS Example

```bash
docker run --rm -it -v $PWD:/documents asciidoctor/docker-asciidoctor \
    asciidoctor-revealjs -a revealjs_theme=sky presentation.adoc
```