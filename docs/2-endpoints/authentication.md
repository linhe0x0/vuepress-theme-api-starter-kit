<Block>

# Authentication

</Block>

<Block>

## Login

You can use this API to login the application with your account.

### Endpoint

```bash
POST /auth/login
```

### Parameters

|   Name   |  Type  | Description |      Required      |
| :------: | :----: | :---------: | :----------------: |
| username | string |  username   | :heavy_check_mark: |
|  phone   | string |    phone    | :heavy_minus_sign: |
| password | string |  password   | :heavy_check_mark: |

### Response

```json
Status: 200

{
  "username": "username",
  "email": "email"
}
```

<Example>

<CURL>
```bash
curl -X POST http://api.example.com/auth/login \
  --data '{
    "username": "my-username",
    "password": "my-password"
  }'
```
</CURL>

</Example>

</Block>

<Block>

## Signup

You can use this API to signup the application with your account.

### Endpoint

```bash
POST /auth/signup
```

### Parameters

|   Name   |  Type  | Description |      Required      |
| :------: | :----: | :---------: | :----------------: |
| username | string |  username   | :heavy_check_mark: |
|  phone   | string |    phone    | :heavy_check_mark: |
| password | string |  password   | :heavy_check_mark: |

### Response

```json
Status: 200

{
  "username": "username",
  "email": "email"
}
```

<Example>

<CURL>
```bash
curl -X POST http://api.example.com/api/auth/login \
  --data '{
    "username": "my-username",
    "password": "my-password"
  }'
```
</CURL>

</Example>

</Block>
