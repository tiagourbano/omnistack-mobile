npm install
cd ios
pod install
cd ../
npx react-native run-ios || npx react-native run-android


P.S.: toda vez que mudar o projeto de pasta, precisa apagar a pasta: ModuleCache.noindex dentro de ios/build/nome_do_projeto/. E entao rodar o comando npx react-native run-ios

P.S.: se for emular diretamente no celular android, precisa rodar o comando: adb reverse tcp:3333 tcp:3333 e garantir que a porta 3333 é a mesma da API

https://facebook.github.io/react-native/docs/debugging
