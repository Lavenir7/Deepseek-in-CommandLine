# deepseek-V3 in command line

## 文件备注

| 文件         | 说明          |
| :-:          | :-:           |
| chat         | 聊天对话      |
| ask          | 单次询问      |
| checkBalance | 查询账户余额  |
| tokenizer    | 离线分词器    |

## 使用说明

### 安装依赖
```sh
pip install -r requirements
```

### 导入api key
首先将你的 `api key` 写入 `assets/keys/apikey` 文件中
[如何获取 `deepseek` 的 `api_key`](./docs/get_deepseek_apikey.md)

### chat
```sh
./chat # 开启聊天（聊天中使用 /? 查看聊天内命令）
./chat -h # 查看全部使用方法
```

### ask
```sh
./ask "请介绍你自己" # 单次询问
./ask -h # 查看全部使用方法
```

### tokenizer
离线token计算 (基于 `DeepSeek-V2` 分词器)
```sh
./tokenizer "请介绍你自己"
```

