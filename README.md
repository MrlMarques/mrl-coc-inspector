# 🏰 CoC Village Inspector PWA

> Um Progressive Web App (PWA) rápido, leve e moderno para analisar dados brutos de vilas do Clash of Clans (JSON), extraindo informações cruciais de forma limpa e direta.

---

## 🚀 Funcionalidades

* **📥 Leitura de JSON Bruto:** Cole o payload JSON completo da sua vila do Clash of Clans para processamento instantâneo no navegador.
* **👑 Monitoramento de Heróis:** Exibe o nível atual de todos os heróis (Rei Bárbaro, Rainha Arqueira, Grande Guardião, Campeã Real, etc.).
* **🛡️ Análise de Defesas e Edifícios:** Mapeia e traduz os IDs internos do jogo para nomes legíveis, mostrando quantidades e níveis das estruturas, defesas e muros.
* **📍 Detecção do Centro de Vila (CV):** Identifica automaticamente o nível do Town Hall principal da vila.
* **⚡ 100% PWA (Progressive Web App):** Totalmente instalável na tela inicial do celular (iOS/Android) ou como aplicativo de desktop, com suporte a cache e funcionamento offline básico via Service Worker.
* **🎨 Dark Mode & Gold Aesthetics:** Interface customizada com tema escuro elegante, detalhes em vermelho e dourado, e fontes monoespaçadas.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3** (Estruturação e Estilização)
* **Tailwind CSS v4** (Via CDN para estilização ágil e responsiva)
* **JavaScript Vanilla (ES6+)** (Parser de JSON e manipulação do DOM)
* **Service Workers & Web App Manifest** (Recursos de PWA e cache offline)

---

## 📱 Como Instalar e Usar

1. Acesse o link do projeto hospedado via **GitHub Pages**.
2. Cole o JSON da sua vila no campo indicado na interface.
3. Clique em **"ANALISAR VILA"** (ou use o botão de exemplo para testar rapidamente).
4. No celular ou PC, clique no menu do navegador e selecione **"Adicionar à Tela Inicial"** / **"Instalar App"** para usar como aplicativo nativo.

---

## 📂 Estrutura do Projeto

```text
├── index.html        # Interface principal e lógica de parsing do JSON
├── manifest.json     # Configurações do Progressive Web App
└── sw.js             # Service Worker para gerenciar o cache e o modo offline
