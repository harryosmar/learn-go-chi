# create project

```
mkdir init learn-go-chi && cd init learn-go-chi && git init learn-go-chi

git remote add origin git@github.com:harryosmar/learn-go-chi.git

// create go.mod file
go mod init

// download package and create go.sum
go get -u github.com/go-chi/chi/v5 
```

## run project 

```
# check gopath 
go env | grep GOPATH
go env | grep GOMOD

go mod download

go list -m all

go run main.go
```

