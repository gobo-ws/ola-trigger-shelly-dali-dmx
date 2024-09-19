**OLA trigger config to control DALI lights using Shelly DALI Dimmer Gen3 with DMX (Art-Net, sACN or via DMX input)**

**Requirements**  

* [OLA](https://www.openlighting.org/ola/)
* [curl](https://curl.haxx.se/)
* [Shelly DALI Dimmer Gen3](https://www.shelly.com/en-se/products/product-overview/1xsddgen3)

**Installation**
  
* Download the [shelly-dali.conf](shelly-dali.conf) file and edit the configuration section  

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage**

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger shelly-dali.conf`
