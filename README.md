balanced-notify
===============

[![Build Status](https://travis-ci.org/balanced/balanced-notify.svg)](https://travis-ci.org/balanced/balanced-notify)

To install:

    python virtualenv.py notify/
    notify/bin/pip install .

To run production:

    ./runp.py

To run debug:

    ./run.py

To test:

    ./tests.py

To run with supervisord:

    notify/bin/pip install supervisor

    notify/bin/supervisord -c supervisor.conf

    notify/bin/supervisorctl -c supervisor.conf

