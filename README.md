# Supercon-2018

## Documention

https://docs.google.com/presentation/d/1lbi9_Ju4LXWuTECuNQzXC9t6qDDKVY6LRu5BnbmGQxI/edit?usp=sharing

## Web Portal:

https://www.digikey.com/en/iot-development-platform/

## Hardware

Part List: http://www.digikey.com/

# Drivers:

## Windows

Windows 10: https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip

Windows 7-8.1: https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip

## MacOS

Mac OSX: https://www.silabs.com/documents/public/software/Mac_OSX_VCP_Driver.zip

## Windows/MacOS:

https://developer.atmosphereiot.com/documents/downloads/atmosphereiotagent.html


## Debian Buster/Sid
```
sudo apt update
sudo apt install libgconf-2-4
sudo dpkg --ignore-depends=libgconf2-4 -i ~/Downloads/atmosphereiotagent_latest_amd64.deb
```
