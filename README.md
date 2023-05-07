# Info
Celestia: Create a UI for submitting PayForBlob transactions


## Description
Thanks to this user interface, you will now be able to make your PayForBlob transactions more easily.


# Web demo
- http://194.163.172.37:3069/



## Dependencies

- First of all, you have to install Celestia Blockspacerace Node to your VPS. I set up a Light Node for this project thanks to [Conqueror](https://github.com/DasRasyo/Celestia-Light-Node-blockspace-race) and [NakoTurk's](https://github.com/okannako/celestia-blockspacerace) guides

### Install NodeJs modules

```
curl http://deb.nodesource.com/setup_lts.x | sudo bash -
sudo apt install git nodejs -y
```

### Setup
```
git clone https://github.com/ezraike/Celestia_PFB_UI.git
```
```
cd Celestia_PFB_UI
```
### Install module dependencies

```
npm install
```

## Run the server
```
npm start
```



##  Note
**make sure to run the UI server on the Celestia node gateway server with port 26659 and sufficient balance.**
