Mini Perfil App
Este é um projeto simples de React Native com Expo que demonstra a criação de um aplicativo de duas telas com navegação e gerenciamento de estado.

1. Criar o projeto
npx create-expo-app mini-perfil --template blank

2. Navegar para a pasta do projeto
cd mini-perfil

3. Instalar o Expo Router e suas dependências
npx expo install expo-router react-native-safe-area-context react-native-screens

4. Configurar o Expo Router no package.json
Certifique-se de que a linha "main" esteja configurada para "expo-router/entry".

  "main": "expo-router/entry",


5. Iniciar o servidor de desenvolvimento
npx expo start
