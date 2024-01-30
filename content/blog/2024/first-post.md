+++
title = '今更hugo'
date = 2024-01-30T17:50:15+09:00
categories = [ "develop" ]
tags = [ "hugo" ]
+++

## Introduction

業務では使用してましたが、個人のアウトプットする場として今更ながらの作成です

<!--more-->

## 環境構築

1. githug上にリポジトリ作成
1. フォルダ初期化

        hugo new site kensei.github.io
        cd kensei.github.io
        git init
        git remote add
        git submodule add https://github.com/vimux/mainroad.git themes/mainroad
1. hugo.tomlを修正

        theme = "mainroad"
1. 動作確認

        hugo server -D --buildDrafts

## 記事の作成

```
hugo new content blog/2024/first-post.md
```

## deploy

1. githubaction作成

        ```
        touch .github/workflows/hugo.yaml
        ```
1. 内容を修正（ほぼ[公式](https://gohugo.io/hosting-and-deployment/hosting-on-github/)通り)

## At the end

早い
