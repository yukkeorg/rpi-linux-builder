## Quick Start
  $ git clone git://github.com/yukkeorg/rpi-linux-builder.git
  $ cd rpi-linux-builder
  $ ./rpi-linux-builder getconfig pi@<your rpi address>
  $ ./rpi-linux-builder all

  $ scp rpi-kernel.tar.gz pi@<your rpi address>
  $ ssh pi@<your rpi address>
  rpi $ sudo tar xf rpi-kernel.tar.gz -C /
  rpi $ sudo shutdown -r now

## License
This script is under the Public Domain.
