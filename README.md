## INICIATIVA KUBERNETES - Desafio 1

Para gerar uma nova imagem executar seguinte comando no diretório "src":
```
docker image build -t <namespace>/<repository>:<tag> .
```

Para executar imagem gerada:
```
docker run -d -p 8080:8080 <namespace>/<repository>:<tag>
```
ou teste com imagem do meu repositório:
```
docker run -d -p 8080:8080 leandrojbraga/kubedev-desafio1:v1.0
```

e em seu navegador:
```
http://localhost:8080/
```
