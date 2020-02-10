# VVV php-ldap Utility

Utility to install php-ldap as part of provisioning in [VVV](https://github.com/varying-vagrant-vagrants/vvv/).

## How To Use

Extend your `vvv-custom.yml` like this:

```yml
utilities:
  php-ldap:
    - php-ldap

utility-sources:
  php-ldap: https://github.com/olipayne/vvv-php-ldap
```

For more see the [official VVV documentation on utilities](https://varyingvagrantvagrants.org/docs/en-US/utilities/).
