MetaMask developer documentation
This is the MetaMask developer documentation repository. The documentation site is hosted at docs.metamask.io, and it's built using Docusaurus, a static site generator purpose-built for technical documentation.

Build locally
Build the documentation site locally using the following steps.

Prerequisites
Node.js version 20.x
Git
Steps
Clone the repository.

git clone https://github.com/MetaMask/metamask-docs.git
cd metamask-docs
Note: If you don't have write access to this repository, you must fork the repository to your personal account and clone your forked repository instead. Add an upstream remote to be able to pull from and push to the original repository.

git clone https://github.com/<YOUR-USERNAME>/metamask-docs.git
cd metamask-docs
git remote add upstream https://github.com/MetaMask/metamask-docs.git
Install dependencies.

npm install
Start the development server.

npm start
Once the server starts, you can view the documentation at http://localhost:3003.

For more information on contributing to the documentation, see the full contribution guidelines.
