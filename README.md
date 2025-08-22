# Pisowifi DDOS

<div align="center">
<img src="https://github.com/xiv3r/pisowifi-ddos/blob/main/image/proof.png">
</div>

# Requirements
- [Termux](https://github.com/termux/termux-app/releases)

# Manual Install
<details><summary> Expand
</summary>
  
```
pkg update && pkg upgrade -y
```
```
pkg install git python -y
```
```
git clone https://github.com/xiv3r/pisowifi-ddos.git
```
```
cd pisowifi-ddos
```
```
chmod 755 ddos.py
```
```
python ddos.py
```
</details>

# Auto Install
Termux
```
pkg update && pkg upgrade -y && pkg install git python -y && git clone https://github.com/xiv3r/pisowifi-ddos.git && chmod 755 pisowifi-ddos/*.py && cd pisowifi-ddos && ls
```

<details><summary> Kali
</summary>
  
```
sudo update && sudo apt upgrade -y && sudo apt install git python3 -y && git clone https://github.com/xiv3r/pisowifi-ddos.git && chmod 755 pisowifi-ddos/ddos.py && cd pisowifi-ddos && ls
```
</details>

# Run
```
cd pisowifi-ddos
```
```
python ddos.py -s 10.0.0.1 -p 80 -t 3500
```

<details><summary> Background mode
</summary>

```
python ddos.py -s 10.0.0.1 -p 80 -t 3500 > /dev/null 2>&1 &
```
</details>

<details><summary> kill the process
</summary>
  
```
pkill -f python
```
</details>

# Screenshot

<div align="center">
<img src="https://github.com/xiv3r/pisowifi-ddos/blob/main/image/ddos.png">
</div>

## ⚠️ Disclaimers
`"This tool is intended solely for ethical cybersecurity purposes, such as penetration testing, vulnerability assessments, and authorized research. Unauthorized use to disrupt networks, services, or systems is illegal and violates cybersecurity laws. Misuse may result in severe legal penalties, including fines and imprisonment. Always obtain explicit permission before testing any system. By using this tool, you agree to comply with all applicable laws and assume full responsibility for your actions."`
