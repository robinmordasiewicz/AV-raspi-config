# RASPI-CONFIG for ATEM mini
### Scene Switching and A/V Automation

Automate the deployment of a raspberry PI4 running software configured to automate the ATEM mini switching, video playout, music and sound effects.  

## Prerequisites

#### Required

* Raspberry Pi4 with 4GB or 8GB of RAM
* [32-bit Raspian Lite](https://downloads.raspberrypi.org/raspios_lite_armhf_latest) [installed](https://www.raspberrypi.org/documentation/installation/installing-images/README.md){:target="_blank" rel="noopener"}.
  * Desktop and Full versions work, but Raspian LITE is preferred. ( haven't tested 64 bit yet )
* Raspberry Pi4 connected to your network with access to the internet

#### Optional

* HDMI port connected from the PI4 to HDMI input #4 on the ATEM mini
* 3.5mm stereo cable connected from the PI4 to Aux input #1 on the ATEM mini

## Installing

Run the following three commands on your raspberry PI4 and follow prompts.
 
```console

sudo apt-get -y install ansible

wget -q --show-progress https://raw.githubusercontent.com/robinmordasiewicz/raspi-config/master/playbook.yml

ansible-playbook playbook.yml


```

![](https://github.com/robinmordasiewicz/raspi-config/raw/master/install_terminal.gif)

## Contents

* [Bitfocus.io Companion](https://bitfocus.io/) - [Companion Facebook group](https://www.facebook.com/groups/2047850215433318/)
* omxplayer
* omxd
* imagemagick
* mpd
* mpc

## Authors

**Robin Mordasiewicz** - *Initial work*

See also the list of [contributors](https://github.com/robinmordasiewicz/raspi-config/contributors) who participated in this project.

## License

This project requires no license.

## Acknowledgments

* Hat tip to anyone whose code was used
* Adam Schumacher

https://robinmordasiewicz.github.io/raspi-config/

<script src="https://utteranc.es/client.js" repo="robinmordasiewicz/raspi-config" issue-term="pathname" theme="github-light" crossorigin="anonymous" async></script>
