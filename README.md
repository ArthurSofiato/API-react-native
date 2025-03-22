📱 Aplicativo de Listagem de Produtos  

Este é um aplicativo React Native que consome a API [DummyJSON](https://dummyjson.com/products) para listar produtos e exibir detalhes.  

🛠 Tecnologias Utilizadas  

- React Native  
- Expo
- React Navigation  

🚀 Como Rodar o Projeto  

1️⃣ **Pré-requisitos**  

Certifique-se de ter instalado:  
- Node.js (recomendado: versão LTS)  
- Expo CLI (se ainda não tiver, instale com `npm install -g expo-cli`)  

2️⃣ **Clone o repositório**  

git clone https://github.com/ArthurSofiato/API-react-native.git
cd API-react-native


3️⃣ Instale as dependências  

npm install


4️⃣ **Inicie o projeto**  

npx expo start


Esse comando abrirá o Metro Bundler no navegador. Para rodar o app:  
- No **Android**, escaneie o QR Code com o Expo Go.  
- No **iOS**, abra no simulador com `i` (caso tenha um Mac).  

📂 Estrutura do Projeto  

```
/seu-repositorio
│── /assets               # Imagens e ícones do projeto  
│── /screens              # Telas do aplicativo  
│   ├── HomeScreen.js     # Tela de listagem de produtos  
│   ├── DetailsScreen.js  # Tela de detalhes do produto  
│── /components           # Componentes reutilizáveis  
│   ├── ProductCard.js    # Card de produto  
│── App.js                # Componente principal  
│── package.json          # Dependências do projeto  
│── README.md             # Documentação  
```
📝 Funcionalidades  

✅ Listagem de produtos exibidos em cards.  
✅ Botão "Ver Detalhes" para acessar a descrição completa.  
✅ Tela de detalhes com nome, preço, descrição e imagem do produto.  
✅ Design responsivo com fundo preto e botões laranja.  

📌 Observações  

Caso tenha problemas com cache, execute:  

npx expo start --clear


📖 Licença  

Projeto desenvolvido para fins de aprendizado. Sinta-se à vontade para modificar!
