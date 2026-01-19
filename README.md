# Weather App 🌤️

Aplicação simples para consulta de clima em tempo real usando a OpenWeather API.

## 🔧 Tecnologias
- HTML
- CSS (Glassmorphism)
- JavaScript
- OpenWeather API

## 🚀 Como rodar o projeto
1. Clone o repositório
2. Copie o arquivo `js/config.example.js` para `js/config.js`:
   ```bash
   cp js/config.example.js js/config.js
   ```
3. Edite o arquivo `js/config.js` e insira sua API Key da OpenWeather:
   ```js
   export const WEATHER_API_KEY = "SUA_API_KEY";
   ```
4. Abra o arquivo `index.html` no navegador ou use um servidor local

## 📝 Obtenha sua API Key
1. Acesse [OpenWeather Map](https://openweathermap.org/api)
2. Crie uma conta gratuita
3. Gere sua API Key
4. Cole a chave no arquivo `js/config.js`