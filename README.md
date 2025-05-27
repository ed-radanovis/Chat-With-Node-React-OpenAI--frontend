# Chat with Node React OpenAI Frontend

## Academic project for delivery

### Bootcamp AWS Cloud Week - DIO 
(taught by Cassiano Peres DIO Tech Education Analyst).
<br>

The result of the completed project.
 <br>

> 🎯 Objective:
>
> - Develop a functional chat that allows instant communication between users, with an implemented integration to interact with **[ChatGPT](https://openai.com/api)** directly in the application, without needing other software.

> - This project was a challenging and enriching experience where I learned how to implement WebSocket for real-time communication and mastered the Serverless backend deployment, which was one of the highlights, since the business logic is executed in managed cloud computing services ( **[AWS Lambda](https://aws.amazon.com/lambda)**, **[API Gateway](https://aws.amazon.com/api-gateway)** and **[AWS Amplify](https://aws.amazon.com/amplify)** ( frontend ) ), without the need to provision, manage and scale physical or virtual servers, which greatly facilitated the architecture.

<br>

<p align="center">
<img src="public/_print_front_1.png" alt="print-screen-image" width="600px" >
</p>
<br>
<br>
<div align="center">
 <a href="https://master.d2uwqmfwqjokju.amplifyapp.com/" >Click here to try it out .. thanks for your interest!</a>
 <p>( Select Ctrl + click for open in new tab )</p>
</div>
 <br>
 <br>


### Adjustments and improvements

The project was fully completed and some of the resources used were:

- [x] **Frontend**:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![React](https://img.shields.io/badge/-React-333333?style=flat&logo=react)](https://reactjs.org)&nbsp;&nbsp;[![TypeScript](https://img.shields.io/badge/-TypeScript-333333?style=flat&logo=typescript&logoColor=2F74C0)](https://www.typescriptlang.org) &nbsp;&nbsp;[![HTML5](https://img.shields.io/badge/-HTML5-333333?style=flat&logo=HTML5)](https://developer.mozilla.org/en-US/docs/Web/HTML) &nbsp;&nbsp;[![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)](https://developer.mozilla.org/en-US/docs/Web/CSS)&nbsp;&nbsp;[![MUI](https://img.shields.io/badge/-MUI-333333?style=flat&logo=MUI)](https://mui.com)<br>


- [x] **Backend**:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Node.js](https://img.shields.io/badge/-Node.js-333333?style=flat&logo=Node.js)](https://nodejs.org)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![npm](https://img.shields.io/badge/-npm-333333?style=flat&logo=npm&logoColor=d31f25)](https://www.npmjs.com)<br>

- [x] **Integration**:&nbsp;&nbsp;&nbsp;[![ChatGPT](https://custom-icon-badges.demolab.com/badge/-OpenAI-333333?logo=openai&logoColor=74AA9C)](https://openai.com/api)<br>

- [x] **Testing**:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![wscat](https://img.shields.io/badge/wscat-333333?logo=npm)](https://www.npmjs.com/package/wscat)<br>

- [x] **Hosting and Deployment**:&nbsp;&nbsp;&nbsp;&nbsp;[![AWS](https://img.shields.io/badge/-AWS-333333?logo=amazon)](https://aws.amazon.com)&nbsp;&nbsp;[![AWS Amplify](https://img.shields.io/badge/AWS%20Amplify-333333?logo=aws-amplify&logoColor=db2f37)](https://aws.amazon.com/amplify)<br>

- [x] **Database**:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![AWS DynamoDB](https://img.shields.io/badge/AWS%20DynamoDB-333333?logo=amazon-dynamodb&logoColor=5398d4)](https://aws.amazon.com/dynamodb)

#### ⚙️ Steps for the project

 ✔️ - Install the dependencies with the `npm install` command <br>
 ✔️ - Update the `.env` file with your OpenAI key <br>
 ✔️ - Compress the project contents into a `.zip` file <br>

#### 🌐 AWS

 ✔️ - Access the AWS console <br>
 ✔️ - Create a function in the AWS Lambda service <br>
 ✔️ - Upload the contents of the `.zip` file in the function code <br>
 ✔️ - Access the AWS API Gateway service <br>
 ✔️ - Create a Websocket API <br>
 ✔️ - Create the endpoints <br>
 
 📝 Note: the first three endpoints marked with `$` are the default for an API Gateway Websocket API: <br>
 
 🔗 - `$connect` <br>
 🔗 - `$disconnect` <br>
 🔗 - `$default` <br>
 🔗 - `setName` <br>
 🔗 - `sendPublic` <br>
 🔗 - `sendPrivate` <br>
 🔗 - `sendBot` <br>

  #### 🔬 Testing Websocket

✔️ - Download the `wscat` dependency using the `npm i -g wscat` command. <br>
✔️ - Use the `-g` parameter to install it globally on the operating system and call it from outside the project.<br>
✔️ - Connect to the WebSocket API: `wscat -c <websocket_connection_url>`<br>
✔️ - Example calls:
- [x] Public message: `{"action":"sendPublic", "message":"Hello World!"}`
- [x] Interact with ChatGPT: `{"action":"sendBot", "message":"Which programming language has the biggest impact on the market at the moment?"}`
<br>

As described in the [![AWS WebSocket Docs](https://img.shields.io/badge/AWS%20WebSocket-Docs-%23232F3E?logo=amazon-aws&logoColor=white)](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html), **wscat** is recommended for testing WebSocket APIs on API Gateway, especially in real-time chat projects, collaboration platforms, multiplayer games, and financial trading platforms.

<h4 align="center">
  🤝 Collaborators
<h4/>
<table align="center"
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/edmar-radanovis-0130b611a/">
        <img src="public/Logo_EWD_APEX.png" width="80px;"height="80px;" alt="Logo da EWD Apex"/><br>
      <sub>
        <b>Edmar Radanovis</b>
      </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.dio.me/">
        <img src="public/logodio.jpg" width="80px;" height="80px;" alt="Logo DIO"/><br>
      <sub>
        <b>DIO.me</b>
      </sub>
      </a>
    </td>
  </tr>
</table>
<br>

<h4 align="center">
  🥇 Certificates
<h4/>
<table align="center">
  <tr>
    <td align="center">
      <img src="public/Certificado 35 _  primeiros passos com AWS.png" width="80px;" height="80px;" alt="Imagem Certificado"/><br>
    </td>
    <td align="center">
      <img src="public/Certificado 36 _  imersão ao ecossistema Cloud Data AWS.png" width="80px;" height="80px;" alt="Imagem Certificado"/><br>
    </td>
    <td align="center">
      <img src="public/Certificado 37 _  desenvolvendo soluções Serveless na AWS.png" width="80px;" height="80px;" alt="Imagem Certificado"/><br>
    </td>
    <td align="center">
      <img src="public/Certificado 38 _  infraestrutura como código com Serveless com framework na AWS.png" width="80px;" height="80px;" alt="Imagem Certificado"/><br>
    </td>
  </tr>
</table>
<br>
<br>

[⬆ Voltar ao topo](#chat-with-node-react-openai-frontend)
