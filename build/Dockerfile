# goバージョン
FROM golang:1.18.3-alpine
# アップデートとgitのインストール！！
RUN apk add --update &&  apk add git
# appディレクトリの作成
RUN mkdir /go/src/app
# ワーキングディレクトリの設定
WORKDIR /go/src/app
# ホストのファイルをコンテナの作業ディレクトリに移行
ADD ./hello /go/src/app 
#install
#RUN go get
