# Peso e Cintura — app Android (v2.0)

Versão Android (Capacitor 7) do app de peso, cintura e IMC. A versão web continua na branch `main`.

Novidades em relação à versão web: lembrete semanal (notificação), previsão da meta, quadril e relação cintura/quadril, modelo 2D do corpo (atual, meta, ideal), backup automático em Documentos/PesoECintura e exportação em planilha (CSV). Funciona offline (fontes embutidas).

## Gerar o APK
```
npm install
npx cap sync android
cd android && ./gradlew assembleRelease   # requer android/keystore.properties e a chave .jks (não versionadas)
```
O código do app fica em `www/index.html`.
