# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v5.6.1

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v5.6.1.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v5.6.1/RaceFlow-v5.6.1.apk) |
| Windows | RaceFlow_Setup_v5.6.1.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v5.6.1/RaceFlow_Setup_v5.6.1.exe) |

Publicado em: 15/07/2026

---

## Notas da versão v5.6.1

### Novidades
- Rastreamento de origem de cadastro no aviso do Telegram (site oficial vs GitHub Releases/versão antiga)
- Logs estruturados do console de debug agora chegam ao Sentry (aba Logs)
- Captura automática no Sentry de sessão perdida sem logout explícito (uid, e-mail, provedor, duração da sessão) — investigação do bug de login não persistindo no MSIX
- Eventos do Sentry agora marcados por variante de build (web/apk/exe/msix), além de development/production

### Correções
- Spinner de exclusão de conta travava indefinidamente em caso de erro de rede ou após sucesso (redirect do GoRouter acontecia antes do fechamento do diálogo)
- Timeout de 20s em toda a cadeia de exclusão de conta (reautenticação, histórico, Firestore)
- Mensagem de senha incorreta ao excluir conta agora aparece corretamente (Firebase Windows retornava código genérico)
- Reautenticação por senha ao excluir conta trocada de reauthenticateWithCredential (travava no plugin Windows) para signInWithEmailAndPassword

### Outros
- .sentry-native/ removido do controle de versão (arquivos de runtime local)

---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
