# Dockerboxes

Vagrant boxes with Docker installed and configured.

## Usage

From the command line:

    vagrant init precise64-docker0.6.3 https://github.com/stuff/ohyeah

In a Vagrantfile:

```ruby
Vagrant.configure(2) do |config|
  config.vm.box = "precise64-docker0.6.3"
  config.vm.box_url = "http://domain.com/path/to/above.box"
end
```

## Avaiable Boxes

| OS                  | Box Name              | Box URL  |
| ---------           | --------------------- | ----------------------- |
| Ubuntu 12.04 64-bit | precise64-docker0.6.3 | https://github.com |
