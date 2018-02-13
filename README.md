# kamailio-config
This is the specific kamailio configuration necessary to deploy the [webph.one](https://github.com/saycel/Saycel.Phone) server for its corresponding [application](https://github.com/saycel/webph.one). The files are pulled into the Docker kamailio container. The repository is broken into three files:
- kamailio-local.cfg.sample
    - This is a sample file of the env variables necessary for kamailio to run. To use, copy this file, adjust its variables accordingly, and rename it kamilio-local.cfg
- kamailio-routing.cfg
    - This file is the dialplan logic for how webph.one handles calls. 
- kamailio.cfg
    - This file defines the kamailio modules required for webph.one.  It also configures the module parameters accordingly. 
