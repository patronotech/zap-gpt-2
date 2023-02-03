# ZAP-GPT

### Clonar o projeto
Clone este projeto com o código abaixo:

```bash
$ git clone https://github.com/patronotech/zap-gpt-2.git
```
--- 

### O que você vai precisar?

> Open-AI API Key
- Click em [this link](https://beta.openai.com/account/api-keys), e no botão `Create new secret key`

> Organization ID (Open-AI)
- Click em [this link](https://beta.openai.com/account/org-settings), selecione sua organização e obtenha o Organization ID.

> Tenor API Key  
- Siga as instruções para gerar uma [TENOR API KEY here](https://developers.google.com/tenor/guides/quickstart)

Copie o arquivo `env.local` para a pasta raiz e renomeie-o para `.env`.

```bash
$ cp <PATH>/.env.local .env 
```
Depois disso, coloque a KEY, Organization ID, seu número de telefone e a TENOR API KEY nas variáveis.

---  
### Como executar o projeto?

Primeiro de tudo, faça um `npm install` para instalar todas as dependências.

```bash
$ cd <PATH> && npm install
```
Depois disso, execute o projeto com `npm start`

```bash
$ npm start
```
---

### Recursos

- **/chatbot \<text\>**
  - Use o comando acima para perguntar algo e o bot retornará uma resposta. Por exemplo.:
    > */chatbot Como faço um bolo?*
- **/imgbot \<description\>**
  - Use o comando acima para gerar uma imagem DALL-E. Por exemplo.:
    > */imgbot gerar imagem de um bolo*
- **/stickerbot**
  - O Comando acima funciona de duas maneiras:
    - Com uma imagem no whatsapp e apenas com o comando como descrição. Por exemplo.: 
    > (image)  
    > */stickerbot*
  - Com uma URL. Por exemplo.:
    > */stickerbot https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/Pound_layer_cake.jpg/800px-Pound_layer_cake.jpg*
  - Com palavras-chave. Por exemplo.:
    > */stickerbot bolo de chocolate*
- **/imgvarbot**
  - O comando acima funciona como o comando _/stickerbot_ e irá gerar uma nova variante da imagem. Ex.: (com url):
    > */imgvarbot https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/Pound_layer_cake.jpg/800px-Pound_layer_cake.jpg*

---

# NÃO USE ESTE BOT PARA PERGUNTAR COISAS ERRADAS!
