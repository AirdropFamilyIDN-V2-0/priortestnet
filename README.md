# Priortestnet Brutal Automation
![Screenshot 2025-05-03 114849](https://github.com/user-attachments/assets/1dd1f880-c1f5-4a2f-b098-bbe1aeb02886) 

# Note Wajib 
- Web3 V6.20.1
- python v3.10
# Cara uninstall + install web3
```
pip uninstall web3
```
```
pip install web3==6.20.1
```

## Features 
- Generator Wallet
- Create Akun Prior
- Share Faucet Base Sepolia to list Address
- Claim Faucet Prior Testnet from Multi Chain Web3
- Swap Prior Automation

## Tutorial Run Awal 
- Run Generator Wallet Dulu! Auto Save PKEVM + Pharse 12 kata & AddressEVM
- Share Faucet Base Sepolia ke Tuyulan dengan pk akun utama di save d file utapapkkey.txt
- Run Priortestnet.py ( Opsional )
- Run Claim Faucet ( faucet.py ) Wajib ada fee Base sepolia
- Run swap.py Jika claim Faucet sdh selesai

## Downloads Script ! 

```
git clone https://github.com/AirdropFamilyIDN-V2-0/priortestnet.git
```
```
cd priortestnet
```
```
pip install -r requirements.txt
```
# Ini Buat Generator Wallet 
```
python wallet.py
```
# Jika sudah selesai lanjut 
```
python sharefaucet.py
```
```
python faucet.py
```
ini otomatis run 24/7
Pastikan privatekey utama yg ada base sepolia ada d file utapapkkey.txt jika sudah 

## Open New CMD / terminal 
```
python priortestnet.py
```
# buat cek saldo akun"
```
python swap.py
````
ini otomatis run 24/7
