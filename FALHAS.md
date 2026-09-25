# Falhas

| data | o que quebrou | menor correção | prompt ou infra |
| 2026-09-25 | Teste de mídia iniciou antes do fim da gravação do MP3 | Aguardar a geração antes de carregar no navegador | infra |
| 2026-09-25 | Transientes reduziram demais o nível médio da mistura | Controlar picos da voz e efeitos antes de somar as camadas | infra |
| 2026-09-25 | Ducking omitia terceiro ponto de volume e ação para inserir pontos | Explicitar quatro pontos e alternativa Dividir, Volume e Fade | prompt |
| 2026-09-25 | Prática de classificar fontes não separava misturas A/B do kit | Identificar seis fontes e guardar A/B como demonstrações | prompt |
| 2026-09-25 | Auditoria encontrou termo download sem explicação | Usar baixar arquivos na redação e nos links | prompt |
| 2026-09-25 | Verificação de áudio falhou ao serializar float32 | Converter números numpy em float no JSON | infra |
| 2026-09-25 | Pico da prévia de papel ultrapassou 0 dBFS após conversão MP3 | Aplicar margem de pico antes da codificação e medir novamente | infra |
| 2026-09-25 | Personagens variaram nas imagens 4 e 12 | Editar usando a imagem 1 como referência | prompt |
| 2026-09-25 | Cartões de fala viraram cenas sem relação na imagem 5 | Substituir por cartões de roteiro com linhas | prompt |
| 2026-09-25 | Transcrição da primeira voz divergiu no verbo da frase central | Simplificar a frase e gerar uma nova tomada para conferir | prompt |
