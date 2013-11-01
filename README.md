# Dockerboxes

Vagrant boxes with Docker installed and configured. **Please be patient, as these boxes are quite large.**

## Usage

From the command line:

    vagrant init precise64-docker0.6.5 https://s3.amazonaws.com/boxes.stackmachine.com/precise64-docker0.6.5.box

In a Vagrantfile:

```ruby
Vagrant.configure(2) do |config|
  config.vm.box = "precise64-docker0.6.5"
  config.vm.box_url = "https://s3.amazonaws.com/boxes.stackmachine.com/precise64-docker0.6.5.box"
end
```

## Avaiable Boxes

| OS                  | Box Name              | Box URL  |
| ---------           | --------------------- | ----------------------- |
| Ubuntu 12.04 64-bit | precise64-docker0.6.5 | https://s3.amazonaws.com/boxes.stackmachine.com/precise64-docker0.6.5.box |
| Ubuntu 12.04 64-bit | precise64-docker0.6.3 | https://s3.amazonaws.com/boxes.stackmachine.com/precise64-docker0.6.3.box |
