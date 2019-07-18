## Hugo Install
 `https://gohugo.io/getting-started/installing/`の写し
### Macでのインストール
1. Golangのインストール:  
`brew install go`

1. HomebrewでHugoを取得:  
`ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go/install)"`

1. Hugoのインストール:  
`brew install hugo`

### Linuxでのインストール
1. Golangのインストール:  
https://golang.org/doc/install

1. Snapdのインストール
https://docs.snapcraft.io/installing-snapd

1. Hugoのインストール
https://gohugo.io/getting-started/installing/#linuxbrew-linux


## Hugoの仕組みの理解
Hugoのレイアウトとコンテントの関係
https://ousttrue.github.io/hugo/hugo_layout/


# CircleCIノウハウ
1. 下記エラーが出た際には、Rebuildすれば多分問題ない（7月12日1回発生）  
`fatal error: concurrent map read and map write`  
 https://circleci.com/gh/sbcloud/help/118
 からの  
 https://circleci.com/gh/sbcloud/help/119