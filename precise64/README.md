## WARNING

These files are only used for creating the Vagrant boxes. You shouldn't use them.

## Guide


```bash
git clone https://github.com/dotcloud/docker.git
cd docker
vagrant up
```

Wait for three minutes as the new guest additions install

```bash
vagrant reload
vagrant package --output precise64-docker0.Y.X.box --vagrantfile ../Vagrantfile
```
