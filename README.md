# 🔐 Wi-Fi QR Code Generator

Uma ferramenta simples, direta e 100% em HTML + CSS + JavaScript para gerar senhas Wi-Fi aleatórias seguras, com QR Codes prontos para escanear e conectar.

## ✨ Funcionalidades

- Geração automática de senhas fortes com:
  - Letras maiúsculas
  - Letras minúsculas
  - Números
  - Caracteres especiais
- Criação instantânea de QR Code com a senha gerada.
- Download automático da imagem do QR Code.
- Alternativa para inserir manualmente a senha já existente e gerar apenas o QR Code.
- Interface responsiva, leve e compatível com qualquer navegador (incluindo mobile e iOS).

## ✅ Como usar

1. **Abrir o arquivo `index.html`** no navegador.
2. Preencha:
   - Nome da rede (SSID)
   - Selecione os tipos de caracteres desejados
   - Defina o tamanho da senha
3. Clique em **"Gerar QR Code + Senha"**.
4. A senha será exibida via alerta e o QR Code aparecerá abaixo.
5. A imagem do QR Code será baixada automaticamente como `.jpg`.

💡 Se já tiver uma senha e quiser apenas o QR Code, use a seção "✍️ Usar Senha Manual" no final da página.

## 🖼 Exemplo visual

| Geração automática | Senha manual |
|-------------------|---------------|
| ![auto](https://via.placeholder.com/200x200.png?text=Auto+QR) | ![manual](https://via.placeholder.com/200x200.png?text=Manual+QR) |

## 💻 Tecnologias

- HTML5
- CSS3
- JavaScript puro
- Biblioteca [QRCode.js](https://github.com/soldair/node-qrcode) via CDN

## 📦 Instalação local (opcional)

```bash
git clone https://github.com/seuusuario/wifi-qrcode-generator.git
cd wifi-qrcode-generator
