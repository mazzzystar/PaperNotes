## My Ubuntu Notes

TLDR; Important notes related to Ubuntu

### [Login Loop Fix](https://askubuntu.com/questions/223501/ubuntu-gets-stuck-in-a-login-loop)
* Log in shell (Ctrl+Alt+[F1 to F6]) and type:
```
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt update
```
* Search for latest NVIDIA package and install it:
```
sudo apt-cache search nvidia-[0-9]+$
sudo apt install nvidia-[latest package number]
```
* If it suceeds, reboot:
```
sudo reboot
```

### Installing Tensorflow

