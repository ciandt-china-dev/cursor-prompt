# 代码生成规范

本文档定义了使用 Cursor 生成纯代码时的规范要求。

## 目的说明

通过纯代码生成模式，我们可以：

- 提高开发效率
- 减少冗余信息
- 保持代码简洁
- 专注于实现逻辑

## 输出规范

### 基本要求

- 仅输出代码，不包含其他说明
- 保持代码格式规范
- 遵循项目编码标准

### 注释规范

- 必要的文档注释使用英文
- 注释应简洁明了
- 仅在关键处添加注释

## 示例

```python
# Function to process data
def process_data(input_data: dict) -> dict:
    """
    Process the input data and return transformed result
    
    Args:
        input_data (dict): Input data to process
        
    Returns:
        dict: Processed data
    """
    return transformed_data
```
