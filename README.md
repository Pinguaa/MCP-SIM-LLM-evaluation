# MCP-SIM-LLM-evaluation

*Valutazione dell'uso di Large Language Models per la generazione di codici termo-fluidodinamici*

## Modelli valutati
- Gemini 3.5 Flash
- Gemini 3 Flash
- Gemini 3.1 Flash Lite
- NVIDIA Nemotron 3 Super

## Ambiente
- FEniCS Legacy (dolfin 2019.1.0)
- Python 3.9
- Miniforge3 / conda

## Struttura
```
MCP-SIM-LLM-evaluation/
├── tasks/
├── gemini-3.5-flash/
│   ├── agents/
│   ├── results/
│   └── main.py
├── gemini-3-flash/
│   ├── agents/
│   ├── results/
│   └── main.py
├── gemini-3.1-flash-lite/
│   ├── agents/
│   ├── results/
│   └── main.py
└── nemotron-3-super/
    ├── agents/
    ├── results/
    └── main.py
```

## Riferimento
Park, D., Moon, H., & Ryu, S. (2026). A self-correcting multi-agent LLM
framework for language-based physics simulation and explanation.
*npj Artificial Intelligence*, 2(1), 10.
https://doi.org/10.1038/s44387-025-00057-z
