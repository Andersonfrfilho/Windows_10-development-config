# Windows_10-development-config

1* - Hable ssh and generating ssh
     - https://tecnoblog.net/229971/windows-10-ativar-openssh-cliente/
     - open temrinal
     - generating key for https://tecdicas.com/como-criar-e-utilizar-chaves-ssh-no-windows-e-linux/ user
     - run command
     - ssh-keygen
     - obs, not must password
     - settings/aplications/resources-optional/add-resource/ssh-client

1 docker mongo:
docker: Error response from daemon: Ports are not available: listen tcp 0.0.0.0:27017: bind: Foi feita uma tentativa de acesso a um soquete de uma maneira que é proibida pelas permissões de acesso.
```
net stop winnat
docker start ...
net start winnat
```
