# canvas-action

> Call a third party API from Canvas

## Examples

### GET request

`canvasApi name="jsonplaceholder" api={string "https://jsonplaceholder.typicode.com/posts/" {urlparam variable="postNumber" default="2" } } label="Get comments"`

### POST request 

`canvasApi name="reqres" method="POST" body="{'name':'bob', 'job':'painter'}" api="https://reqres.in/api/users" label="Create User"`
