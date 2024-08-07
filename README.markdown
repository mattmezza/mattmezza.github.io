[web](https://github.com/mattmezza/web)
===

This repo works in conjunction with [mattmezza/mattmezza.github.io](https://github.com/mattmezza/mattmezza.github.io).

Before starting editing within the context of this repo, please clone the above mentioned one.

```
git clone ...mattmezza/mattmezza.github.io...
cd mattmezza.github.io
serve .
```

You can then cd back into the this repo and start editing the content. You can build the website by running:
```
make
```

Note: both this repo and `mattmezza.github.io` need to be cloned in the same level directory. See `Makefile` in this repo to understand why.


### Usage with tailwindcss

- `npx tailwindcss -i input.css -o style/global.css --watch`
- `cd ../mattmezza.github.io && npx live-server .`
