## API ENDPOINTS

<a href="https://paypal.me/lazarospsarokostas" rel="nofollow"><img src="https://camo.githubusercontent.com/d5d24e33e2f4b6fe53987419a21b203c03789a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d677265656e2e737667" alt="Donate" data-canonical-src="https://img.shields.io/badge/Donate-PayPal-green.svg" style="max-width:100%;"></a>

### All Posts
- Path : `/posts`
- Method: `GET`
- Response: `200`

### Create Post
- Path : `/posts/create`
- Method: `POST`
- Fields: `title, content`
- Response: `201`

### Details a Post
- Path : `/posts/{id}`
- Method: `GET`
- Response: `200`

### Update Post
- Path : `/posts/update/{id}`
- Method: `PUT`
- Fields: `title, content`
- Response: `200`

### Delete Post
- Path : `/posts/{id}`
- Method: `DELETE`
- Response: `204`
