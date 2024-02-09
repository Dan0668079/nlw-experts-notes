## Instalação

1. Clone o repositório.
2. `cd` para o diretório do projeto.
3. Execute `npm install` para instalar as dependências.

## Uso

1. Execute `npm start` para iniciar o servidor de desenvolvimento.

2. intalar Install Tailwind CSS with Vite
   2.1 para instalar use os comandos `npm install -D tailwindcss postcss autoprefixer` e depois `npx tailwindcss init -p`.

3. Na pasta `tailwind.config.js` adicione:
   3.2 content: [
   "./index.html",
   "./src/**/*.{js,ts,jsx,tsx}",
   ],

4. Na pasta`./src/index.css` adicione:
   4.1
   @tailwind base;
   @tailwind components;
   @tailwind utilities;

5. Usando radix-ui.com
   5.1 para instalar o modal dialog use o comando `npm install @radix-ui/react-dialog`.

6. Instalar a lib date-fns :
   6.1 `npm install date-fns`.

7. Instalar a lib lucide-react:
   7.1 `npm install lucide-react`.

8. Intalar a lib sonner:
   8.1 `npm install sonner`.

9. para utilizar SpeechRecognitionEvent API e o typeScript entender vamos instalar :
   9.1 `npm install -D @types/dom-speech-recognition`.
