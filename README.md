# nvim config

Configuración personal de Neovim, basada en [LazyVim](https://github.com/LazyVim/LazyVim).

## Instalación

```sh
git clone <this-repo> ~/.config/nvim
nvim
```

Lazy.nvim instalará automáticamente los plugins en el primer arranque.

## Estructura

```
lua/
├── config/
│   ├── autocmds.lua   # autocomandos propios
│   ├── keymaps.lua    # atajos de teclado propios
│   ├── lazy.lua       # bootstrap de lazy.nvim
│   └── options.lua    # opciones propias
└── plugins/           # specs de plugins (uno por archivo)
```

Ver la [documentación de LazyVim](https://lazyvim.github.io/installation) para más detalle sobre los defaults que trae por debajo.
