# PaimanVim

My personal Neovim configuration. 

## Requirements

- Neovim (>= v0.8.2)
- fzf
- ripgrep

## Environment variables

- OPENAI_API_KEY (for ChatGPT)

## Keymaps

```lua
vim.g.mapleader = ' '
```

| Mode   	| Keymap     	| Action            	|
|--------	|------------	|-------------------	|
| Normal 	| <leader>tb 	| Toggle Blame Line 	|
| Normal 	| <leader>e  	| Toggle Nvim Tree  	|
| Normal 	| <leader>cg 	| Open ChatGPT      	|
| Normal 	| zR         	| Open All Folds    	|
| Normal 	| zM         	| Close All Folds   	|
| Normal 	| zo         	| Open Fold         	|
| Normal 	| za         	| Close Fold        	|
| Normal 	| <leader>b  	| Toggle Breakpoint 	|
| Normal 	| <F15>  	| Continue 	|

