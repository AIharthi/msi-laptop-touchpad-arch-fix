# msi-laptop-touchpad-arch-fix

-1 chmod +x setup-i2c-restart.sh

-2 ./setup-i2c-restart.sh


the script only unbind and bind the i2c driver when the laptop fully boots up, its kinda a horrible fix but it works, i think the cause of problem is the i2c driver load before the touchpad even get powered. im not an expert so idk. 

love yall :3
