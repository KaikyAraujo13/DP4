# SINTAXE MARKDOWN

## TÍTULOS

```
# Título principal 
## Título de seção
### Título de subseção
``` 

# TÍTULO PRINCIPAL 
## Título de seção
### Título de subseção

## FORMATAÇÃO DE TEXTO

``` 
**Texto em NEGRITO**

*Texto em ITALÍCO*

~~Texto TACHADO~~
``` 

**Texto em NEGRITO**

*Texto em ITALÍCO*

~~Texto TACHADO~~ 

## LISTAS

- Primeiro item
- Segundo item
    - Subitem identado
    - Outro subitem 

``` 
1. Primeiro passo
2. Segundo passo
3. Terceiro passo
``` 

1. Primeiro passo
2. Segundo passo
3. Terceiro passo 

## CHECKLISTS 

``` 
- [x] Tarefa concluída
- [ ] Tarefa pendente 
``` 

- [ ] Tarefa concluída
- [x] Tarefa pendente 

## LINKS 

``` 
[Visite o GitHub](https://github.com/)

[Simple Badges] (![Supermicro Badge](https://img.shields.io/badge/Supermicro-151F6D?logo=supermicro&logoColor=fff&style=for-the-badge))
``` 
[Visite o GitHub](https://github.com/)

[Simple Badges] (![Supermicro Badge](https://img.shields.io/badge/Supermicro-151F6D?logo=supermicro&logoColor=fff&style=for-the-badge))


[Abra outro arquivo do projeto](./OUTRO%20GATO)

## CÓDIGO EM LINHA E BLOCOS DE CÓDIGO

Use uma crase para destacar um comando ou trecho curto no meio de uma frase.

O comando `git status` mostra o estado atual do repositório 

O comando `git add .` adiciona os arquivos modificados à *stagingarea*.

O comando `git commit -m "Texto com a descrição do que foi feito"` registra as alterações com uma mensagem.

O comando `git push origin main` sobe as alterações para a núvem.

``` 
git status
git add .
git commit -m "Texto com a descrição do que foi implementado"
git push origin main
``` 