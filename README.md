# tiktok_api_server
> Register a new Device to get a device_id and install_id for TikTok

> API request header parameter generation (x-gorgon, x-khronos)

### TikTok Android APP

#### Device information registration (install_id, device_id, openudid...)
``` json
# http://tiktok.h1code2.cn/api/v1.0/device_register
{
  "code": 0,
  "message": "request is ok",
  "data": {
    "server_time": 1639926503,
    "device_id": 7043430346466362885,
    "install_id": 7043430597058955013,
    "device_id_str": "7043430346466362885",
    "install_id_str": "7043430597058955013",
    "new_user": 1
  }
}
```

#### API request header parameter generation (x-gorgon, x-khronos)
``` json
# http://tiktok.h1code2.cn/api/v1.0/security?uri=
{
  "code": 0,
  "message": "request is ok",
  "data": {
    "x-gorgon": "036141108000fde7ce29b51fbe74c6b04a86b996c439f9f1af0c",
    "x-khronos": "1639925016"
  }
}
```
#### wechat: wx_h1code2.cn

#### api-site: [tiktok.h1code2.cn](http://tiktok.h1code2.cn)

