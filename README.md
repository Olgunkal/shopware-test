# shopware-test

## First start with this project
### Requiremented tools for this project
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Visual Studio Code](https://code.visualstudio.com/download)

### Starting
1. Start docker and wait it is running
2. Start Visual Studio Code and open the folder where you clone the repo
3. Open a Terminal in Visual Studio Code and type ```docker-compose up -d ```
4. You will see that docker is pulling the container "dockware/dev". 
5. Wait for docker finished creating the container image
6. Go back to Visual Studio Code and install the Extensions [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) and [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) (maybe you will need to restart VSCode)
7. On the left Menübar ther will be a new icon it looks like a monitor.
8. Klick on that and select on the top at "REMOTE EXPLORER" the folowwing selection -> 'Dev Containers'
9. And then klick at "shopware-test" on the icon with the plus called "Attach in new Window"
10. A new window of Visual studio will be open 
11. To be sure that you attached in the container, you can look on bottom-left side, there will be a blue box with following text `">< Container dockware/dev:latest (shopware)"`


#### Now you are in the container and can start to develop! 
### Have fun!

