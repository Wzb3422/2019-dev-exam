# API 文档

## 获取 token

### Request

Request Header

```text
url: https://os.ncuos.com/api/user/token
Method: POST
Content-Type: application/json
```

Request body:

```json
{
  "username": "学号",
  "password": "云家园密码"
}
```

### Response

如果密码正确，会返回一个 `JSON` 格式的数据，里面有 `token` 字段。

## 凭 token 获取个人信息

### Request

Request Header

```text
url: https://os.ncuos.com/api/user/profile/basic
Method: GET
Authorization: passport {token}
Content-Type: application/json
```

### Response

返回 `JSON` ，带有个人信息。
