# ansible-thunderbird60
tiny role to download and install mozilla thunderbird v60.0 to fedora w/ GNOME

What it does:

- download tbz2 from mozilla into /tmp/thunderbird
- unzip it into /opt/thunderbird
- copy GNOME desktop icon/app-definition into user directory to make it available in "Applications"

Usage:

1. clone the role tbv60 into your local roles-directory
2. (optional): edit url in tasks/main.yml to choose language etc
3. add role to the hosts you want thunderbird v60 installed to:

``` 
---
- hosts: localhost
  roles:
    - role: tbv60
```
