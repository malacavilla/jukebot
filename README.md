Jukebot
========

[Last.fm](http://www.last.fm/) scrobble bot for Slack.

Commands
--------

**What's everyone listening to?**

Reports what everyone's listening to right now according to Last.fm.

**I'm <name> on Lastfm**

Adds __name__ to the Last.fm profile database.

Usage
------

1. `$ git clone https://github.com/cdolan/jukebot`
2. `$ bundle install --without test`
3. `$ SLACK_API_TOKEN=token bundle exec ./bin/jukebot`

License
-------

MIT License.