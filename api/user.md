# User API Request/Response

 - [Create](#create)
 - [Delete](#delete)

## Create

POST /api/v1/users

### Request

```json
{
	"name": "username",
	"email": "email@example.com",
	"password": "password"
}
```

### Response

```json
{
    "success": true
}
```

## Delete

Required: `LOGIN`

DELETE /api/v1/users

### Response

```json
{
    "success": true
}
```
