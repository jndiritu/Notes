#

## Automatically

Choose from a List of all available php versions installed

```
sudo update-alternatives --config php
```

## Manually

### Enable

```
sudo a2enmod php7.2
```

### disable

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
