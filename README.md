# Organ-Harbour
Organ donation and transplantation using blockchain

# Introduction
Organ donation and transplantation is one of the great advances in modern medicine. It offers a second chance at life to people of all ages who have life-threatening diseases or injuries to their vital organs. But due to scarcity, unfortunately, not everyone who needs an organ transplant gets one in time. The lack of transparency in the existing system among donors, recipients, hospitals and other higher authorities, often leads to the illegal sale and purchase of organs. The more needy patient might not get the organ while someone who is behind in the waiting list might get an organ before, if he/she is able to pay the higher amount. As per the current system the entire data is stored at a single point, thus shifting to a distributed system will introduce more security.
In response to this pressing challenge, we introduce Organ Harbour, an innovative dApp platform connecting organ donor and acceptor via public ethereum blockchain that gives a decentralized, transparent and secure system for organ donation and transplantation. Central to our approach is the utilization of smart contracts, meticulously designed to govern the conditions and actions pertinent to hospitals, patients, and donors. These smart contracts enable hospitals to efficiently match donors with compatible recipients, streamlining the transplantation process and ensuring timely access to life-saving treatments. The secure deployment of smart contracts onto the Ethereum blockchain, facilitated by migrations.sol, underscores our commitment to transparency and reliability. 
Through this project, we explore how blockchain technology enables us to streamline the organ donation process, authenticate donors and patients, facilitate efficient matching, and ensure transparency throughout the transplantation journey. From donor pledges and registrations to the deployment of smart contracts on the Ethereum blockchain, our project showcases the transformative potential of blockchain in revolutionizing healthcare practices for the betterment of society. 

# Problem Statement
An organ donation and transplantation application is essential to address the growing waiting list and efficiently matching donors with recipients. The existing system relies on traditional methods like manual record-keeping, and third-party mediation leading to delays, errors, and a lack of transparency using centralized databases. Our approach uses Ethereum-blockchain-based technology that not only addresses the limitations of traditional methods but also ensures three key features- privacy, security, and confidentiality for organ donation. By utilizing smart contracts between the donors and patients we ensure security and confidentiality features. Distributed ledger in blockchain, ensures a secure and immutable record of organ donation transactions. By doing so, we aim to save more lives by improving the accuracy, and speed of organ matching, and ultimately increasing the number of successful organ transplantations.

# Built With
FrontEnd - HTML, CSS, Javascript
BackEnd - node.js, Solidity

# Prerequisites
These software needs to be installed on your machine to run the project.

## Node.js
### Windows:
1. Visit the NodeJS web page at https://nodejs.org/en/
2. Download and install the LTS version.
3. Download the installer and run it. This will install both NodeJS and NPM (Node Package Manager).
   
Note: If you're on Windows 11, make sure to have latest LTS version of nodejs installed, or else you'll probably run into some issues.

### Arch Linux:
Open a terminal and type the following command.
`sudo pacman -S nodejs npm`

### Ubuntu:
Open a terminal and type these commands in order.
` sudo apt update
  sudo apt install nodejs
  sudo apt install npm`

### RedHat, Fedora, CentOS:
`sudo yum update
curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -`

### MacOS:
Download the LTS application binary for MacOS.
When the file finishes downloading, locate it in Finder and double-click on it.
Go through the entire installation process.

## Truffle
Open the command prompt or terminal and execute the following command.
`npm install -g truffle`

## Ganache
Visit the Ganache webpage at http://trufflesuite.com/ganache/ Download the platform binary for your OS and install it.

## Git
### Arch Linux
`sudo pacman -S git`

### Ubuntu
`sudo apt update
sudo apt install git`

### Windows
Install gitbash from https://gitforwindows.org/

# Installation
## Download
1. Open gitbash or terminal.
2. Traverse into the app folder.
`cd organ-donation-platform/app`
3. Install npm dependencies.
`npm install`

## Connect Ganache
After npm dependencies are installed, follow these instructions:

1. Open ganache.
2. Click on "New Workspace".
3. Select "Add Project".
4. Navigate to the folder where you downloaded the project, specifically the "organ-donation-platform" folder.
5. Add the truffle-config.js file located in the "organ-donation-platform" folder.
6. Confirm by pressing "Save Workspace" on the top-right corner.
7. Navigate to the "Contracts" tab.
8. You will notice the DonorContract is not deployed.
   
## Deploy Contract
Once the npm dependencies have finished downloading, return to your Git Bash or Terminal window. Ensure that the download process has completed, then type in the following commands to deploy the contract:
`truffle compile && truffle migrate`

After running the above command, check the contracts on Ganache, the DonorContract will now be deployed. If not, then there will be some error with the downloading.

## Run the server
Now, you can run the server by:
`npm run dev`

Open a browser and go to http://localhost:8080/

# Methodology
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/flowchart.png"></center></a>

# Results
Thus, our project utilizes blockchain technology to optimize organ donation processes, reducing waiting times for patients. Through Ethereum blockchain on Truffle Ganache, the platform ensures transparency, security and ease of access for both donors and patients. Verification by hospitals enhances credibility, while the immutable ledger mitigates illegal activities like black marketing and trafficking of organs. Overall, the proposed solution offers hope by prioritizing data privacy, transparency and fairness in organ donation and transplantation, ultimately saving lives and improving healthcare outcomes.
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/homepage.png"></center></a>
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/donor.png"></center></a>
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/dashboard.png"></center></a>
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/verification.png"></center></a>
<a target="blank"><center><img src="https://github.com/Nikki-ta/Organ-Harbour/blob/main/organ-donation-platform/images/transplant.png"></center></a>

## Team Members
* #### NIKITA BANSAL - 21103069(B3)
* #### SAMYAK JAIN  - 21103075(B3)
* #### RIBHA NISHAL  - 21103098(B4)

## LICENSE
This project is licensed under the MIT License - see the <a href="https://github.com/Nikki-ta/Organ-Harbour/blob/main/LICENSE.md" target="blank">LICENSE.MD</a> files for details.
