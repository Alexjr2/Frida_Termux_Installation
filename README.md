> [!NOTE]
> Only For Termux User (Android) support arm, arm64, x86 and x86_64

## Installing Python
```bash
apt update && apt upgrade && apt install build-essential python python-pip git wget binutils openssl && pip install -U setuptools wheel && pip cache purge
```
## Installing frida
```
cd $TMPDIR && wget https://raw.githubusercontent.com/Alexjr2/Frida_Termux_Installation/refs/heads/main/frida-python.sh && bash frida-python.sh && cd && pip install frida-tools==13.6.1 && pip cache purge
```
## Installing dependencies
```
pip install colorama prompt_toolkit pygments
```
# Credits
- [frida](https://github.com/frida/frida) : Official Frida Repository
- [frida-python](https://github.com/frida/frida-python.git) : For frida-python installation and script
