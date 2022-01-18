# owasp-kubernetes

To LOCALLY make a presentation into a PDF:

```
$ npx @marp-team/marp-cli@latest ch1-2.md -o ch1-2.pdf
```

Alternatively, just use docker:

```
docker run --rm --init -v $PWD:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli ch1-2.md --pdf
```