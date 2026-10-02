# API examples

## Register
```http
POST /api/auth/register
Content-Type: application/json

{"name":"Aniska K","email":"aniska@example.com","password":"secret123"}
```

## Login
```http
POST /api/auth/login
Content-Type: application/json

{"email":"aniska@example.com","password":"secret123"}
```

Copy the returned `token` and use it as:

```http
Authorization: Bearer YOUR_TOKEN
```

## Create a post
```http
POST /api/posts
Authorization: Bearer YOUR_TOKEN
Content-Type: application/json

{"title":"My first post","content":"Hello from my full-stack blog!"}
```

## Add a comment
```http
POST /api/posts/1/comments
Authorization: Bearer YOUR_TOKEN
Content-Type: application/json

{"content":"Great post!"}
```
