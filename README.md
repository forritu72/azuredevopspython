# azuredevopspython


az group create --name pythonwebappnaveen --location westus

az appservice plan create --resource-group pythonwebappnaveen --name pythonwebappplannaveen --is-linux --sku B1

az webapp create --resource-group pythonwebappnaveen --plan pythonwebappplannaveen --name pythonwebappsnaveen --runtime "Python|3.7"

git init

git clone url

git add .

git commit -m 'First commit'

git status

git branch

git remote

git remote add alias url

git push alias branch

git push remotetest master
