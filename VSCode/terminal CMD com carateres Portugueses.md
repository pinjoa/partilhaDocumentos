# Configurar o terminal CMD do VSCode para carateres Portugueses

## Descrição

Assumindo que estás a utilizar no VSCode o terminal CMD com a _shell_ tradicional do windows também conhecida por "_Linha de comandos_"



Necessitas de alterar as configurações do VSCode e pesquisar por _terminal.integrated_ depois só necessitas de editar o ficheiro de configuração _settings.json_ e completar para as seguintes configurações, caso queiras seguir a minha sugestão de configuração:

```
    ...
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe",
    "terminal.integrated.shellArgs.windows": ["/K", "chcp 65001"],
    ...
```

**NOTA**:

- a página de código configurada por defeito é 850 (ASCII)
- para Portugal o código é o 860 
- para as versões mais recentes do sistema operativo, a minha sugestão é o código 65001 (UTF-8)


## Contribuir

Todas as sugestões para melhorar são aceites.

## Licença

Copyright (c) 2020, João Carlos Pinto
