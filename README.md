# OBSIDIAN SETUP

1. Instalação do obsidian 
2. Instalação do Calude desktop
3. Instalação do Python 3.x
4. Instalação do uv (https://github.com/astral-sh/uv)
5. Configurar o mcp-obsidian (https://github.com/MarkusPfundstein/mcp-obsidian)

```
.env

OBSIDIAN_API_KEY=api_key_aqui
```
6. Configurar mcpServer do Claude

```
{
    "mcpServers": {
        "mcp-obsidian": {
            "command": "/Users/54117/.local/bin/uv",
            "args": [
                "--directory",
                "/Users/54117/Desktop/Obsidian/mcp-obsidian",
                "run",
                "mcp-obsidian"
            ]
        }
    }
}
```

7. Reiniciar o Claude