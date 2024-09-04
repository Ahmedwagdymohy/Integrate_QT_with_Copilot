# How to Add GitHub Copilot to QT creator
1. Install the required Dependancies
    ```bash
        apt-get install Node.js
        git clone https://github.com/github/copilot.vim.git `
        $HOME/vimfiles/pack/github/start/copilot.vim
    ```

2. In the same terminal write `vim` , Vim editor will pop-up 

3. write `:Copilot setup` it will ask you to authenticate your github copilot account in a browser window , Enter the code provided and Done :) 

4. Now open QT creator and go to `HELP` in the upper bar , press on `About Plugins`
   
5. Search for Copilot and then enable it & press OK
 
6. Go to `Edit` then prefrences search for copilot in the seach bar

7. Check Enable Copilot
      
8. For the Node.js path put the binary of Node it will be something like this:
 `C:\Users\study\AppData\Roaming\fnm\node-versions\v20.17.0\installation\node.exe`
 
9. for agentJs go to the place where the copilot.vim is installed take `language-server.js` path of the file and place it in QT , it will look like this :
`C:\Users\study\vimfiles\pack\github\start\copilot.vim\dist\language-server.js`