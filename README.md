# ssh-key-generator

run the one line cli command on mac
```
curl -sSL https://raw.githubusercontent.com/cookii-king/ssh-key-generator/main/mac/generate-key.sh -o generate-key.sh && chmod +x generate-key.sh && ./generate-key.sh
```

This is bare bones, to use on platform like gcp edit the .pub file and add you working account email address at the end like:
```
ssh-rsa you-key your-email@example.com
```

Remember that if you have previosly use the ip and ssh into it you will probably need to clear the ```.ssh/known_hosts``` file from the bit with that previous ip otherwise may get an error trying to use an new key to ssh with.

You can use:
```
sudo nano /Users/you-username-here/.ssh/known_hosts
```
