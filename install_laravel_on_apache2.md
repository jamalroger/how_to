# How to config laravel on apache2

Change config in apache2 
```
AllowOverride None to AllowOverride All
```

Enable rewrite mode
```
sudo a2enmod rewrite
```


If you create new virtual host website
```
sudo a2ensite virtual_host.conf
```


Change Permission 
```
sudo chgrp -R www-data {laravel_folder}
sudo chmod -R 775 {laravel_folder}/storage
```

just this it easy !!!
