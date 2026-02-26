# O que é Cadeia de Pensamento (Chain of Thought)?

Cadeia de Pensamento é uma técnica de prompting que incentiva a IA a explicar o raciocínio passo a passo antes de chegar à resposta final.

Em vez de pedir apenas a resposta, você orienta o modelo a:

**Pense passo a passo antes de responder.**

## Conceito simplificado

Sem Cadeia de Pensamento:

```
Pergunta → Resposta direta
```

Com Cadeia de Pensamento:

```
Pergunta → Raciocínio estruturado → Resposta final
```

## Exemplo prático (problema lógico)

**Sem Cadeia de Pensamento**

Pergunta:

```
Se João tem 3 maçãs e compra mais 2, com quantas ele fica?

Resposta: 5.
```

Correto, mas sem mostrar o raciocínio.

**Com Cadeia de Pensamento**

Prompt:

```
Explique passo a passo antes de dar a resposta.
```

**Resposta:**

```
João tem 3 maçãs.
Ele compra mais 2.
Somando 3 + 2 = 5.
Resposta final: 5.
```

Aqui o modelo estrutura o raciocínio.

## Por que isso é importante?

A Cadeia de Pensamento melhora:

- Precisão em problemas matemáticos
- Resolução de lógica
- Planejamento
- Tomada de decisão
- Análises complexas

Ela reduz respostas precipitadas.

## Onde isso é mais usado?

- Resolução de problemas matemáticos
- Questões de raciocínio lógico
- Planejamento estratégico
- Diagnóstico técnico
- Tomadas de decisão com múltiplos fatores

### Exemplo aplicado à gestão (sua área)

Pergunta:

```
Devo contratar mais um desenvolvedor ou investir em treinamento da equipe atual?
```

Com Cadeia de Pensamento, o modelo poderia:

- Analisar a carga atual de trabalho.
- Avaliar gargalos.
- Considerar orçamento.
- Avaliar impacto de longo prazo.
- Comparar custo vs benefício.

Só depois apresentar a recomendação.

## Diferença entre Prompt Iterativo e Cadeia de Pensamento

| Prompt Iterativo               | Cadeia de Pensamento          |
| ------------------------------ | ----------------------------- |
| Estratégia de refinamento      | Estratégia de raciocínio      |
| Ocorre em múltiplas interações | Ocorre dentro de uma resposta |
| Foco em melhorar o resultado   | Foco em melhorar a lógica     |

## Estruturas comuns para ativar Cadeia de Pensamento

Você pode usar frases como:

- Explique passo a passo.
- Mostre seu raciocínio.
- Pense antes de responder.
- Quebre o problema em partes.
