phpLDAPadmin working on CentOS7
===============================

Application phpLDAPadmin - Web based LDAP administration tool.
Working on CentOS7


## Installation

1. Download phpldapadmin on www apache folder: 
1.1. `wget https://github.com/manuparra/phpLDAPadmin/archive/master.zip`
1.2. (for instance: `/var/www/shtml/phpldapadmin/` or `/var/www/html/phpldapadmin/`)
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
