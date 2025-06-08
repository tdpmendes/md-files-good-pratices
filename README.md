
# Boas Práticas para Escrever Arquivos Markdown (.md)

## Sumário
- [1. Use Títulos e Subtítulos](#1-use-títulos-e-subtítulos)
- [2. Use Listas para Organizar Ideias](#2-use-listas-para-organizar-ideias)
- [3. Destaque Trechos de Código](#3-destaque-trechos-de-código)
- [4. Crie Links e Imagens](#4-crie-links-e-imagens)
- [5. Use Ênfase com Moderação](#5-use-ênfase-com-moderação)
- [6. Mantenha o Texto Claro e Direto](#6-mantenha-o-texto-claro-e-direto)
- [7. Use Tabelas para Dados Estruturados](#7-use-tabelas-para-dados-estruturados)
- [8. Separe Seções com Linhas Horizontais](#8-separe-seções-com-linhas-horizontais)
- [9. Adicione Sumário (Opcional)](#9-adicione-sumário-opcional)
- [10. Teste a Renderização](#10-teste-a-renderização)

## 1. Use Títulos e Subtítulos
Use `#`, `##`, `###` para estruturar o conteúdo hierarquicamente.

# Título Principal
## Seção
### Subseção

## 2. Use listas para organizar ideias
- Use `-`, `*` ou `1.` para listas com marcadores ou numeradas.

### Exemplo de lista com marcadores:
- Item 1
- Item 2
  - Subitem

### Exemplo de lista numerada:
1. Primeiro item
2. Segundo item
   1. Subitem

### ✅ 3. Destaque trechos de código

- Use crases simples para código inline: `` `comando` ``  
  Exemplo: Use o comando `npm install` para instalar as dependências.

- Use três crases para blocos de código:

#### Exemplo em JSON:
```json
{
  "nome": "João",
  "idade": 30
}
```

### ✅ 4. Crie links e imagens

- **Links**: Use `texto` para criar links.

#### Exemplo de link:
Visite o site da Microsoft

- **Imagens**: Use `!texto alternativo` para exibir imagens.

#### Exemplo de imagem:
!Logo do Markdown

### ✅ 5. Use ênfase com moderação

- **Negrito**: Use `**texto**` ou `__texto__`  
  Exemplo: **Importante**

- *Itálico*: Use `*texto*` ou `_texto_`  
  Exemplo: *Destaque leve*

- ***Negrito e itálico***: Combine os dois com `***texto***`  
  Exemplo: ***Muito importante***

### ✅ 6. Mantenha o texto claro e direto

- Prefira frases curtas e objetivas.
- Evite jargões técnicos desnecessários.
- Use linguagem simples e acessível.
- Separe ideias em parágrafos distintos.
- Destaque pontos importantes com listas ou ênfase.

> Um texto claro facilita a leitura e a compreensão, especialmente em documentação técnica.

### ✅ 7. Use tabelas para dados estruturados

- Use `|` para separar colunas e `-` para criar o cabeçalho.

#### Exemplo de tabela:

| Nome     | Idade | Cidade       |
|----------|-------|--------------|
| João     | 30    | Porto        |
| Maria    | 25    | Lisboa       |
| Ana      | 28    | Coimbra      |

> Dica: alinhe as colunas para facilitar a leitura, mesmo que o Markdown não exija.

### ✅ 8. Separe seções com linhas horizontais

- Use três hífens (`---`), asteriscos (`***`) ou underlines (`___`) para criar uma linha horizontal.

#### Exemplo:

---

Essa linha separa visualmente blocos de conteúdo.

***

Também funciona com asteriscos.

___

Ou com underlines.

### ✅ 9. Adicione sumário (opcional)

- Um sumário ajuda na navegação, especialmente em arquivos longos.
- Use links âncora para cada seção.

#### Exemplo de sumário:

```markdown
## Sumário
- 1. Introdução
- 2. Instalação
- 3. Uso
```

> Dica: mantenha os títulos consistentes para que os links funcionem corretamente.

### ✅ 10. Teste a renderização

- Visualize seu arquivo `.md` em um editor que suporte Markdown (como VS Code, GitHub, Obsidian, etc.).
- Verifique se os links, listas, tabelas e blocos de código estão sendo exibidos corretamente.
- Corrija quebras de linha, erros de sintaxe ou formatação incorreta.

> Uma boa renderização melhora a legibilidade e a experiência de quem lê sua documentação.
