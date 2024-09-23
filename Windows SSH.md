Windows SSH
https://youtu.be/cHg8Fk3dmEc

Default folder: user\.ssh

# Create ssh key
```
ssh-kengen
```

# Root
```
sudo passwd root
```

# Set ssh
cd /etc/ssh
vim sshd

-- PermitRootLogin -without-password
-- PublicAuthentication yes

cd /root/.ssh
vim authorized_keys
-- Save public keys into this file

# Restart SSH service
```
service ssh restart
```

# Login into SSH via CMD
```
ssh root@ip_address
```

