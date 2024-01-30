# kensei.github.io

## site create

```
hugo new site kensei.github.io
git submodule add https://github.com/vimux/mainroad.git themes/mainroad
```

## set theme

https://gohugo.io/getting-started/quick-start/

`config.toml `

```
theme = "mainroad"
```

## run server

```
hugo server -D
```

## add content

```
hugo new content blog/2024/first-post.md
```

## submodule update

```
git submodule update --init --recursive
```
