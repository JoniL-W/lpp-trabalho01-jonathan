# Cacau Dourado — Vila da Chocolateria

## Etapa 2 — conexão e estado sincronizado

A tela abre, Mestre/Jogador conectam e o servidor envia `estado.sincronizado`.

Esta é uma versão intermediária e cumulativa do Trabalho 01 de Programação Orientada a Eventos. A especificação completa está em `docs/especificacao.md`.

**Integrante:** Jonathan Wiessner — preencher o `@` do GitHub antes da entrega.

## Executar

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m uvicorn server:app --reload
```

Abra `http://localhost:8000` em duas abas.
