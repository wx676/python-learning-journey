# 🔧 环境配置管理

## 🎯 用途说明

管理所有Python开发环境和工具配置，确保开发环境的一致性和可复现性。

## 📋 包含内容

- **Conda环境配置** - Python虚拟环境管理
- **VS Code设置** - 编辑器配置和扩展
- **依赖包管理** - 项目依赖记录和安装
- **环境测试脚本** - 验证环境配置

## 🛠️ 环境配置

### Conda环境管理

```bash
# 查看所有环境
conda info --envs

# 激活myenv环境（数据科学项目使用）
conda activate myenv

# 激活base环境（学习项目使用）
conda activate base

# 创建新环境
conda create --name 新环境名 python=3.9
```
