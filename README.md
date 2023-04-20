<h1>Tokens Account Manager</h1>
<p>This program keeps track of the user's tokens and transactions.</p>

<h2>Description</h2>
<p>The project's purpose is simple. It is to provide users the ability to mint and burn their tokens. This program also keeps track of the user's balance and total amount of tokens in their blockchain.</p>
<p>The project has the ability to mint tokens, which adds tokens into the user's account as they make transactions. It can also burn tokens, which subtracts the amount of tokens from the user's account. However, the program will be unable to subtract tokens if the token balance being subtracted from is lesser than the amount of tokens that is supposed to be subtracted from the account.</p>

<h2>Getting Started</h2>
<h3>Installing</h3>
1. You can download this program through github.

2. Download all of files that are contained within this github project. Make sure that it includes the Solidity file token.sol.

3. Open Remix, an Ethereum IDE that can run sol files and allows you to use the program. Link is provided below.(https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.19+commit.7dd6d404.js)

<h3>Executing Program</h3>
1. Open the token.sol file in Remix.

2. Change the solidity version in the first line to match the current version of Solidity

> pragma solidity 0.8.18; //<- change this

<h3>Help</h3>
<b>Program does not work</b>
<p>One of the possible solution is to change the pragma solidity line to the same version as your Solidity</p>

<b>Tokens were not added to the balance</b>
<p>You may have attempted to use an invalid value. Please input whole numbers without decimals.</p>


<h3>Authors</h3>

Maia Francine Endaya
(mfEndaya@mcm.edu.ph)

<h3>License</h3>
This project is licensed under the Maia Francine Endaya License - see the LICENSE.md file for details
