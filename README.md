# haproxy
bastille-haproxy

## Now apply template to container
```sh
bastille create haproxy 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/haproxy; bastille template haproxy bastille-templates/haproxy
```
## License
This project is licensed under the BSD-3-Clause license.