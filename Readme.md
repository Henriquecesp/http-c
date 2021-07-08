# 💻 Servidor HTTP | C | Sockets
Um servidor HTTP simples escrito em C usando soquetes. Solicitações GET e HEAD.

```bash
Distributor ID: Ubuntu
Description:    Ubuntu 20.04.2 LTS
Release:        20.04
Codename:       focal
```

## 📜 Instruções
1. Instale o `make`.
2. Clone o repositorio com o comando:
```bash
git clone https://github.com/Henriquecesp/http-c.git
```

3. Na pasta do projeto clonado rode o comando `make`:

```bash
make
```
4. Rode o servidor com:

```
./http-server
```
5. A aplicação estará disponivel em

```bash
http://localhost:3000/
```

## 🚀 Features
- Aceita requisições GET e HEAD.
- No caminho padrão retorna o `index.html`
- Se o caminho for `/contact` retorna o `contact.html`
- Retorna os status:
> `200 (OK)`

> `400 (Bad Request)`

> `404 (Not Found)`
