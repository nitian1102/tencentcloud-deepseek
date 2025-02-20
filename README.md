# tencentcloud-deepseek
通过腾讯云接口调用deepseek模型
可查看该文档获取自己的ak，替换代码中的api_key即可  https://cloud.tencent.com/document/product/1772/115970

# 已支持的模型

| 模型           | 参数量 | 上下文长度 | 最大输入长度 | 最大输出长度                  |
| -------------- | ------ | ---------- | ------------ | ----------------------------- |
| DeepSeek-R1    | 671B   | 64k        | 56k          | 8k（不含思维链长度）          |
| DeepSeek-V3    | 671B   | 64k        | 56k          | 8k（不含思维链长度）          |

## DeepSeek-R1 (model 参数值为 deepseek-r1)

DeepSeek-R1 为 671B 模型

## DeepSeek-V3 (model 参数值为 deepseek-v3)

DeepSeek-V3 为 671B 参数 MoE 模型

即日起至北京时间2025年2月25日23:59:59，该接口限时免费，可以调用deepseek接口。该时间后，腾讯云开始收费
