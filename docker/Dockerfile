FROM  golang:1.17.2

COPY  main.go .
ARG   SKAFFOLD_GO_GCFLAGS
RUN   go build -gcflags="${SKAFFOLD_GO_GCFLAGS}" -o /app main.go

ENV   GOTRACEBACK=single
CMD   ["/app"]
