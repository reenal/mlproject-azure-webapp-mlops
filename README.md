# Azure Web App MLOPS

1)create azur container regestry ( used it for storeing docker image)  

2) create azur web app (form image source container regestry )

3) get username password from container regestry

Login server : testdockerreenal.azurecr.io

Username : testdockerreenal

password : 

4) build and push docker image to container regestry

docker build -t testdockerreenal.azurecr.io/studentperformance:latest .

docker login testdockerreenal.azurecr.io

docker push testdockerreenal.azurecr.io/studentperformance:latest

5) web app seeting : deplyment center  option contiunus deplolyment ON