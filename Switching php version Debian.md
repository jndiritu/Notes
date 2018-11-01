#

## Automatically Switch Php version

Choose from a List of all available php versions installed

```
sudo update-alternatives --config php
```

## Manually Switch Php version

### Enable php version

```
sudo a2enmod php7.2
```

### disable php version

```
sudo a2dismod php5
```

### restart apache
```
sudo /etc/init.d/apache2 restart
```
or
```
sudo service apache2 restart
```
or
```
sudo systemctl restart apache2
