# elixir
elixirm命令
### 官方教程
[官方教程](https://docs.elixir.xyz/running-an-elixir-validator)
### 更新命令
```
docker kill elixir
docker rm elixir
docker pull elixirprotocol/validator:v3
```
### 启动命令
```
docker run -d \
  --env-file /root/validator.env \
  --name elixir \
  -p 17690:17690 \
  elixirprotocol/validator:v3
```
