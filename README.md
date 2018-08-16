# ansible-thunderbird60
tiny role to download and install mozilla thunderbird v60.0 to fedora w/ GNOME

Usage:

1. clone the role tbv60 into your local roles-directory
2. add role to the hosts you want thunderbird v60 installed to:

``` ---

- hosts: localhost
  roles:
    - role: tbv60
```
