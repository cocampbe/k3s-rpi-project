# K3s rpi project

This is a repo to document how I built out my k3s cluster.

# Items

- 7 x rpi4 2GB
- 1 x enclosure
- 7 x rpi poe tophats
- 1 x poe switch
- 7 x ???GB microsd cards. 

# What I did

1. I pulled the oracle linux rpi4 images. I've used Red Hat since around 1996. I moved to using OL about 7 years ago. I mainly use it because it is familiar.

2. dd the image onto the microsd card

    ```
    sudo dd if=~/Documents/RaspeberryPi/rpi-ol8.3-image-20210106.img of=/dev/mmcblk0 bs=4M
    ``` 
    
    Do this 7 times.

3. 
