## Surge.app Conf Builder by Preprocess

> Inspired by [@janlay](https://gist.github.com/janlay/b57476c72a93b7e622a6) and rules from [@scomper](https://gist.github.com/scomper/b0c6129840272c136a82).

### Install

1. `npm install`
   
2. Modify or create `config/*.conf` files, you can use [preprocess directives](https://github.com/jsoverson/preprocess#all-directives) to set build conditions.
   
3. Modify or create `context.json` to set context variables, in which `srcDir` should be the path of all `@include` files.
   
4. Use `$ preprocess index.conf -f coffee -c context.json > surge.conf` to build configuration file.
   