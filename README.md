# To whom it may concern

This is a bash script that installs the Autodesk Maya AUR package. Since version 2020.3, the Linux version of Maya has been split up into several different rpm packages, which made the installation via an AUR helper like `yay` impossible. The AUR page of the package contains some information on how to install the package manually, but to me, those did not make it immediately clear what to do. So I took some time to figure it out and wrote this little script to automate the process for the future.

The script still requires `yay` to install two other AUR dependencies. I suppose it could easily be rewritten to install those manually as well, but I was too lazy for that -- maybe I'll do it some time.

# How to use

Just clone this repo and run the script. Then reboot and enter the following command to run Maya:

`/usr/autodesk/maya2020/bin/maya2020`

# Maya 2022

At the time I'm writing this, Maya 2022 has already been released but the AUR package is still at version 2020.4. The code is written in such a way that it *should* work with 2022 as well (as soon as the AUR package is upgraded), but I can't be sure because I haven't tested it. In case it doesn't work, you'll either have to fix it yourself or wait for me to fix it (which, honestly, might never happen).
