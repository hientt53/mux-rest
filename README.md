# Simple Go Lang REST API with MUX
> Simple RESTful API to create, read, update and delete books. No databsae implementation yet

## Quick start

```bash
# Install mux route 
go get -u github.com/gorilla/mux
```

```bash
go build 
./mux-rest
```

## Endpoints

### Get All Books
```bash 
GET api/books
```

### Get Single Book
```bash 
GET api/books/{id}
```

### Create Book
``` bash
POST api/books

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Book Three",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }
```

### Update Book
``` bash
PUT api/books/{id}

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Updated Title",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }


