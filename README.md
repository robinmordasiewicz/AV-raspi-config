# Video Switching and A/V Automation

Automate the deployment of a raspberry PI4 running software configured to automate the ATEM mini switching, video playout, music and sound effects.  

## Prerequisites

#### Required

* Raspberry Pi4 with 4GB or 8GB of RAM
* Raspian, Raspian Lite, or Ubuntu installed
* Connected to the network with access to the internet

#### Optional

* HDMI port connected from the PI4 to HDMI input #4 on the ATEM mini
* 3.5mm stereo cable connected from the PI4 to Aux input #1 on the ATEM mini

## Installing

Run the following three commands on your raspberry PI4 and follow prompts.
 
```console

sudo apt-get -y install ansible wget
wget -N https://raw.githubusercontent.com/robinhoodis/video_switcher/master/playbook.yml
ansible-playbook playbook.yml  

```

## Contents

* (companion)[https://bitfocus.io/] - (Companion Facebook group)[https://www.facebook.com/groups/2047850215433318/]
* omxplayer
* omxd
* imagemagick
* mpd
* mpc

## Authors

* **Robin Mordasiewicz** - *Initial work*

See also the list of [contributors](https://github.com/robinhoodis/video_switcher/contributors) who participated in this project.

## License

This project requires no license.

## Acknowledgments

* Hat tip to anyone whose code was used
* Aaron Parecki
* John Barker
* Bill Church
* Adam Schumacher

<script src="https://utteranc.es/client.js" repo="robinhoodis/video_switcher" issue-term="pathname" theme="github-light" crossorigin="anonymous" async></script>
