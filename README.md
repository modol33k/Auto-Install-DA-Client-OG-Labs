# DA-Client-0G-Labs by Modol
This is my documentation of my node project.

# Auto Install DA Client OG Labs
Jalankan perintah berikut di Linux anda dan input Private Key diawal.

```bash
bash <(curl -s https://gist.githubusercontent.com/modol33k/152ed7d1dd25083377887b0cc17426be/raw/c47a8f367bfc5e387b4c1ed08eea3f91453b2570/install_da_client.sh

```
# Cek Logs
```
docker logs 0g-da-client -fn 100

```
# Stop dan Hapus node
```
docker stop 0g-da-client
docker rm 0g-da-client
rm -rf $HOME/0g-da-client
```
