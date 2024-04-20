## mwx-official-site-hugo
The blog site of Matrixworks that powered by Hugo with theme hugo-clarity

[Product site](htts://matrix.works/blog)

### Dependencies
1. [Hugo - A fast and flexible static site generator](https://github.com/gohugoio/hugo)
2. [Theme - Hugo Clarity MWX](https://github.com/iveteran/hugo-clarity-mwx.git)

### Install Hugo
```shell
CGO_ENABLED=1 go install -tags extended github.com/gohugoio/hugo@latest
```

### Clone repository and theme
```shell
git clone --recurse-submodules https://github.com/iveteran/mwx-official-site-hugo.git
```

### Run
```shell
cd mwx-official-site-hugo
hugo server -D
```

### Screenshots
![Blog list](https://github.com/iveteran/mwx-official-site-hugo/blob/main/screenshots/home.png?raw=true)
![Blog list - light style](https://github.com/iveteran/mwx-official-site-hugo/blob/main/screenshots/light-mode.png?raw=true)
![About page](https://github.com/iveteran/mwx-official-site-hugo/blob/main/screenshots/about.png?raw=true)
![Post content](https://github.com/iveteran/mwx-official-site-hugo/blob/main/screenshots/post.png?raw=true)
