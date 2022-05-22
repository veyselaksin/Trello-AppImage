# Trello-AppImage
Since Trello does not have a desktop version in the Linux environment, I packaged the Trello application I developed with Electronjs as AppImage.

## Install
Download files from git repository and navigate to the file directory you downloaded.
To use the application, all you have to do is run the ./install script. Then the desktop application will be created and you can access it by typing Trello from the application menu.

```bash
git clone https://github.com/veyselaksin/Trello-AppImage.git
cd Trello-AppImage && sudo ./install.sh
```

## Uninstall
To uninstall the application, you need the ./install script again. To get to ./script you will need to go to /opt/Trello-1.0.0/. Then you have to run the ./install.sh file and choose option 2. After the process is complete, the application will be completely deleted from your operating system.

```bash
cd /opt/Trello-1.0.0 && sudo ./install.sh
```
