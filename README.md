This repository holds the source code for my presentation on
[http://www3.imperial.ac.uk/newsandeventspggrp/imperialcollege/administration/energyfutureslab/eventssummary/event_5-4-2016-9-1-7]("Do
disaggregated electricity bills really help people to save energy?")
presented as part of the Imperial College Energy Futures Lab seminars.

If you just want to view this presentation, just point your browser to
TODO.

You do not need to clone this repository just to view the presentation.

---

If you want to run this presentation locally then here is one way to
do that (on Ubuntu):

```
sudo apt-get install nodejs-legacy npm
sudo npm install -g grunt-cli http-server bower
bower install
```

Then run `http-server -c-1` from the base directory of this project.
And point your browser to `http://localhost:8080`.
