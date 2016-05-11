This repository holds the source code for my slides on "Does
disaggregated electricity feedback reduce domestic electricity
consumption? A systematic review of the literature" presented as part
of the
[3rd International NILM Workshop](http://nilmworkshop.org/2016/index.html)
in Vancouver, Canada on Saturday 14th May 2016.

If you just want to view this presentation, just point your browser to
[http://jackkelly.github.io/NILM_Workshop_talk_2016](http://jackkelly.github.io/NILM_Workshop_talk_2016)

You do not need to clone this repository just to view the
presentation.

This presentation is based on my paper:

* Jack Kelly & William Knottenbelt. "**Does disaggregated electricity
feedback reduce domestic electricity consumption? A systematic review
of the literature**", In *3rd International NILM Workshop*, Vancouver,
Canada, 14-15 May 2016. arXiv:[1605.00962](http://arxiv.org/abs/1605.00962)

# Run presentation on your local machine

If you want to run this presentation locally then here is one way to
do that (on Ubuntu):

First clone the git repository. Then run:

```
sudo apt-get install nodejs-legacy npm
sudo npm install -g grunt-cli http-server bower
bower install
```

Then run `http-server -c-1` from the base directory of this project.
And point your browser to `http://localhost:8080`.

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
