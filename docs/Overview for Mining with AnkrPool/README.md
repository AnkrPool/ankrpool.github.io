---
sort: 1
---
# I. Overview for Farming with AnkrPool

**Operating systems:** Windows/Linux/MacOS；

**Farming software:** AnkrPlot

 

**Steps to mine****：

a. Install Chia Blockchain and create your private key for your Chia wallet.

b. Install Chia-signer and enter your created private key. 

c. Add a plot

d. Bind data.

e. Install Chia-Plot to access AnkrPool.

 

# II. Install Chia Blockchain and create your private key

\1.   Visit Chia website (https://www.chia.net/) to install Chia Blockchain.      

![image](https://user-images.githubusercontent.com/86063945/125550907-ca32a74b-dbb2-4851-813e-a9ec6129f5ed.png)

Or you can also install it on github: https://github.com/Chia-Network/chia-blockchain/wiki/INSTALL#Windows

 ![image](https://user-images.githubusercontent.com/86063945/125550937-8b98d2f8-0536-4276-8ce8-298809e959f8.png)

\2.   Once downloaded, open it to set your preferred language, then create a new private key. 

 ![image](https://user-images.githubusercontent.com/86063945/125550970-ca823f32-fbb7-43f0-97c4-964aedc647cd.png)

\3.   The 24 words generated are your seed phrase, which you will need to recover your wallet. Please keep them safe!  

![image](https://user-images.githubusercontent.com/86063945/125550995-da23cc7b-b658-4e07-afe0-006e140b047a.png)

# III. Install Chia-signer and enter your created private key

\1.   Navigate to Download＆Help, then install Chia-Signer.

 ![微信截图_20210624122752](https://user-images.githubusercontent.com/86063945/125550672-a3bc31d3-998f-46ea-9991-392168d76224.png)

\2.   Unzip the file and run the AnkrPool-chia-signer app that suits your operating system. 

 ![image](https://user-images.githubusercontent.com/86063945/125551031-6f5ab5a7-529b-4b6a-a510-a2c34b24a6c6.png)

And put in your secret 24 words with space in between each word, then press “Enter”. 

 ![image](https://user-images.githubusercontent.com/86063945/125551107-1a424c84-f382-41cd-9461-42d29851c972.png)

![image](https://user-images.githubusercontent.com/86063945/125551168-1ddf3a08-e9f3-4d1a-be22-68175ad31c76.png)

\3.   Check if the Fingerprint matches your private key. Then copy your signature for connecting to AnkrPool later.  

![image](https://user-images.githubusercontent.com/86063945/125551254-cd9f88e8-98fa-45ee-902b-4e16de46c4a6.png)

*Only your signature is needed to connect your device to AnkrPool. Your private key and seed phrase will not be accessed at any time. Also, Chia-Signer can be run to generate your signature even when you are offline. 

# IV. Add a plot

Log in Chia wallet and navigate to “Plots” to add a plot. 

 ![image](https://user-images.githubusercontent.com/86063945/125551303-bfab351e-3ba8-4ed3-9222-60ca9b818ae1.png)
![image](https://user-images.githubusercontent.com/86063945/125551322-4349cd1d-b879-468f-89ae-a4bf290297b7.png)
![image](https://user-images.githubusercontent.com/86063945/125551341-3f66d252-80a1-4d2f-bba1-f024962ffd27.png)

# V. Bind data

\1. Go to the “Configure” page, paste your signature in the “Binding Date” field, then click “Apply”. 

 ![image](https://user-images.githubusercontent.com/86063945/125551362-a933cecb-3531-4c62-8e8d-43761e177778.png)

\2. When binding is done, you will find your plotter ID below:

 ![image](https://user-images.githubusercontent.com/86063945/125551380-9baa0b33-9ded-48b0-9857-9b80d7e81915.png)

# VI. Install Chia-Miner to access the pool.

\1. Navigate to Download＆Help, then install Chia-Miner.

 ![image](https://user-images.githubusercontent.com/86063945/125551400-0e3ed69a-ca19-4bbe-b3e8-3611da9759bc.png)

\2. Find config.toml and open it with your notepad.

 ![image](https://user-images.githubusercontent.com/86063945/125551418-eb773f87-7fa4-4438-8f99-40e6fa425805.png)

  \3. Copy your account key as shown on the “Configure” page and paste it into the config.toml file. 

 ![image](https://user-images.githubusercontent.com/86063945/125551439-3f29afec-ed13-4250-b663-e6a362fdbc43.png)

![image](https://user-images.githubusercontent.com/86063945/125551469-653c6709-0076-468c-9985-f7b6ce66cdb2.png)

\4. Change the plots path to your preferred one, then save the file. 

 ![image](https://user-images.githubusercontent.com/86063945/125551481-c9b4d407-f567-4b28-9134-15358fbcebd7.png)

\5. Run the AnkrPool-chia-miner app that suits your operating system. 

 ![image](https://user-images.githubusercontent.com/86063945/125551505-76755633-3e5f-4803-ada0-cf0d721c04f4.png)

\6. You should able to see things running after you successfully ran the miner app. 

*Don’t close the miner app when you are mining. 

 ![image](https://user-images.githubusercontent.com/86063945/125551516-cfdde123-bb20-4c14-b6e2-026060205b19.png)

\7. You can see how your miner is doing by going to the “My Plots” page.

![359F60DE-1612-48C9-B740-3E67DDF5FA4C](https://user-images.githubusercontent.com/86063945/125558467-dee37f1f-eed9-4af6-afea-eda33aa56bc8.png)

