**A discord welcomer bot developed in discord.js v13 that is very simple to use and comes with code and deployment instructions!**

**Aliter**

### Step 1: Install the Dependencies:
Linux 
```sh
apt install nodejs npm -y
curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
chmod 777 nodesource_setup.sh
./nodesource_setup.sh
apt install nodejs -y
npm install

```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.0.0/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
<b>
  

### Step 3 : Replace the Token in [config.json](https://github.com/ZeroDiscord/Welcomer/blob/master/config.json) <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Welcomer" index.js --watch
```


#  Core Dependencies 
- Discord.js v13.x
- KeyV - Customisable database ( sqlite by default can be connected to any type of database )
- Canvas - For crafting the welcome message 
- Canvas - Constuctor - Making my work easy :P
- Weird-to-normal-chars - To Adjust the fonts present around discord to our available fonts in image.
## Need help? Join the [Support Server](https://discord.gg/ARu4hr6hJw)

