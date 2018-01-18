# Batman theme for Icinga Web 2

By using this theme you are agreeing to never suing the author for any damage which can result from using this theme :)

Thanks to @mikesch-mp https://github.com/Mikesch-mp for inspiration and the skeleton for the batman theme

![Icinga Web 2 theme Batman](https://github.com/jschanz/icingaweb2-theme-batman/raw/master/screenshots/batman-theme-login.png "Batman theme login")

## How to install

Install these theme repository like any other Icinga Web 2 theme:

* copy all folders/files to your icingaweb2 folder (mostly /usr/share/icingaweb2)
```bash
git clone https://github.com/jschanz/icingaweb2-theme-batman /usr/share/icingaweb2/modules/batman
```
* If you want, you can download the background image in full resolution (6000x4000) and logo from https://unsplash.com/photos/meqVd5zwylI and https://www.shareicon.net/download/2015/09/24/106444_man.svg.
```bash
wget 'https://unsplash.com/photos/meqVd5zwylI' -O /usr/share/icingaweb2/modules/batman/public/img/batman.jpg
wget 'https://www.shareicon.net/download/2015/09/24/106444_man.svg' -O /usr/share/icingaweb2/modules/batman/public/img/batman.svg
```

* Enable the module
```bash
icingacli module enable batman
```

* Choose theme in admin or user UI
  - Tactical Overview ![Icinga Web 2 theme Batman](https://github.com/jschanz/icingaweb2-theme-batman/raw/master/screenshots/batman-theme-to.png "Batman theme tactical overview") <p>
  - User Preferences / Activation (de) ![Icinga Web 2 theme Batman](https://github.com/jschanz/icingaweb2-theme-batman/raw/master/screenshots/batman-theme-user-de.png "Batman theme user activation") <p>
  - User Preferences / Activation (en) ![Icinga Web 2 theme Batman](https://github.com/jschanz/icingaweb2-theme-batman/raw/master/screenshots/batman-theme-user-en.png "Batman theme user activation") <p>

## Contribution

Feel free to add your ideas and examples here as well. Just add or modify a theme.

## License

Background picture by Serge Kutuzov on Unsplash (https://unsplash.com/photos/meqVd5zwylI) -> License: https://unsplash.com/license

Icon by Sagar Unagar on shareicon.net (https://www.shareicon.net/man-bat-batman-hero-superhero-super-saver-106444) -> License: Creative Commons (Attribution 3.0 Unported)

Unless otherwise noted the license of these theme is public domain
