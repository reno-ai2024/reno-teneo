# Teneo Bot

## Description
Teneo bot is a simple tool designed to automate the node interaction.

## Features
- **Automated node interaction**

## Prerequisites
- [Node.js](https://nodejs.org/) (version 12 or higher)

## Installation

1. Clone the repository to your local machine:
   ```bash
	git clone https://github.com/recitativonika/teneo-bot.git
   ```
2. Navigate to the project directory:
	```bash
	cd teneo-bot
	```
3. Install the necessary dependencies:
	```bash
	npm install
	```

## Usage

1. Set the `account.js`, `config.js` and `proxy.js` before running the script. Below how to setup this fie.
2. Configuration:
	Modify the `account.js` file to set your account parameters
	```
	module.exports = [
	{
		email: "account1@example.com",
		password: "password1"
	},
	{
		email: "account2@example.com",
		password: "password2"
	},
	// Add more accounts as needed
	];
	```
	Modify the `config.js` file if you want to use proxy or not, default is false (not use proxy)
	```
	const useProxy = false; // (set true if want to use proxy, false if not)

	module.exports = {
	useProxy
	};
	```
	Modify and set the `proxy.js` file if you want to use proxy
	```
	module.exports = [
	{
		host: "proxy1.example.com",
		port: 8080,
		username: "proxyuser1",  // Include these if your proxy requires authentication, delete this part if you dont need auth in your proxy
		password: "proxypass1" // Include these if your proxy requires authentication, delete this part if you dont need auth in your proxy
	},
	{
		host: "proxy2.example.com",
		port: 8080,
		username: "proxyuser2",
		password: "proxypass2"
	},
	// Add more proxies as needed
	];
	```
3. Run the script:
	```bash
	node index-old.js
	```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.

Extension link : https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm

My reff code if you want to use :) : 
```bash
03WkM
```
