# Favicon generator

Little bash tool for generating favicons.

### Prerequisites

- [ImageMagick](https://www.imagemagick.org/) - download [here](https://www.imagemagick.org/script/download.php) or use homebrew

### How to use

- copy your PNG favicon (minimum size 196x196) to this catalog and rename it to `favicon-master.png`
- run

```bash
$ ./generate
```

- copy all files from `output` catalog to your application
- copy html code from `code.html` to HEAD html section of your application and modify href's to match your application structure

