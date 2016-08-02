# Numix Circle
Circle is an icon theme for Linux from the [Numix project](http://numixproject.org). This readme provides information on [installation](https://github.com/numixproject/numix-icon-theme-circle/#installation), [icon requests](https://github.com/numixproject/numix-icon-theme-circle/#icon-requests) and [hardcoded icons](https://github.com/numixproject/numix-icon-theme-circle/#hardcoded-icons). Licensed under the GPL-3.0+

### Installation
If using this with our [base icon theme](https://github.com/numixproject/numix-icon-theme) make sure you install both parts using the same method. This makes sure that the panel icons keep working as intended.

To install simply download the package on [DeviantArt](http://me4oslav.deviantart.com/art/Numix-Circle-Linux-Desktop-Icon-Theme-414741466) and follow the instructions. Alternatively you can follow any of the following distribution specific methods.

If you use Ubuntu or any of it's derivatives (including Mint and elementary OS) you can use our Numix PPA. Fire up a Terminal and run the following:

```bash
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install numix-icon-theme-circle
```

If you use Fedora you can either use [Fedy](http://folkswithhats.org/) or using a terminal run:

```bash
sudo dnf copr enable numix/numix
sudo dnf install numix-icon-theme-circle
```

For Arch users there's a [community maintained package](https://aur.archlinux.org/packages/numix-circle-icon-theme-git/) in the AUR which builds from this GitHub.

### Issues & Requests
The tracker for this repo is only for issues relating to the Linux packaging. Please report icon requests in [this repo](https://github.com/numixproject/circle-core/issues) which handles the icons themselves.
For normal applications follow [this video tutorial](https://plus.google.com/+NumixprojectOrg/posts/DkRmhFZuWez), for Steam games follow [this one](https://www.youtube.com/watch?v=BuUy4CzCoXc) and for Chrome apps just post a link to the webstore page. When filing your request please be respectful, patient, and remember that Circle development is done solely on the back of donations.

### Hardcoded Icons
To deal with hardcoded application icons Numix uses the [hardcode-fixer](https://github.com/Foggalong/hardcode-fixer) script. A list of the applications supported by the script can be found [here](https://github.com/Foggalong/hardcode-fixer/wiki/App-Support).
