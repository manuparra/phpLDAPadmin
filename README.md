phpLDAPadmin working on CentOS7
===============================

Application phpLDAPadmin - Web based LDAP administration tool.
Working on CentOS7


## Installation

1. Download phpldapadmin on your www  apache folder (in your server): 

```
wget https://github.com/manuparra/phpLDAPadmin/archive/master.zip
(for instance: /var/www/shtml/phpldapadmin/ or /var/www/html/phpldapadmin/)
````

2. Open browser: `https://myhost/phpldapadmin/`
3. Rename `config/config.php.example` to `config/config.php`
4. Reload you browser `https://myhost/phpldapadmin/`

## Error solved

This version of phpldapadmin solves the problem with SESSION unset:

```
Notice: Undefined variable: _SESSION in /path/to/pla/lib/page.php on line 381 Fatal error: 
Call to a member function getValue() on a non-object in /path/to/pla/lib/page.php on line 381
```

## License

[LICENSE](LICENSE)
