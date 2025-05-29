# Discord-auto-with-AI From Airdrop Sambil Rebahan

# Fitur
- auto chat with AI
- Untuk Push level Dscord

**buat screen**
```
sudo apt update && sudo apt install screen
```
```
screen -S AI
```
**install AI lokal**
```
curl -fsSL https://ollama.com/install.sh | sh
```
```
ollama serve
```
```
ollama pull gemma:2b
```
**Keluar screen AI**
- crtl a+d
**buat screen discord**
```
screen -S discord
```
**Install Script**
```
git clone https://github.com/yonarebahan/Discord-auto-with-AI.git
cd Discord-auto-with-AI
```
Buat environtment
```
python3 -m venv dc
source dc/bin/activate
```
**install bahan**
```
pip3 install -r requirements.txt
```
**buka script**
```
nano bot.py
```
= isi TOKEN DC & channel ID target

= klik ctrl + x -> klik y -> klik enter (untuk keluar)
**Mainkan script**
```
python3 bot.py
```
## Fungsi tambahan
masuk screen AI
```
screen -r AI
```
masuk screen discord
```
screen -r discord
```
## DISCLAIMER
Gunakan dengan bijak, semua risiko dan tanggung jawab ada di tangan pengguna.

## Support by MyBrain, Chat GPT AI & Join Channel Airdrop Sambil Rebahan : https://t.me/kingfeeder

## ☕ Donate for Coffee

**EVM Address**  
`0xE70Cfda5FE920d0439752D1Cc8081Ef58479aC85`

**SOL Address**  
`J6qmkXTnngtWeK1JU5kHjfuRrnwgtiLN5QwsRdPjj27C`

---
© 2025 Airdrop Sambil Rebahan. All rights reserved.
