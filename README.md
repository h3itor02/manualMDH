```md
# manualMDH
```

## BOUUA, aula prof rold, fazendo repositório destinado ao formato MD.

Aqui está um manual simples e completo de **Markdown (MD)**, cobrindo os principais conceitos e sintaxes para que você possa usá-lo facilmente:

---

# Manual de Uso de Markdown (MD)

Markdown é uma linguagem de marcação leve e fácil de usar, muito utilizada para formatação de texto. É comumente usado em plataformas como GitHub, blogs e editores de texto.

## 1. **Estrutura Básica**

### Títulos
Para criar títulos, use o símbolo `#` seguido de um espaço. O número de `#` indica o nível do título.

```md
# Título de nível 1
## Título de nível 2
### Título de nível 3
#### Título de nível 4
##### Título de nível 5
###### Título de nível 6
```

### Texto em Negrito e Itálico
- **Negrito**: Envolva o texto com `**` ou `__`.
- *Itálico*: Envolva o texto com `*` ou `_`.

```md
**Texto em negrito**
__Texto em negrito__

*Texto em itálico*
_Texto em itálico_
```

### Misturar Negrito e Itálico
Você pode combinar negrito e itálico no mesmo texto.

```md
***Texto em negrito e itálico***
```

## 2. **Listas**

### Listas Ordenadas (Numeradas)
Use números seguidos de um ponto para criar uma lista ordenada.

```md
1. Item 1
2. Item 2
3. Item 3
```

### Listas Não Ordenadas (Com Marcadores)
Use `-`, `*` ou `+` para criar uma lista não ordenada.

```md
- Item 1
- Item 2
- Item 3

* Item 1
* Item 2
* Item 3
```

## 3. **Links e Imagens**

### Links
Para criar um link, use `[Texto do link](URL)`.

```md
[Google](https://www.google.com)
```

### Imagens
Imagens seguem a mesma sintaxe de links, mas adicionam um `!` antes do texto.

```md
![Texto alternativo](URL_da_imagem)
```

## 4. **Bloco de Citação**
Para criar uma citação, use o símbolo `>` antes do texto.

```md
> Este é um bloco de citação.
```

## 5. **Bloco de Código**

### Código em Linha
Envolva o código em uma única crase `` ` `` para destacá-lo em linha.

```md
Aqui está o código em `linha de comando`.
```

### Bloco de Código
Use três crases ``` para criar blocos de código.

```md
```
Aqui está um bloco de código.
```
```

Você também pode especificar a linguagem para realce de sintaxe:

```md
```python
def ola_mundo():
    print("Olá, Mundo!")
```
```

## 6. **Tabelas**

Para criar uma tabela, use `|` para separar as colunas e `-` para criar a linha de separação entre cabeçalho e conteúdo.

```md
| Coluna 1 | Coluna 2 | Coluna 3 |
|----------|----------|----------|
| Valor 1  | Valor 2  | Valor 3  |
| Valor A  | Valor B  | Valor C  |
```

## 7. **Emojis**
Para adicionar emojis, basta usar o código do emoji entre dois pontos `:`.

```md
:smile: :heart: :thumbsup:
```

## 8. **Linhas Horizontais**
Use três ou mais hífens `---`, asteriscos `***` ou underscores `___` para criar uma linha horizontal.

```md
---
ou
***
ou
___
```

## 9. **Escape de Caracteres Especiais**
Se precisar usar caracteres especiais como `#`, `*`, `[]`, etc., sem que sejam interpretados pelo Markdown, use a barra invertida `\` antes do caractere.

```md
\# Isto não será um título
\* Isto não será itálico
```

---

## Exemplos Práticos

```md
# Como Usar Markdown

## Títulos
Você pode usar vários níveis de títulos:

# Título principal
## Subtítulo
### Subtítulo menor

## Listas
- Item 1
- Item 2
  - Subitem A
  - Subitem B

1. Primeiro
2. Segundo

## Link e Imagem
[Google](https://www.google.com)

![Imagem](https://www.example.com/imagem.jpg)

## Citação
> Este é um exemplo de citação.

## Código
Para código em linha: `print("Olá")`

Bloco de código:

```python
def ola():
    print("Olá, Mundo!")
```

## Tabela
| Nome  | Idade | País |
|-------|-------|------|
| João  | 20    | BR   |
| Maria | 25    | PT   |
```

---

Este manual abrange as sintaxes mais usadas de Markdown. Você pode usar este guia para criar textos formatados de forma simples e eficiente! 😊