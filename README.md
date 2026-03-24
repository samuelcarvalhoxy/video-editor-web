# video-editor-web
# 🎬 Editor de Vídeo Web Pro com FFmpeg.wasm

Aplicação web avançada para edição de vídeos diretamente no navegador, com suporte a corte, recorte (crop), rotação, velocidade, compressão e exportação — sem necessidade de instalação.

---

## 🚀 Funcionalidades

* ✂️ Corte de vídeo (trim)
* 🔲 Recorte de área (crop com presets: 1:1, 16:9, 9:16)
* 🔄 Rotação e espelhamento
* ⏩ Controle de velocidade (0.5x até 2x)
* 🔇 Remoção de áudio
* 🎞️ Timeline interativa com preview
* 🔍 Zoom na linha do tempo
* 🧠 Snap inteligente de tempo
* ⚡ Processamento no navegador (sem upload para servidor)
* 📦 Exportação em MP4 com compressão ajustável

---

## 🧠 Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

* **FFmpeg.wasm** — processamento de vídeo via WebAssembly
* **Tailwind CSS** — estilização e layout
* **Font Awesome** — ícones
* **JavaScript Vanilla** — lógica principal

---

## ⚠️ Aviso Importante sobre Dependências

Este projeto **utiliza bibliotecas de terceiros**, que possuem suas próprias licenças:

* FFmpeg.wasm → baseado no FFmpeg (licença LGPL/GPL)
* Tailwind CSS → licença MIT
* Font Awesome → pode possuir restrições dependendo do uso

👉 O uso dessas bibliotecas não transfere propriedade ao autor deste projeto.

---

## 📜 Licença e Direitos Autorais

© 2026 Samuel Carvalho. Todos os direitos reservados.

Este software e seu código-fonte são propriedade exclusiva do autor.

### ❌ Não é permitido:

* Copiar, reproduzir ou redistribuir este código
* Modificar ou criar derivados sem autorização
* Utilizar para fins comerciais sem permissão explícita
* Reivindicar este projeto como próprio

### ✅ Permitido apenas:

* Uso pessoal mediante acesso autorizado
* Visualização do código para fins educacionais (sem reutilização)

Para qualquer tipo de uso, entre em contato com o autor.

---

## 🛡️ Proteção de Propriedade Intelectual

Este projeto contém:

* Lógica proprietária de edição no navegador
* Interface personalizada
* Estrutura de processamento otimizada com FFmpeg.wasm

Qualquer uso indevido poderá resultar em medidas legais.

---

## 🌐 Como Executar

### 🔹 Opção recomendada (produção)

Acesse via ambiente web hospedado (ex: Vercel)

---

### 🔹 Ambiente local

Não abrir diretamente via `file://`

Utilize um servidor local, como:

* Live Server (VS Code)
* Python HTTP Server

---

## 📌 Observações Técnicas

* O processamento ocorre totalmente no navegador
* Não há upload de arquivos para servidores externos
* Performance pode variar conforme o hardware do usuário
* Algumas operações exigem re-encoding (mais lento)

---

## 📈 Possíveis Evoluções

* Salvamento de projetos
* Exportação em múltiplos formatos
* Interface multi-usuário
* Versão desktop (Electron)
* Integração com APIs

---

## 🤝 Contato

Para uso comercial, parcerias ou licenciamento:

📩 Entre em contato diretamente com o autor

---

## ⭐ Considerações Finais

Este projeto representa uma solução moderna de edição de vídeo client-side, explorando o poder do WebAssembly para entregar performance e privacidade.

---
