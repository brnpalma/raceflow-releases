# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v3.16.0

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v3.16.0.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v3.16.0/RaceFlow-v3.16.0.apk) |
| Windows | RaceFlow_Setup_v3.16.0.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v3.16.0/RaceFlow_Setup_v3.16.0.exe) |

Publicado em: 07/07/2026

---

## Notas da versão v3.16.0

### Novidades
- Nova opção de desenvolvedor para travar a frequência de processamento dos overlays de transmissão (10/20/30/60Hz), independente da configuração do jogo.
- Ao gravar telemetria para uma liga com divisões, o app agora pergunta qual divisão usar (antes escolhia a primeira automaticamente).
- Botão "Editar Equipe" mais visível na tela de revisão de pontuação (antes era um ícone de lápis discreto), e a lista de equipes agora mostra o logo de cada uma.

### Correções
- Corrigido travamento/lentidão geral do app durante sessões de telemetria com múltiplos overlays de transmissão abertos ao mesmo tempo.
- Overlays de transmissão (delta, classificação ao vivo, engenheiro, mapa da pista, gauges) agora resetam corretamente ao reiniciar uma sessão no jogo — antes alguns dados (ex: melhor volta) ficavam "grudados" da sessão anterior.
- O overlay de delta agora continua contando a volta em andamento durante in-lap/out-lap (antes só funcionava em volta rápida), e mostra "BOX" quando o piloto está na garagem.
- Corrigido overlay de delta ficando preso mostrando "-" ao reabrir manualmente o card de um piloto.
- O ícone de volta mais rápida na Classificação ao vivo agora só aparece em sessões de corrida (em quali/treino já existe o destaque em roxo no tempo).
- Corrigida quebra de linha do texto "No Time" no overlay de Classificação ao vivo.

### Outros
- Atualização de versão e binários de build.


---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
