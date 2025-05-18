#IPFS
Commands (IPFS)
1.	Install the IPFS through WSL: wget https://dist.ipfs.tech/kubo/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz 
Or 
wget https://github.com/ipfs/kubo/releases/download/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz
2.	tar -xvzf kubo_v0.32.1_linux-amd64.tar.gz
3.	Kubo is a reference implementation of IPFS in Go: cd kubo 
4.	ls
5.	sudo bash install.sh
6.	ipfs –version
7.	ipfs init
8.	ipfs daemon
9.	On Browser: http://127.0.0.1:5001/webui
10.	To run ipfs daemon in background: ipfs daemon > ipfs.log 2>&1 &
11.	This is daemon ID: [1] 772
12.	Add file: echo "Hello, IPFS!" > hello.txt
13.	ipfs add hello.txt
14.	ipfs cat <CID>
15.	Add a directory: 
mkdir myfolder
echo "File 1 content" > myfolder/file1.txt
echo "File 2 content" > myfolder/file2.txt
16.	ipfs add -r myfolder
17.	ps aux | grep ipfs
18.	kill <PID>
19.	in Browser you can directly run this to see the IPFS: https://ipfs.io/ipfs/QmWd9cavD8UGZQcqYBVhZqs2Jure5W9cgxR7S6TC4StfZe

    ![WhatsApp Image 2025-04-09 at 22 34 30_33f03901](https://github.com/user-attachments/assets/9ef52b9d-b75f-4eef-9b0e-4e886e64cf26)
![WhatsApp Image 2025-04-09 at 22 37 42_2fe91985](https://github.com/user-attachments/assets/1f1f1157-18e9-49bd-ad64-a521f22a85b4)
![image](https://github.com/user-attachments/assets/28899af9-abc9-4e95-986b-beeff73f8413)
![WhatsApp Image 2025-04-09 at 22 35 03_6e97179d](https://github.com/user-attachments/assets/020d71e8-801b-4da0-b05c-d5834f6272d8)
![image](https://github.com/user-attachments/assets/6879deea-6eec-415c-a2ad-378b802b85b7)
![WhatsApp Image 2025-04-09 at 22 38 04_2adbbc1b](https://github.com/user-attachments/assets/583aaa18-2e6e-4773-88b5-f00e7020a5e3)
![WhatsApp Image 2025-04-09 at 22 38 40_7294414f](https://github.com/user-attachments/assets/64be043c-8b3f-4d9c-85b0-c303f3777e45)
![WhatsApp Image 2025-04-09 at 22 37 44_c05dbb9c](https://github.com/user-attachments/assets/d6ece3ae-ea46-4820-b443-af0adfc211f5)
