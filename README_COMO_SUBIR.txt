# mcc-repo corrigido para Aniyomi

Arquivos principais:
- index.min.json: usado pelo Aniyomi
- index.json: igual ao index.min.json, só formatado
- repo.json: fingerprint da assinatura dos APKs
- aniyomi-pt.anitube.apk
- aniyomi-pt.doramogo.apk
- icon/

Link para adicionar no Aniyomi:
https://raw.githubusercontent.com/Biiwl/mcc-repo/repo/index.min.json

Comandos para subir:
```powershell
cd C:\Users\biiel\Downloads\mcc-repo-repo_corrigido

git init
git checkout -B repo

git remote remove origin
git remote add origin https://github.com/Biiwl/mcc-repo.git

git add .
git commit -m "corrigir repo aniyomi"
git push -u origin repo --force
```

Teste no navegador:
https://raw.githubusercontent.com/Biiwl/mcc-repo/repo/index.min.json
https://raw.githubusercontent.com/Biiwl/mcc-repo/repo/aniyomi-pt.anitube.apk
https://raw.githubusercontent.com/Biiwl/mcc-repo/repo/aniyomi-pt.doramogo.apk
```
