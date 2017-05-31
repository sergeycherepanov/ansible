# Ansible Roles

### Bootstrap
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "bootstrap.yml"
```

### Web-server (Traefik + Nginx + Php + Mysql)
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "tnpm.yml"
```

### Virtual hosts
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "vhosts.yml"
```

### Magento v1.x
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "magento1.yml"
```

### Symfony
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "symfony.yml"
```

### PhpMyAdmin
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "phpmyadmin.yml"
```

> Will be available by url: http://XXX.XXX.XXX.XXX/phpmyadmin

### Webmin
```
ansible-playbook -u root -i "XXX.XXX.XXX.XXX," "webmin.yml"
```

> Will be available by url: http://XXX.XXX.XXX.XXX/webmin
