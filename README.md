# Installation guides
Open terminal
git clone https://github.com/lamaparbat/amazon-web3.git
open the recently clone project in your favourite code editor [VScode, or Webstorm, or ... ]
npm install
npm run dev
Building steps
Open Vscode terminal and

npx create-next-app@latest amzon-web3 [init Frontend project]
npm add -D tailwindcss postcss autoprefixer [Css Framework]
npx tailwindcss init -p [Generate tailwindcss config file]
Replace the tailwindcss.config with https://tailwindcss.com/docs/guides/nextjs
mkdir smartcontracts [Contains smartcontracts]
npm run dev [Start frontend server]
Install additional npm packages

npm add react-icons react-spinners react-simple-hook-modal
 npm add @walletconnect/web3-provider @web3auth/web3auth ethers
npm add magic-sdk moment web3uikit
Now Let`s code

Go to /pages/index.js page and remove the ... and rename the title inside ...
