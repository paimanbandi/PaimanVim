# PaimanVim

This is my PDE (Personalized Development Environment). I use to code Flutter, TypeScript, Rust and V.

## Requirements

- Neovim (>= v0.8.2)
- fzf
- ripgrep

## Environment variables

- OPENAI_API_KEY (for ChatGPT)

## Keymaps

I use <space> for the <leader> key.

| Mode           	| Keymap          	| Action                       	|
|----------------	|-----------------	|------------------------------	|
| Normal         	| \\ 		     	| Toggle Term			|            
| Normal         	| <leader>l      	| Toggle Blame Line		|            
| Normal         	| <leader>e       	| Toggle Nvim Tree             	|
| Normal         	| <leader>cg      	| Open ChatGPT                 	|
| Normal         	| zR              	| Open All Folds               	|
| Normal         	| zM              	| Close All Folds              	|
| Normal         	| zo              	| Open Fold                    	|
| Normal         	| za              	| Close Fold                   	|
| Normal         	| <leader>b       	| Toggle Breakpoint            	|
| Normal         	| <F5>            	| Continue                     	|
| Normal         	| <F10>            	| Step Over			|
| Normal         	| <F11>            	| Step Into			|
| Normal         	| <F12>            	| Step Out			|
| Normal         	| J               	| Remove row below             	|
| Normal         	| K               	| Hover Documentation          	|
| Normal         	| <C-k>               	| Signature Documentation     	|
| Normal         	| <leader>?       	| Find Recently Opened Files   	|
| Normal         	| <leader><space> 	| Find Existing Buffers        	|
| Normal         	| <leader>f      	| Find Files                   	|
| Normal         	| <leader>g      	| Live Grep                   	|
| Normal         	| <leader>h      	| Search Help			|
| Normal         	| <leader>w      	| Search in Current File        |
| Normal         	| <leader>d      	| Search Diagnostics            |
| Normal         	| gd		      	| Go to Definition		|
| Normal         	| gr		      	| Go to Reference		|
| Normal         	| gi		 	| Go to Implementation 		|
| Insert, Visual     	| hh              	| Escape                       	|
| Insert, Visual      	| HH              	| Escape                       	|
| Visual         	| J               	| Move selected text to bottom 	|
| Visual         	| K               	| Move selected text to above  	|
| Normal, Visual 	| <leader>ca      	| Code Action                  	|
