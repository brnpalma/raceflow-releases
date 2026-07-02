# RaceFlow — Releases

Distribuição pública dos instaladores do **RaceFlow**.

> Acesse o app em: https://raceflow-puce.vercel.app

## Download — versão atual: v3.12.0

| Plataforma | Arquivo | Link |
|------------|---------|------|
| Android | RaceFlow-v3.12.0.apk | [⬇ Baixar APK](https://github.com/brnpalma/raceflow-releases/releases/download/v3.12.0/RaceFlow-v3.12.0.apk) |
| Windows | RaceFlow_Setup_v3.12.0.exe | [⬇ Baixar instalador](https://github.com/brnpalma/raceflow-releases/releases/download/v3.12.0/RaceFlow_Setup_v3.12.0.exe) |

Publicado em: 02/07/2026

---

## Notas da versão v3.12.0

### Novidades
- Telemetria automática agora é totalmente global — sem mais configuração por liga. A tela de configuração (jogo/porta) tem acesso direto pelo novo item "Telemetria Auto" no menu lateral.
- Novo botão "Gravar Telemetria" em cada card de liga no dashboard, exibido apenas quando o monitor detecta dados do jogo e o plano permite o uso.
- Indicador no topo da tela mostra o status da captura em tempo real: amarelo para gravação temporária sem liga definida, azul (com o nome da liga em destaque) quando já vinculada a uma liga.
- Aviso ao fechar o app no Windows sempre que houver dados de telemetria não salvos (gravação em andamento ou temporária).
- Acesso à telemetria automática restrito ao plano Premium (antes também liberado incorretamente para o plano Piloto).
- Seleção de simulador/jogo na tela de configuração de telemetria virou um dropdown, no lugar da grade de botões.

### Correções
- Monitor de telemetria não desliga(ou liga) mais de forma inconsistente após trocar de plano.
- Sessão pendente (recuperação após fechamento inesperado durante uma gravação) não reaparecia mais indefinidamente mesmo depois de resolvida.
- Indicador de gravação não ficava mais preso mostrando dados da sessão anterior durante a revisão/finalização da corrida.
- Toasts e diálogos de telemetria corrigidos para não quebrar (Overlay ausente) e não esticar de ponta a ponta em telas grandes.
- Textos secundários (cinza) muito escuros e pequenos foram clareados e aumentados para melhor legibilidade em todo o app.

### Outros
- Largura mínima da janela (Windows) e do layout (Web) ajustada para não permitir redimensionar demais.
- Diversos ajustes visuais: ícones do menu lateral maiores, cores e destaque do card "Próxima Corrida".


---

## Versões anteriores

Veja todas as versões em [Releases](https://github.com/brnpalma/raceflow-releases/releases).
