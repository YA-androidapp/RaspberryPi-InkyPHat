# RaspberryPi-InkyPHat

```sh
$ curl https://get.pimoroni.com/inky | bash

$ cd /home/pi/Pimoroni/inky/examples
$ python3 name-badge.py --type "auto" --colour "red" --name "Yu"
$ python3 phat/calendar-phat.py --colour "red"
```

- cron

```
*/30 * * * * python3 /home/pi/Pimoroni/inky/examples/phat/calendar-phat.py --colour "red"
```
