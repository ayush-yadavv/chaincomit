<h1 align="center"> chain-Comit </h1> <br>

<hr>

# Introduction

Chain-Comit is a Decentralized Platform for Open Source developers. It provides a platform for developers to find projects to work on and get rewarded for their work. It also provides a platform for project owners to find developers to work on their projects and pay them in crypto. Developers can post their projects issues and get it solved by other developers.

# Working

1. User can post their project issues and get it solved by other developers.
2. Once the issue is posted it will be visible to all the developers.
3. Developers can choose the issue they want to work on and request to work on it by clicking on the "Request" button.
4. Once the request is sent the issue will be visible in the trying issues section of the user's profile.
5. Once requested, the user can start working on the issue. After successfully solving the issue the user can create a pull request.
6. Once the pull request is merged by the project owner, the user have to claim the reward by submitting the pull request number and marking the issue as completed.
7. Once the issue is marked as completed the project owner will be able to see the Pay user button in the My issue section.
8. Once the user is paid the issue will be marked as completed and the user will be able to see the issue in the completed issues section of his profile.

# Advantages

Open Source: GithubCrypt is an open source project and anyone can contribute to it.

Decentralized: GithubCrypt is a decentralized platform and it is not controlled by any single entity.

Secure: GithubCrypt is a secure platform as all the data is stored on the blockchain.

Transparent: GithubCrypt is a transparent platform as all the data is stored on the blockchain.

No Middleman: GithubCrypt is a platform where there is no middleman and the user can directly interact with the project owner.

No Fees: GithubCrypt is a platform where there are no fees and the user can directly interact with the project owner.

# How to Run

1.           Clone the repository

2.           Change directory to client
    `$ cd smart_contract`
3.           Install dependencies

    `$ npm install`

4.       Install Metamask and Signin to alchemy.

5.       Create new App under Sepolia network.

6.       Copy its key and paste it in hardhat.config.js file under url.

7.       Get your metamask account private key and paste it in hardhat.config.js file under account.

8.       Deploy the contract

    `$ npx hardhat run scripts/deploy.js --network Sepolia`

9.       Copy the contract address and paste it in client/utils under constants.js file.

10.     Copy account key generated by deploying contract and paste it in client/utils under constants.js file.

11.     under smart_contact/artifacts/contracts copy data of Github.json file and paste it under client/utils into Github.json file.

12.     Change directory to client
    `$ cd client`
13.     Install dependencies

    `$ npm install`

14.     Run the client

    `$ npm run dev`
