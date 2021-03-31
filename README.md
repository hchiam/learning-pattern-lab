# Learning Pattern Lab

Just one of the things I'm learning. <https://github.com/hchiam/learning>

<https://patternlab.io>

<https://github.com/pattern-lab/patternlab-node>

```bash
npm create pattern-lab
# will use the pattern-lab initializer
```

- BTW: `npm create` is an alias for `npm init` <https://stackoverflow.com/a/57133248> so you could run `npm init pattern-lab` instead.

(Note: the `/public` folder is auto-generated, [as well as some other files](https://github.com/hchiam/learning-pattern-lab/commit/0432a3ceb19c707b4acb22a0f9625386f5f6cf6a).)

For templating syntax, I prefer [Handlebars](https://handlebarsjs.com/guide/) over [Twig](https://twig.symfony.com/).

View patterns: `npm run pl:serve`

Patterns be here: `/source/_patterns`

You can edit the files and the page will reload, and auto-generate the HTML.

You can edit CSS here and see on live reload: `/source/css/style.css` ([See example commit](https://github.com/hchiam/learning-pattern-lab/commit/84245c830019839daea654395179cf3b357f4f90).)

You can add a pattern by simply adding a new file under ` source/_patterns` ([see example commit](https://github.com/hchiam/learning-pattern-lab/commit/4276c09719a91eb581ac36dc2291edf272d27c72)), and it'll auto-generate the menu, title, expandable tab, HTML code, etc.
