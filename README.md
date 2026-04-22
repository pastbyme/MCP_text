![MCP实验截图](图片/1.png)
![MCP实验截图](图片/2.png)
# 激活虚拟环境
conda activate MCP

# 安装MCP核心SDK与命令行工具
pip install mcp mcp[cli]
# 验证Python版本
python --version
# 输出：Python 3.13.13

# 验证MCP命令行工具可用
mcp --help

mcp dev .\doc_example_mcp.py