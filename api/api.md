# API

## list of API

| method | url | request | response | description |
| --     | --  | --      | --       | --          |
| POST  | /api/register | json | json | 注册用户 |

## request and response

### `/api/register`

request, 服务端需校验 user, passwd 合法性, 存储密码时须采用加密手段

```json
{
    "user":STRING,
    "passwd":STRING
}
```

response, status 为 true 表示注册成功, reason 为 "success"; 否则 status 为 false, 并给出可能的出错原因

```json
{
    "status":BOOL,
    "reason":STRING
}
```
