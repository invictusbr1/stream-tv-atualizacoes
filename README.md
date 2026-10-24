# stream-tv-atualizacoes
Instaladores e atualizações do Stream TV para Android e TV Box.

## Segurança das versões

Não publique APKs contendo chaves do Groq, Gemini ou credenciais administrativas. O Jarvis deve chamar o servidor do aplicativo; somente o servidor guarda a chave de IA.

Antes de enviar uma release, execute `android/Verificar-Segredos-Apk.ps1` do repositório `stream-tv-app` para cada APK. A verificação automática deste repositório examina arquivos e APKs versionados; ela não examina anexos de releases. O publicador atualizado do aplicativo verifica Android e TV antes do envio.

Chaves presentes em versões anteriores devem ser revogadas no painel do provedor. Alterar este repositório não invalida chaves em downloads, releases ou commits antigos. Substitua os instaladores por builds verificados após configurar o Jarvis no servidor.
