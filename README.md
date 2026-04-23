## Como executar

```bash
# A partir da raiz do projeto T5/
python src/main.py dados/brasil.txt
```

Requisito: **Python 3.10+** (sem dependências externas).

---

## Estrutura do projeto

```
T5/
├── README.md
├── T5.md
├── dados/
│   └── brasil.txt          ← grafo no padrão algs4
└── src/
    ├── main.py             ← ponto de entrada
    ├── graph.py            ← classe Graph (algs4-style)
    └── dsatur.py           ← algoritmo DSatur + validação
```

---

## Resultado obtido

O programa produziu uma coloração válida com **3 cores** para os 27 estados
brasileiros (27 vértices, 51 arestas), o que é consistente com o Teorema das
Quatro Cores — que garante no máximo 4 cores para qualquer grafo planar — e
demonstra que o DSatur encontrou uma solução de alta qualidade neste caso.

---

## Vídeo explicativo

> 🔗 _(https://youtu.be/Mloy0kJWXiw)_
