# dxproject
d=drupal
x=WxT
project=project to fork
(WxT with Drupal 9 / Drupal 10 and eventually future core versions)


This project requires entreprise7pro/dxbase https://github.com/entreprise7pro/dxbase (from packagist) which brings in the wxt distribution along with carefully curated core patches and also contrib modules that are very good to use with wxt.
A lot of attention to detail and work was done to ensure that these items help build a very strong site.

so in this dxproject you can fork it and put your own stuff in, custom modules, config, whatever.

QUICK INSTALLATION:

```
git clone https://github.com/entreprise7pro/dxproject.git mywxtsite;
cd mywxtsite;
git checkout 4.4.0;
sudo composer self-update 2.4.4;
composer install;
```


features: helpful installation setup for splash (if you have one) 
          configuring split settings in settings.php, configuring user/psw for db in settings.php.
          

