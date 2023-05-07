


## Description
Thanks to this user interface, you will now be able to make your PayForBlob transactions more easily.


# Web Page
- http://194.163.172.37:2222/




https://user-images.githubusercontent.com/102254553/236700138-07e99b88-ac14-4218-9b1b-c302f332c314.mp4







## Dependencies

- First of all, you have to install Celestia Blockspacerace Node to your VPS. I set up a Light Node for this project thanks to [Conqueror](https://github.com/DasRasyo/Celestia-Light-Node-blockspace-race) and [NakoTurk's](https://github.com/okannako/celestia-blockspacerace) guides


### Install NodeJs modules

```
curl http://deb.nodesource.com/setup_lts.x | sudo bash -
sudo apt install git nodejs -y
```

### Create A Screen
```
screen -S webserver
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
**Your server must run with port 26659 
