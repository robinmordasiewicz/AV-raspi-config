## Video switching configuration files

This is an example repo for an atem mini and bitfocus.io companion config for Streamdeck XL

For this to work, you require a Rasberry PI4B with raspian OS installed.
Once your Raspberry PI is running, log into it and run the following commands.

```
sudo apt-get -y install ansible wget
wget -N https://raw.githubusercontent.com/robinhoodis/video_switcher/master/playbook.yml
ansible-playbook playbook.yml

```


<script src="https://utteranc.es/client.js"
        repo="[ENTER REPO HERE]"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
