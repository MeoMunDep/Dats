📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux.)

> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> > > Help me with your referral [Link](https://t.me/DATSAPP_bot/datsapp?startapp=6713068747)

## 🚀 Getting Started

To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).


1. **Install Dependencies and Modules:**

   ```
   npm i user-agents cloudscraper axios colors p-limit https-proxy-agent socks-proxy-agent crypto ws
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "limit": 100,
  "countdown": 300,
  "country_time": "en-US",
  "speedTest": false,
  "limitFaucetAccount": 10,
  "delayEachAccount": [1, 81]
}
```

### 2. `datas.txt` 🗂️ - Get it from [here](https://t.me/KeoAirDropFreeNe/257/6879).

```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Fill EVM address, if you guys want to delete one address from a account just type ' ' (space) in that account's line

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt - wallet address
0x...
0x...
0x...
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd dats; node meomundep` or if you want to use faucet for multiple wallets: `cd dats; node meomundep_faucet`

🎇Enjoy!
