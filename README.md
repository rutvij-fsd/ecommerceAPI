
# ecommerceAPI

Design an API for an ecommerce platform admin to manage product inventory
## Tech Stack



**Server:** Node, Express, MongoDB


## API Reference

#### Get all items

```http
  GET /products
```

#### Create a Product

```http
  GET /products/create
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `name`      | `string` | **Required**. |
| `quantity`      | `number` | **Required**.  |


#### Delete a Product

```http
  GET /products/:id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. in params|

#### Update a Product

```http
  GET /products/:id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. in params|
| `quantity`      | `number` | **Required**. in body|

## Author

- [@RutvijPatel](https://github.com/rutvij-fsd)

