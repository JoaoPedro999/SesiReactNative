# React Native

[- Comandos](#-comandos-utilizados-em-react-native) <br>
[- Export x Export Default](#-explicações) <br>

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="30" height="30"/> Comandos utilizados em React Native
&ensp; &ensp; ``` npx create-expo-app nomedoseuapp ``` <br>
&ensp; &ensp; 🚀 Cria um novo projeto Expo. <br> <br>

&ensp; &ensp; ``` npx expo install react-native-web react-dom @expo/metro-runtime ``` <br>
&ensp; &ensp; 🔧 Instala as dependências necessárias para executar o aplicativo no navegador. <br> <br>

&ensp; &ensp; ``` npx expo start ``` <br>
&ensp; &ensp; ▶️ Inicia o projeto. <br> <br>

&ensp; &ensp; ``` npx expo start --tunnel ```<br>
&ensp; &ensp; 🔗 Inicia o projeto com suporte a conexões externas. <br> <br>

&ensp; &ensp; ``` npx expo start --web ``` <br>
&ensp; &ensp; 🌐 Inicia o servidor de desenvolvimento no ambiente web. <br> <br>

&ensp; &ensp; ``` npm install @react-navigation/native ``` <br>
&ensp; &ensp; 🔖 Instala o pacote em seu projeto, que fornece as funcionalidades básicas para navegação. <br> <br>

&ensp; &ensp; ``` npx expo install react-native-screens react-native-safe-area-context ``` <br>
&ensp; &ensp; 📱 Instala dependências necessárias para o correto funcionamento do React Navigation em projetos Expo. <br> <br>

&ensp; &ensp; ``` npm install @react-navigation/native-stack ``` <br>
&ensp; &ensp; ↔️ Instala o pacote Stack que gerencia a navegação entre diferentes telas. <br> <br> <br> <br>

## <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitbook/gitbook-original.svg" width="40" height="40" /> Explicação sobre export e export default<br>

- <strong>export vs export default</strong>: <br>
No JavaScript, há duas formas de exportar funcionalidades de um arquivo: utilizando <strong>export</strong> e <strong>export default</strong>.  <br><br>
Quando você exporta uma constante, função ou classe usando apenas <strong>export</strong>, você precisa importá-la exatamente pelo nome que foi exportado, e, para importar múltiplas coisas, você precisa envolvê-las entre chaves {}, exemplo:
```
// Arquivo1.js
export const minhaFuncao = () => {
    // código da função
};

// Arquivo2.js
import { minhaFuncao } from './Arquivo1';
```
&ensp; &ensp;  Quando você usa <strong>export default</strong>, você está exportando uma única coisa que será considerada como o valor padrão do arquivo.<br> 
&ensp;&ensp; &ensp;Isso significa que quando você importa, você pode dar a esse valor o nome que desejar, não precisando envolvê-lo entre chaves, exemplo:

```
// Arquivo1.js
const meuValorPadrao = 10;
export default meuValorPadrao;

// Arquivo2.js
import qualquerNome from './Arquivo1';
```       




