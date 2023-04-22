https の代わりに ssh を使用。
git config --add --global url."git@github.com:".insteadOf https://github.com
GOPROXY を direct に設定。
export GOPROXY=direct
GOPRIVATE にプライベートリポジトリを設定。
export GOPRIVATE=github.com/PRIVATE_REPO