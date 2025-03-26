# Monadscore Auto Bot

## Description
Monadscore Auto Bot is an automated tool for generating Ethereum wallets and registering them on the Monadscore platform using proxy support.

## Prerequisites
- Node.js (version 16 or higher)
- npm (Node Package Manager)

## Installation
1. Clone the repository
```bash
git clone https://github.com/airdropinsiders/Monadscore-Auto-Bot.git
cd Monadscore-Auto-Bot
```

2. Install dependencies
```bash
npm install
```

## Configuration
1. Create a `proxies.txt` file in the project root with proxy list:
```
http://username:password@host:port
socks5://username:password@host:port
```

2. Create a `code.txt` file with your referral code:
```
YOUR REF CODE
```

## Usage
```bash
npm start
```

When prompted, enter the number of wallets to generate.

## Requirements
- `proxies.txt`: List of proxies
- `code.txt`: Your referral code
- Must have content in both files to run successfully

## Disclaimer
- Use at your own risk
- Comply with Monadscore's terms of service
- Proxies are recommended to avoid IP-based restrictions

## License
MIT License