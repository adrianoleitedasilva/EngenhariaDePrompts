# Zero-shot, One-shot e Few-shot Prompting

Esses conceitos descrevem quanto de exemplo você fornece à IA antes de solicitar uma tarefa.

## Zero-shot Prompting

No Zero-shot, você não fornece exemplos. Apenas descreve o que deseja.

Exemplo:

Prompt:

```
Classifique o sentimento da frase: ‘Hoje foi um dia incrível.'
```

A IA responde diretamente (positivo).

**Características:**

- Mais rápido
- Prompt mais curto
- Funciona bem para tarefas simples
- Pode gerar respostas genéricas ou menos precisas

## One-shot Prompting

No One-shot, você fornece um único exemplo para orientar o modelo.

**Exemplo:**

Prompt:

```
Classifique o sentimento das frases.

Exemplo:
Frase: ‘Estou muito feliz hoje.’
Sentimento: Positivo

Agora classifique:
Frase: ‘Hoje foi um dia terrível.’
```

A IA entende o padrão e replica o formato.

**Características:**

- Ajuda a alinhar formato e estilo
- Melhora consistência
- Útil quando o modelo não segue a estrutura desejada

## Few-shot Prompting

No Few-shot, você fornece vários exemplos.

Exemplo:

Prompt:

```
Classifique o sentimento das frases.

Frase: ‘Estou muito feliz hoje.’ → Positivo
Frase: ‘Que dia horrível.’ → Negativo
Frase: ‘Nada mal.’ → Neutro

Agora classifique:
Frase: ‘Isso foi surpreendente.’
```

A IA aprende o padrão com mais clareza.

**Características:**

- Maior controle sobre a resposta
- Melhor para tarefas ambíguas ou complexas
- Reduz erros
- Prompt mais longo

Comparação

| Técnica   | Exemplos fornecidos | Quando usar                              |
| --------- | ------------------- | ---------------------------------------- |
| Zero-shot | Nenhum              | Tarefas simples e rápidas                |
| One-shot  | 1 exemplo           | Ajustar formato ou estilo                |
| Few-shot  | 2 ou mais exemplos  | Tarefas complexas ou que exigem precisão |

# Exemplo

**Tarefa: gerar título de artigo**

**Zero-shot:**

```
Crie um título para um artigo sobre liderança.
```

Resultado tende a ser mais genérico.

**One-shot:**

```
Exemplo de título:
‘Liderança Humanizada: Como Engajar Times Modernos’
Agora crie um título sobre liderança técnica.”
```

Resultado mais alinhado ao padrão.

**Few-shot:**

```
Exemplos:
‘Liderança Humanizada: Como Engajar Times Modernos’
‘Gestão Ágil: Liderando em Ambientes de Mudança’
‘Times de Alta Performance: Estratégias de Liderança’

Agora crie um título sobre liderança técnica.
```

Resultado geralmente mais consistente.
