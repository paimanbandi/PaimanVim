# PaimanVim

My personal Neovim configuration. I use to code Flutter, TypeScript, and Rust.

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

| Mode           	| Keymap          	| Action                       	|
|----------------	|-----------------	|------------------------------	|
| Normal         	| <leader>tb      	| Toggle Blame Line            	|
| Normal         	| <leader>e       	| Toggle Nvim Tree             	|
| Normal         	| <leader>cg      	| Open ChatGPT                 	|
| Normal         	| zR              	| Open All Folds               	|
| Normal         	| zM              	| Close All Folds              	|
| Normal         	| zo              	| Open Fold                    	|
| Normal         	| za              	| Close Fold                   	|
| Normal         	| <leader>b       	| Toggle Breakpoint            	|
| Normal         	| <F5>            	| Continue                     	|
| Normal         	| J               	| Remove row below             	|
| Normal         	| K               	| Hover Documentation          	|
| Normal         	| <leader>?       	| Find Recently Opened Files   	|
| Normal         	| <leader><space> 	| Find Existing Buffers        	|
| Normal         	| <leader>ff      	| Find Files                   	|
| Insert         	| hh              	| Escape                       	|
| Insert         	| HH              	| Escape                       	|
| Visual         	| J               	| Move selected text to bottom 	|
| Visual         	| K               	| Move selected text to above  	|
| Normal, Visual 	| <leader>ca      	| Code Action                  	|
