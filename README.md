Para baixar os commits do repositório: git clone <url_do_repositorio>
Para ver histórico usar: git log .
Para conectar ao repositório e enviar mudanças: git push origin main
Rastreia e adiciona todos os arquivos do diretório: git add .
Pega as atualizações do github e coloca para dentro do projeto aberto atualmente: git pull origin main
Para preparar commit: git commit -m "sua mensagem"
Para verificar status: git status
Para ver branches remotas: git remote -v
Para ver histórico usar: git log --oneline

*****  Passo a passar para criar uma nova Branche: ******

Para criar uma nova Branche: git checkout -b feature-teste (essa última parte é o nome da Branche)
Muda a branche para o local existente: git checkout feature-teste
Adciona as mudanças: git add . 
Faz commit se houver mudanças: git commit -m "Primeira feature teste"
Enviar para o github: git push origin feature-teste

***** Para usar uma branche ou a outra: ******

Muda para main: git checkout main          
Afeta apenas main: git add . ; git commit -m "..."  
Envia só main: git push origin main       

Muda para feature-teste: git checkout feature-teste  
Afeta APENAS feature-teste: git add . ; git commit -m "..."  
Envia só feature-teste: git push origin feature-teste 