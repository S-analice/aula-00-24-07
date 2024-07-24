Comandos para antes de fazer o commit:
git config --local user.name "ANA" 
git config --local user.email "analice.santos200308@gmail.com"
git add NomeArquivo.txt
git commit -m "Mensagem do comit"
git push origin main 

git checkout -b teste
git push origem teste
git config --local user.name "ANA" 
git config --local user.email "analice.santos200308@gmail.com"
git add OutroNomeArquivo.txt
git commit -m "Mensagem do comit"
git push origin teste