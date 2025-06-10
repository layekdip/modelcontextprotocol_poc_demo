pip install uv
uv init mcp-server-demo
cd mcp-server-demo
uv add "mcp[cli]" --native-tls
pip install "mcp[cli]"
mcp dev demo_server.py
