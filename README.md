# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v4.0.0

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v4.0.0.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v4.0.0/RaceFlow-v4.0.0.apk) |
| Windows | RaceFlow_Setup_v4.0.0.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v4.0.0/RaceFlow_Setup_v4.0.0.exe) |

Publicado em: 08/07/2026

---

## Notas da versão v4.0.0

### Novidades
- Instalador Windows não exige mais permissão de administrador — instala em pasta do usuário e cria o atalho na área de trabalho pessoal
- Atualização silenciosa no Windows: baixa, instala e reabre o app automaticamente, sem deixar instaladores acumulados
- Tag "Atualização disponível" agora tem botões "Ignorar" e "Atualizar"
- Menu lateral: item renomeado para "Transmissão", com indicador "Online" quando o servidor de overlays está ativo
- "Gerar dados de teste" nos Overlays de Transmissão agora abre um modal com seleção Corrida/Quali, disponível em qualquer tamanho de tela

### Correções
- Notificação de novo usuário movida para o backend — o token do bot do Telegram deixou de ser embutido nos builds do app (Web/Android/Windows)
- Diversos ajustes de responsividade na tela de Overlays de Transmissão (URL, botões e cards em telas pequenas)

### Outros
- Migração do instalador de Program Files para instalação por usuário (%LocalAppData%)

---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
