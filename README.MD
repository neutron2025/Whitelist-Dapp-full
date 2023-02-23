mkdir Whitelist-Dapp

cd Whitelist-Dapp

mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox

npx hardhat 选择 Create a Javascript Project

添加 Whitelist.sol
添加 deploy.js
添加  .env 文件  
'''
QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"

PRIVATE_KEY="add-the-private-key-here"
'''
运行npm install dotenv

配置 hardhat.config.js
编译 npx hardhat compile
部署 npx hardhat run scripts/deploy.js --network goerli

回到Whitelist-Dapp 目录下
cd Whitelist-Dapp
创建前端
npx create-next-app@latest  选择 Javascript 
运行APP
cd my-app
npm run dev

网站搭好了- 开始修改连接前后端
npm install web3modal
npm install ethers@5
修改 Home.modules.css
修改page目录下的  index.js 文件

在my-app目录下 创建新文件夹 constants 里面创建文件 index.js

运行 npm run dev

