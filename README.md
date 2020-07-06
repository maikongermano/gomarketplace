<p align="center">
  <img src="./src/assets/logo@3x.png" />
</p>

# GoMarketplace
Este repositório é referente ao desafio 'Fundamentos do React Native' do Bootcamp GoStack 12.0, da Rocketseat 🚀.

# Proposta
Este projeto é um estudo do React-Native junto com o TypeScript, utilizando
rotas, Async Storage e a Context API.
A ideia é simular uma loja fictícia, trazendo dados de uma Fake API e integrar as informações disponíveis em tela, tais como quantidade de produtos e preço final.

<p align="center">
  <img src="gomarketplace.png" />
</p>

# Tecnologias Utilizadas 🚀
React ⚛️ <br />
React Native ⚛️ <br />
React Navigation ⚛️ <br />
Styled-Components ⚛️💅 <br />
React Icons ⚛️ <br />
Typescript 🦕

# Como obter esse repositório?
Para obter esse projeto, siga os passos:
1. Clone esse repositório utilizando <code>git clone</code>.
2. Rode o comando <code> yarn </code> na raíz da pasta do projeto clonado para baixar as dependências.
3. Rode <code> yarn start </code> na raíz da pasta do projeto para inicializar o Metro Bundler.
4. Rode o comando <code> yarn android</code> (se estiver emulando em um android) ou <code>yarn ios</code> (se estiver emulando em um ios) na raíz da pasta do projeto clonado para instalar o app no emulador.
5. Rode <code>yarn json-server server.json -p 3333</code> na raíz da pasta do projeto para inicializar a Fake API.
6. Rode <code>yarn json-server --host 0.0.0.0 server.json --port 3333</code>caso queira utilizar uma fake API com host
7. Abra o projeto no seu emulador.

⚠️ Caso o projeto não mostre os produtos, rode <code>adb reverse tcp:3333 tcp:3333</code> antes de iniciar a Fake API ⚠️

# Como Contribuir?
**Faça um fork deste repositório**

```bash
# Clone o seu fork
$ git clone url-do-seu-fork && cd GoMarketplace

# Crie uma branch com sua feature ou correção de bugs
$ git checkout -b minha-branch

# Faça o commit das suas alterações
$ git commit -m 'minhas alterações'

# Faça o push para a sua branch
$ git push origin minha-branch
```

Delete sua branch, se quiser, quando o merge da sua pull request for feito. <br />


