# Video switching configuration files<br>
This is an example repo for an atem mini and bitfocus.io companion config for Streamdeck XL<br>
I barely know what I'm doing, but watch out here I come.<br>
<br>
For this to work, you require a Rasberry PI4B with raspian OS installed.<br>
Once your Raspberry PI is running, log into it and run the following commands.<br>
<br>
sudo apt-get -y install ansible wget<br>
wget -N https://github.com/robinhoodis/video_switcher/raw/master/playbook.yml<br>
ansible-playbook playbook.yml<br>
<br>
