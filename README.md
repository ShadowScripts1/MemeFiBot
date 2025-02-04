Here's the updated README tailored for the MemeFi bot:

---

# MemeFi Bot

Auto Tap MemeFi Bot

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/shadowscripters)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ShadowScripts1)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ShadowScripts1)

# Table of Contents
- [MemeFi Bot](#memefi-bot)
- [Warning](#warning)
- [Features](#features)
- [Registration](#registration)
- [How to Use](#how-to-use)
  - [Command Line Options / Arguments](#command-line-options--arguments)
  - [About Proxies](#about-proxies)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [Viewing Reports](#viewing-reports)
- [Thank You](#thank-you)


# Warning

All risks are borne by the user.

# Features

- [x] God Mode (Single Tap to Defeat Boss)
- [x] Auto Refresh Token
- [x] Auto Use Booster Energy
- [x] Auto Use Booster Tap
- [x] Auto Switch Boss
- [x] Multi-Account Support
- [x] Proxy Support
- [x] Total Tap Count Report for All Accounts
- [x] Random User-Agent
- [x] Waiting time before starting the program

# Registration

Join the MemeFi bot here: [MemeFiBot](https://t.me/memefi_coin_bot/main?startapp=r_b984864181)

# How to Use

## Installation

1. Download Python 3.10 or newer.
2. Install required modules:
   ```bash
   pip install pytz aiohttp
   ```

3. Open the MemeFi bot on Telegram desktop (it will prompt you to open it on your phone).
4. Press `F12` to open Developer Tools and navigate to the "Application" tab.
5. In "Session Storage," find the key `__telegram_initParams`.
6. Copy the `tgWebAppData` value (e.g., `query_id=xxxxxxxxxxxx`). Make sure to copy the entire value.
7. Paste this data into a file named `query_id.txt` (each account on a new line).

## Command Line Options / Arguments

This bot supports several command-line arguments:

- `--data` / `-D`: Use a different filename for storing account data. Default filename is `data.txt`.
- `--proxy` / `-P`: Use a different filename for the proxy list. Default filename is `proxies.txt`.
- `--worker` / `-W`: Customize the number of threads. By default, the script uses half of your CPU cores. Example: `python bot.py --worker 5`.
- `--action` / `-A`: Directly enter a specific menu in the bot. Example: `python bot.py --action 5`.

## About Proxies

To use proxies, add them to the `proxies.txt` file in the following format:

For proxies with authentication:
```
protocol://user:password@hostname:port
```

For proxies without authentication:
```
protocol://hostname:port
```

## Windows

1. Ensure Python and Git are installed.
   - [Python](https://python.org)
   - [Git](https://git-scm.com)

2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/MemeFiBot
   ```

3. Enter the MemeFiBot directory:
   ```shell
   cd MemeFiBot
   ```

4. Add your account data in `query_id.txt`.

5. Run the bot:
   ```shell
   python bot.py
   ```

## Linux

1. Ensure Python and Git are installed:
   ```shell
   sudo apt install python3 python3-pip git
   ```

2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/MemeFiBot
   ```

3. Enter the MemeFiBot directory:
   ```shell
   cd MemeFiBot
   ```

4. Add your account data in `query_id.txt`.

5. Run the bot:
   ```shell
   python bot.py
   ```

## Termux

1. Ensure Python and Git are installed:
   ```shell
   pkg install python3 git
   ```

2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/MemeFiBot
   ```

3. Enter the MemeFiBot directory:
   ```shell
   cd MemeFiBot
   ```

4. Add your account data in `query_id.txt`.

5. Run the bot:
   ```shell
   python bot.py
   ```

# Viewing Reports

To view a report of the total tap count across all accounts, run:
   ```shell
   python report.py
   ```

# Error Table

| Error                 | Description                                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| failed get json error | This is because the server response is not in JSON format and may be in HTML. Check the server response in the `http.log` file       |
| failed get task list  | The server response is missing the expected data. Check the `http.log` file                                                          |
| cannot start game     | Similar to the above, this is likely due to a server error. Check the `http.log` file                                               |

## 💱 Support Me

If you found this tool useful, consider supporting me:

- EVM: `0x7BeE9994a631523e22A3aB83039c196bFc6BC513`
- SOLANA: `6mbFy6AojWo3J5ksa1SYHHyCWw5Bms4p9McKmaFkCsyW`

## Contact
For questions or support, please contact [Scripters Enclave chat](https://t.me/chatwithscripters)

# HAPPY HUNTING

--- 

