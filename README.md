#  This project is made under 

![Screenshot from 2023-12-22 14-02-07](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/73186902-2b66-4376-b36d-3714241fd3ac)



# Data Dao Club

Trasure Dao Club allows you to manage investment clubs, and to spread access to participate in investment funds to anyone, decentralized, agile, and without bureaucracy.Implementing a comprehensive on-chain governance system allows DataDAO members to create and vote on proposals, covering aspects such as member management, dataset storage and distribution, and token distribution. This ensures a democratic and transparent decision-making process within the DAO.

<br>

  
## 📋 Table of Contents

- [Introduction](#introduction)
- [What It Does ?](#what-it-does)
- [Installation](#-setting-up-the-project-locally)
- [Challenges we ran into](#-challenges-we-ran-into)
- [Technologies we used](#%EF%B8%8Ftechnologies-we-used)
- [Video Demo](#-video-demo)
- [Contributing](#-contributing)

</div>
<a href="#top">Back to top</a>


 
## 💡Introduction

In the ever-evolving landscape of decentralized finance, TReasure Dao Club emerges as a groundbreaking platform, offering a seamless solution for managing investment clubs and democratizing access to investment funds. This innovative platform is designed to be decentralized, agile, and free from bureaucratic hurdles, providing users with unparalleled flexibility in their investment strategies.

DataDAO members can create and vote on proposals, covering aspects such as member management, dataset storage and distribution, and token distribution. This ensures a democratic and transparent decision-making process within the DAO.
One of the standout features of DAO CLUB is its commitment to decentralization. Through the use of blockchain technology, the platform ensures that investment club data is transparent, secure, and immutable. This decentralized approach eliminates the need for intermediaries, putting control directly into the hands of the users.'


## Smart Contract deployed on Sepolia testnet
- Smart contract Address - 0xcBbAeBdC163e0Cd487903c85213b7F5629a03F8A
- https://sepolia.etherscan.io/address/0xcbbaebdc163e0cd487903c85213b7f5629a03f8a

  ![Screenshot from 2023-12-22 14-29-47](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/40b254d6-83d7-4555-ad8c-5a0551e339ec)

# What it does

## Create Data Dao Investment Clubs

- Users can easily create investment clubs by providing a club name.
- The club becomes associated with the account of the user who creates it (owner).
![Screenshot from 2023-12-21 04-37-17](https://github.com/Vikash-8090-Yadav/Dao-Club/assets/85225156/f799ed27-e9dd-4d82-82b1-fa7ac920b316)


## Join or Leave and Contribute to the Club 
- Data Dao Members can contribute to the common fund (pool) by depositing ICP coins.
- Contributions can be utilized in proposals.
  
![gallery](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/75f15263-0113-4353-aaee-acb073b98791)



Transaction after contribution 
![image](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/e2caf135-037d-4f77-9634-6d846c2c4efe)


## Create and Vote on Proposals

- Members who contribute funds to the club pool can create proposals.
- Proposals include a description, amount (not exceeding the pool amount), and recipient for potential investments.
- All members can approve or reject proposals with one vote per member on each proposal.
  
![gallery (1)](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/530f1ebf-04c2-4215-a07a-7117c867ea52)



## Execute and Close proposal

- Proposal owners, with greater approval than rejection, can execute proposals.
- Can't execute in voting periods which last for 5 min after creation. 
- This action transfers the proposal amount to the specified recipient.
- Owners can also close proposals for various reasons, such as cancellation or to avoid sending funds.
- ![gallery (2)](https://github.com/Vikash-8090-Yadav/TreasureGrant/assets/85225156/9c3f6bbc-8e2f-4b7f-b922-f08c13e77737)





<be>

## What you can currently do in this version is:

- Create investment clubs: Just define a name and the club will be associated with the account of the user who creates it (owner).
- Join or leave clubs: Anyone with an aeternity blockchain account can join the available investment clubs, as well as leave one, with just a couple of clicks.
- Contribute to the club: Any member of a club can contribute to the common fund (pool), depositing AE coins that can be used in proposals.
- Create and Vote on Proposals: Any member who has contributed funds to the club pool can create proposals, giving a description, amount (not to exceed the pool amount), and recipient, with a view to investing in any business/person in a project. Also, all members can approve or reject the proposal (only one vote per member is allowed on each proposal).
- Run Proposals: A proposal owner can execute a proposal (if approval is greater than rejection), which will cause the proposal amount to be sent to the specified recipient. The owner can also close a proposal, in case of not continuing with it, either as a cancellation, publication error or to avoid sending funds.


## 💥 Challenges we ran into
- Understanding Dao is very critical and took me more than 4 hours to get the best idea to build
- I faced lots of issue in smart contract as I have to manage all the funds, proposal, voting periods and many more things but at the end I enjoyed a lot during the building time.I preferred that all It was 100% web without a backend other than the smart contract, so any other developer or person can test it in any environment.

    
<br>

<a href = "#top">Back to top</a>



### 	▶️ Experience the Live Site by Clicking the Link Below
<br>
<div align="center">
  <table>
    <tr>
      <th>Deployed On</th>
      <th>URL</th>
    </tr>
    <tr>
      <td>Vercel</td>
      <td>
        https://treasure-grant.vercel.app/
      </td>
    </tr>
    </tr>
    </table>
</div>
<br><br>

## 🚀 Setting up the project locally

To run the Edu.dev locally, follow these steps:
1. Clone the repository:
 ```bash
 git clone  https://github.com/Vikash-8090-Yadav/TreasureGrant.git
 ```
 2. Navigate to the project directory:
```bash
cd  TreasureGrant
```
3. Node Re-versioning

```bash
export NODE_OPTIONS=--openssl-legacy-provider
```

4. Install the dependencies:
```bash
npm install --legacy-peer-deps
```

6. Access the dApp:
```bash
npm start
```
Open your web browser and visit the URL SHOWING IN UR TERMINAL to interact with the Trasure  DAO CLUB

<br>

## 🛠️Technologies we used


[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Developed in Motoko](https://img.shields.io/badge/Developed_in-Motoko-2196F3?logo=dfinity)](https://sdk.dfinity.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|



<be>


## 🎥 Video Demo



## 🤝 Contributing

Contributions to Dao Club are always welcome! If you'd like to contribute, please follow these guidelines:
Fork the repository.

Create a new branch for your feature or bug fix:

```
git checkout -b feature/your-feature-name
```
Commit your changes:

```
git commit -m 'Add some feature'
```
Push the branch:

```
git push origin feature/your-feature-name
```
Open a pull request.

We appreciate your contributions and thank you for helping us improve Algo-Media!

<br >
</div>

## LICENSE

```
MIT
```

## Project Contributor (Member)

<table>
<tr>
<td align="center"><a href="https://github.com/Vikash-8090-Yadav"><img src="https://avatars.githubusercontent.com/u/85225156?s=400&u=3363e9db42792ae40a18b3119c745930bb85cf47&v=4" width=150px height=150px /></a></br> <h4 style="color:red;">Vikash Kumar Yadav</h4>
<a href="https://www.linkedin.com/in/vikash-kumar-yadav-8090/"><img src="https://mpng.subpng.com/20180324/vhe/kisspng-linkedin-computer-icons-logo-social-networking-ser-facebook-5ab6ebfe5f5397.2333748215219374063905.jpg" width="32px" height="32px"></a>
   </td>
  
   
</div>
<a href="#top">Back to top ⬆️</a>

