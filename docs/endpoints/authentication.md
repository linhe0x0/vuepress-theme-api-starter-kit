<Block>

# Authentication

</Block>

<Block>

## Login

You can use this API to login the application with your account.

### Endpoint

```bash
POST /api/auth/login
```

### Parameters

| Name | Type | Description | Required |
| :-: | :-: | :-: | :-: |
| username | string | username | :heavy_check_mark: |
| password | string | password | :heavy_check_mark: |

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
