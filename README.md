# Portal B2B Grupo Serra Grande

Setup local do projeto estatico (`code.html`) com execucao em `localhost:3000`, sem instalacao global de dependencias.

## Estrutura de runtime local

- App: `code.html` (Tailwind CDN + JavaScript vanilla)
- Node portatil: `tools/node/`
- GitHub CLI portatil: `tools/gh/bin/gh.exe`
- Dependencias npm locais: `node_modules/`

## Pre-requisitos

- Windows 10/11 com PowerShell
- Conexao com internet para baixar dependencias

Nao e necessario instalar Node/npm globalmente para este fluxo.

## Subir o app localmente na porta 3000

1. Na raiz do projeto, execute:

```powershell
.\tools\node\npm.cmd install
```

2. Inicie o servidor local:

```powershell
.\tools\node\npm.cmd run dev
```

3. Abra no navegador:

- [http://localhost:3000](http://localhost:3000)

## Scripts disponiveis

- `.\tools\node\npm.cmd run dev` -> sobe local em `3000`
- `.\tools\node\npm.cmd run start` -> equivalente ao `dev`
- `.\tools\node\npm.cmd run vercel -- --version` -> valida Vercel CLI local

## Vercel CLI sem instalacao global

O projeto usa `vercel` como dependencia local (`devDependencies`).

Comandos uteis:

```powershell
.\tools\node\npm.cmd run vercel -- --version
.\tools\node\npm.cmd run vercel -- login
.\tools\node\npm.cmd run vercel -- link
.\tools\node\npm.cmd run vercel -- deploy
```

## GitHub CLI portatil (sem PATH global)

Binario local:

```text
tools/gh/bin/gh.exe
```

Comandos uteis:

```powershell
.\tools\gh\bin\gh.exe --version
.\tools\gh\bin\gh.exe auth login
.\tools\gh\bin\gh.exe repo view
```

## Troubleshooting

- Porta 3000 ocupada:
  - encerre o processo da porta (`netstat -ano | findstr :3000` + `taskkill /PID <pid> /F`)
- `npm` nao reconhecido:
  - use sempre `.\tools\node\npm.cmd` em vez de `npm` puro
- Navegador abre listagem de arquivos:
  - rode o script do projeto (`npm run dev`) que serve diretamente `code.html`
- `gh` nao encontrado:
  - execute pelo caminho completo `.\tools\gh\bin\gh.exe`

## Checklist manual (mobile-first)

- Navbar mobile abre/fecha corretamente
- Incremento/decremento de itens no portfolio
- Drawer "Resumo da Cotacao" abre/fecha (incluindo tecla ESC)
- Persistencia de cotacao apos recarregar pagina (`localStorage`)
- Envio do formulario abre WhatsApp com mensagem pre-formatada

