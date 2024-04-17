# Manipulando Branches

## 1. Para criar uma nova branch a partir de outra
    git checkout -b nova-branch
    
## 2. Para add a branch ao repo remoto
	git push --set-upstream origin nome-branch

## 3. Para juntar os updates das branches conectadas
(vou para a branch que vai receber o update e faco o segunte comando)
	git rebase branch-com-update
    

## 4. para renomear a branch local
	git branch -m novo-nome

## 5. Para deletar a branch local
	git branch -d nome-branch

## 6. Para deletar a branch remota
	git push origin --delete nome-branch


Referencias: 

https://www.youtube.com/watch?v=HBDJGsPn7rk

https://www.youtube.com/watch?v=2ClyXNbdx8I

https://www.youtube.com/watch?v=cEfoB8Hl2gY

https://www.youtube.com/watch?v=cEfoB8Hl2gY
