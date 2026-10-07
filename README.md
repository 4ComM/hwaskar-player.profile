# Hwaskar — Player Profile

Documento de arquivo único produzido pela 4ComM. Trilíngue (PT/EN/ES), abre em português.

**No ar:** https://4comm.github.io/hwaskar-player.profile/

Primeira versão publicada em 07/10/2026, aberta a ajustes depois da validação do gestor.
Fora dos buscadores (`noindex, nofollow`), abre só para quem tem o link.

Gerado a partir do repositório `4comm-player-profiles`:

```
python -X utf8 _fontes/hwaskar/monta_dados.py   # dados.json a partir do dossiê de fontes
python -X utf8 constroi.py hwaskar              # remonta o HTML
python -X utf8 valida.py hwaskar                # checklist estrutural
```

Fotos: `_fontes/hwaskar/prepara_fotos.py`. Dossiê de fontes no Drive, em `01_ATLETAS/hwaskar/`.

Versão única: atualização substitui o `index.html` no mesmo lugar. Nunca criar
repositório novo para o mesmo atleta.
