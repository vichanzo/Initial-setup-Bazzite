In this guide I am instaling Kali linux in Distrobox.  I found this useful guide at https://tresnax.com/blog/setup-kalilinux-distrobox/

# Set up Distrobox (if you have bazzite or another atomic distribution)
Using Distrobox using flatpak (Bazaar)

# Create a new box

```
distrobox create Kali docker.io/kalilinux/kali-rolling:latest
```

# Install Kali Tools
```
apt update && apt -y install kali-linux-headless
apt update && apt -y install kali-linux-large
```

```
sudo apt update && sudo apt install -y
```

https://www.kali.org/docs/troubleshooting/common-minimum-setup/
