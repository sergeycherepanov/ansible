# Ansible Roles

### Bootstrap
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "bootstrap.yml"
```

### Web-server (Traefik + Nginx + Php7.0 + Mysql)
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "tnpm70.yml"
```

### Web-server (Traefik + Nginx + Php5.6 + Mysql)
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "tnpm56.yml"
```

### Magento v1.x
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "magento1.yml"
```

### Magento v1.x VHosts
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "magento1_vhosts.yml"
```

### Symfony
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "symfony.yml"
```

### PhpMyAdmin
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "phpmyadmin.yml"
```

> Will be available by url: http://XXX.XXX.XXX.XXX/phpmyadmin

### Webmin
```
$ python ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "webmin.yml"
```

> Will be available by url: http://XXX.XXX.XXX.XXX/webmin
