## DAWN VALIDATOR AUTO REFERRAL BOT

Dawn Network Autoreferral script with autogenerated credentials and using proxies.
## Tools and Components Required
1. Dawn Validator Account | Download [Dawn Validator Extension](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp)
2. Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/pages/dashboard.html``, insert Referral code ``rj6ektjg`` and Register
3. Captcha Solvers API keys, you need to recharge credits. Register here: [2captcha.com](https://2captcha.com/) or [anti-captcha.com](https://getcaptchasolution.com)
4. Proxies (Must use proxies for avoid rate limit)
5. VPS or RDP (OPTIONAL)
6. Python version 3.13 Recommended

## Installation
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix:
```bash
apt install python3 python3-pip git -y
```
- For Termux:
```bash
pkg install python python-pip git -y
```
- Download script [Manually](https://github.com/Rambeboy/dawn-autoreff-bot/archive/refs/heads/main.zip) or use git:
```bash
git clone https://github.com/Rambeboy/dawn-autoreff-bot
```
### Requirements installation
- Make sure you already in bot folder:
```bash
cd dawn-autoreff-bot
```
#### Windows and Termux:
```bash
pip install -r requirements.txt
```
#### Unix:
```bash
pip3 install -r requirements.txt
```
## Run the Bot
- Replace the proxies ```proxies.txt``` to your own proxies, with the format example is like:
```bash
http://127.0.0.1:8080
http://user:pass@127.0.0.1:8080
```
>Only http proxies supported for now
- Windows and Termux:
```bash
python main.py
```
- Unix:
```bash
python3 main.py
```
- Then insert your referral code
## Notes
- Run this bot, use my referrer code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot.
- This bot is for educational purposes only.
