# Super App React Native
## Overview
The **Super App React Native** repository is a monorepo setup that encompasses multiple applications designed to work together seamlessly. This project utilizes Yarn workspaces to manage dependencies and scripts for both a host application and mini applications. It provides a streamlined development process for building and running React Native applications.

### Features

- **Monorepo Structure**: Easily manage multiple applications and shared components in a single repository.

- **Yarn Workspaces**: Simplifies dependency management and speeds up installations.

- **Concurrent Execution**: Run multiple scripts simultaneously for an efficient development workflow.

- **Cross-Platform**: Supports both iOS and Android platforms.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (Recommended version: LTS)
- [Yarn](https://yarnpkg.com/) (Install via npm: `npm install --global yarn`)

### Installation

1. Clone the repository:

   ```bash
git clone https://github.com/MangalBeta/super-app-react-native.git

Navigate into the project directory:

cd super-app-react-native
Install dependencies:

1. yarn install
Bootstrap the workspaces:
2. yarn bootstrap

Start the Development Server
To start the development server for all applications:
3. yarn start

Start Host App: yarn start:host-app
Start Mini App: yarn start:mini-app


Run Host App on iOS:
yarn run:host-app:ios


Run Host App on Android:
yarn run:host-app:android




Run Mini App on iOS:
yarn run:mini-app:ios

Run Mini App on Android:
yarn run:mini-app:android



Clean Up:
yarn clean
Removes all node_modules directories throughout the project to free up disk space.

Usage
After bootstrapping the project, you can start any of the applications using the provided scripts. For example, to start the host application, run:
yarn start => It will run the both server 


yarn start:host-app  => It will run the only host-app server 
yarn start:mini-app  => It will run the only mini-app server 

