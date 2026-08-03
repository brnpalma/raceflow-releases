<div align="center">

<img src="https://raw.githubusercontent.com/brnpalma/raceflow-releases/main/logo_app_transp.png" width="100" alt="RaceFlow Logo" />

# RaceFlow

**Gerencie seus campeonatos de automobilismo como um verdadeiro chefe de equipe.**

[![Version](https://img.shields.io/badge/versão-6.7.0-blue?style=flat-square)](https://github.com/brnpalma/raceflow-releases/releases/tag/v6.7.0)
[![Flutter](https://img.shields.io/badge/Flutter-3.7-02569B?style=flat-square&logo=flutter)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Platform](https://img.shields.io/badge/plataforma-Web%20%7C%20Android%20%7C%20Windows-lightgrey?style=flat-square)](https://flutter.dev)

[🌐 Acesse a Landing Page](https://raceflow-puce.vercel.app) · [📱 Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v6.7.0/RaceFlow-v6.7.0.apk) · [🪟 Baixar na Microsoft Store](https://apps.microsoft.com/detail/9NSV6W2XSVCH)

</div>

---

Distribuição pública dos instaladores do **RaceFlow**.

## Sobre o RaceFlow

RaceFlow é uma plataforma multiplataforma para criar e gerenciar campeonatos de automobilismo — virtual ou real. Suporta as principais categorias do automobilismo mundial com dados reais pré-carregados, telemetria automática via UDP sem plugins, overlays de transmissão prontos pra OBS, e visualização pública sem necessidade de conta.

Disponível para **Web**, **Android** e **Windows**.

## Download — versão atual: v6.7.0

| Plataforma | Como baixar |
|------------|-------------|
| Android | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v6.7.0/RaceFlow-v6.7.0.apk) |
| Windows | [🪟 Baixar na Microsoft Store](https://apps.microsoft.com/detail/9NSV6W2XSVCH) |

Publicado em: 03/08/2026

---

## Notas da versão v6.7.0

### Novidades
- Notificação de incidente pro piloto acusado (quando o piloto já tem usuário vinculado), com opção de ignorar ou registrar defesa direto pela tela de Notificações
- Reclamante pode excluir o próprio registro de incidente antes de decidido
- Stepper +/- pra pontos/segundos de penalidade na análise de incidente (mesmo padrão da pontuação de nova liga)
- Card de incidente mostra piloto acusado e acusador (Organizador/Piloto) com nome
- Divisões: vínculo acima/abaixo agora sincroniza os dois lados automaticamente
- Notificação de nova release via GitHub Actions

### Correções
- Contador de notificações na barra lateral não contava incidentes pendentes
- Layout do formulário de registrar incidente (botão no rodapé, ajustado ao conteúdo)
- Diálogo de "sem dados" da telemetria
- Regras do Firestore: brecha que permitia qualquer usuário autenticado escrever em dados de qualquer liga

### Outros
- Ajustes de localização (pt/en)


---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
