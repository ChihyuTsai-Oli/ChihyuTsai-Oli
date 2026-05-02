# 電腦 B 同步說明

## 1. Clone Overview repo

在 Terminal 執行：

```bash
git clone https://github.com/ChihyuTsai-Oli/ChihyuTsai-Oli.git "E:\_GitHub\Overview"
```

## 2. 更新 LoopFlow.code-workspace

編輯 `E:\_GitHub\LoopFlow.code-workspace`，在 folders 陣列最後加入：

```json
{
  "path": "Overview"
}
```

完整結果如下：

```json
{
  "folders": [
    {
      "path": "LoopFlow"
    },
    {
      "path": "LoopFlow_Rhino-to-Blender-Sync"
    },
    {
      "path": "LoopFlow_Rhino-to-Octane-Sync"
    },
    {
      "path": "Overview"
    }
  ],
  "settings": {}
}
```
