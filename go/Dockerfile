FROM golang

COPY . .

WORKDIR /go

RUN go get github.com/gin-gonic/gin
RUN go get github.com/jinzhu/gorm

CMD ["go","run","main.go"]