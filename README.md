![Icon](https://raw.github.com/jazzido/crowdata/master/static/img/crowdata.png) crowdata
========================================================================================

Easily crowdsource the analysis of your documents


## Installation

    pip install -r requirements.txt

Rename `local_settings.py.example` to `local_settings.py` and adjust the settings there.

Then,

    python manage.py syncdb
    python manage.py migrate --all
    python manage.py runserver_plus

Copyright (C) 2013 Manuel Aristarán <jazzido@jazzido.com>

Crow icon designed by Matt Steele from The Noun Project — Creative Commons Attribution (CC BY 3.0)
