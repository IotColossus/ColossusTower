# ColossusTower
Particle Core/Photon Code for powering the message tower

Adapted from [MessageTower](https://github.com/plan44/messagetorch)

## Building

Build and deploy via the partical CLI tool:


With your Particle device connected to the internet, find the device id with:

```
> particle list
```

The example output will be:

```
Core1 [55ff6c065075555322461487] (Core) is offline
pho-1 [3c003e001447343339383037] (Photon) is online
```

The id you need is in the brackets.

```
> particle flash <device_id> tower.ino
```
