# ScholAI

ScholAI 是一个基于 CrewAI 和 LangChain 的框架，专为自动化科研文献的搜索、阅读、整理和汇报而设计。此项目旨在减轻科研工作者和学生的负担，通过 AI 智能化处理文献，提高科研效率。

## 特性

- **自动文献搜索**：自动在多个科研数据库中搜索相关文献。
- **智能内容摘要**：利用大语言模型提取文献的核心观点。
- **文献管理**：整理和分类文献，便于快速检索和引用。
- **报告生成**：自动生成文献综述或研究报告。

## 开始使用

以下指南将帮助你在本地机器上部署和运行 ReadAI。

### 先决条件

确保你的系统中安装了以下软件：

- Python 3.8 或更高版本
- pip (Python 包管理器)

### 安装

首先，克隆此仓库到你的本地机器：

```bash
git clone https://github.com/SpencerRaw/ScholAI.git
cd ReadAI
```

然后，创建一个虚拟环境并激活它：

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

安装所有依赖：

```bash
pip install -r requirements.txt
```

### 使用

运行主程序：

```bash
python main.py
```

## 贡献

感谢对 ScholAI 项目的兴趣！欢迎通过 Pull Requests 或 Issues 提交代码和建议。

## 许可证

本项目采用 MIT 许可证。详情请查阅 [LICENSE](LICENSE) 文件。

## 联系方式

如果你有任何问题或者建议，请通过以下方式联系我们：

- 电子邮件：spencerxu79@gmail.com
- GitHub Issues：https://github.com/SpencerRaw/ScholAI/issues
