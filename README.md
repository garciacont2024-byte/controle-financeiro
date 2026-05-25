# Financeiro Pro — APK correto

## Estrutura

```text
.github/workflows/build-apk.yml
www/index.html
www/manifest.json
www/sw.js
package.json
capacitor.config.json
README.md
VALIDACAO.txt
```

## Como gerar o APK

1. Extraia o ZIP.
2. Suba para o GitHub o conteúdo da pasta `financeiropro-apk-final-correto`.
3. Vá em `Actions`.
4. Rode `Build Android APK`.
5. Baixe em `Artifacts > financeiro-pro-apk`.
6. O arquivo será `app-debug.apk`.

## Configuração usada

```json
{
  "appId": "com.garciacontabilidade.financeiropro",
  "appName": "Financeiro Pro",
  "webDir": "www"
}
```
