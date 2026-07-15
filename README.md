# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v5.7.0

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v5.7.0.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v5.7.0/RaceFlow-v5.7.0.apk) |
| Windows | RaceFlow_Setup_v5.7.0.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v5.7.0/RaceFlow_Setup_v5.7.0.exe) |

Publicado em: 15/07/2026

---

## Notas da versão v5.7.0

### Correções
- Login não persistia ao fechar/reabrir o app no Windows: firebase_auth deixava `currentUser` null por até ~20s na inicialização, fazendo o app redirecionar pra tela de login antes da sessão real carregar. Corrigido via upgrade do Firebase (firebase_core 4.x, firebase_auth 6.x, cloud_firestore 6.x, firebase_analytics 12.x).
- Duas instâncias do RaceFlow abertas ao mesmo tempo no Windows (ex.: versão instalada + MSIX) derrubavam a sessão de login uma da outra. Agora o app detecta instância já em execução (exe, portátil ou MSIX) e mostra aviso em vez de abrir uma segunda janela conflitante.
- Corrigido encoding de acentos em mensagens nativas do Windows (MSVC compilando sem UTF-8 explícito).
- Corrigida falha de build Android causada por incompatibilidade de versão do Kotlin com o firebase_analytics atualizado.

### Outros
- Instrumentação extra no Sentry para diagnosticar perda de sessão (uid, e-mail, provedor, duração da sessão, plataforma/variante de build).

---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
