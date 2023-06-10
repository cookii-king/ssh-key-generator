# ssh-key-generator.sh

run the one line cli command on mac
```
curl -sSL https://raw.githubusercontent.com/cookii-king/ssh-key-generator/main/mac/generate-key.sh -o generate-key.sh && chmod +x generate-key.sh && ./generate-key.sh
```

This is bare bones, to use on platform like gcp edit the .pub file and add you working account email address at the end like:
```
ssh-rsa you-key your-email@example.com
```
