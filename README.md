# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v5.4.0

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v5.4.0.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v5.4.0/RaceFlow-v5.4.0.apk) |
| Windows | RaceFlow_Setup_v5.4.0.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v5.4.0/RaceFlow_Setup_v5.4.0.exe) |

Publicado em: 13/07/2026

---

## Notas da versão v5.4.0

### Novidades
- Vinculação de perfil de jogador aprimorada, com melhorias de UI
- Rastreamento e exibição de penalidades no dashboard de telemetria
- Projeto inicial do backend Cloudflare (raceflow-backend-cloudflare)
- Atualização de strings de localização e melhorias na vinculação de pilotos

### Correções
- Corrigido travamento indefinido no cadastro/login quando a rede bloqueia o Firebase (ex.: China) — agora exibe erro de conexão em vez de girar o loading para sempre
- Substituída dependência firebase-admin por REST API nas functions do Cloudflare
- Removida referência quebrada de submodule (.claude/worktrees)

### Outros
- Refatoração de estrutura de código para maior legibilidade e manutenção
- Remoção de diagnósticos e rotas temporárias de debug do backend Cloudflare
- Remoção do ViewerTeamsTab e atualização das funcionalidades do modal Novidades


---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
