# Áudio que Vende: Voz, Música e Sound Design v6.2

Curso gratuito com 12 aulas em 4 módulos, estilo OSWork v6.2. Reconstruir HTML: `python3 montar.py`.

Imagens Codex. Voz sintetizada pelo INEMAVOX/Chatterbox; música e efeitos obtidos pelo downloader INEMAVOX. Fontes e licenças em creditos.html. Arquivos de referência de voz privados não são distribuídos. Comparação sonora A/B gerada localmente, sem alegar execução no CapCut. Estimativa: 4–7 horas com produção, além das filas.

## English / Español

[English](https://inematds.github.io/curso-audio-video-ia/en/) · [Español](https://inematds.github.io/curso-audio-video-ia/es/)

Textos traduzidos com GPT-6 Luna por subagentes nativos da assinatura Codex, sem API externa. Ilustrações originais compartilhadas; progresso e anotações separados por idioma.

Após montar o português, reaplique os catálogos salvos:

```sh
python3 scripts/i18n_local.py build .
python3 scripts/verify_i18n.py .
node scripts/check_i18n_browser.cjs . /tmp/curso-i18n-checks
```

Requer Python/BeautifulSoup e os pacotes locais Babel/Playwright indicados nos scripts. A montagem não chama modelos nem redes. Mudanças na fonte PT exigem revisar os catálogos `i18n/`. O motor oficial `assets/curso.js` é preservado; a proteção de importação é gerada em `assets/curso-i18n.js` e nas edições traduzidas.

Evidências em `context/validacao-i18n.md`. Revisões por agentes são simuladas, não testes com alunos reais.
