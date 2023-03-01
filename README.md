LAB do crescer 
============================

**Pré-requisitos**
- Maven
- Jdk 11

**No terminal  execute a instrução abaixo para gerar o .jar**
```bash
mvn clean install -DskipTests
```

**No terminal do intellij execute o wsl**
```bash
wsl
```

**Conectado no wsl, construir imagem docker**
```bash
docker build -t hello-docker:latest .
```

**Conectado no wsl, executar imagem docker**
```bash
docker run --name hello-docker -p 9320:8080 hello-docker:latest
```

**Faça bom proveito!**

