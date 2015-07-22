
This is a backend for campfire (https://campfirenow.com/) for err (http://errbot.net) 2.3.0-rc3 or newer.

Note: as of writing, this backend is only compatible with Python 2.7

## Installation

```
git checkout https://github.com/gbin/err-backend-campfire.git
pip install pyfire
```

and add:

```
BACKEND = 'Campfire'
BOT_EXTRA_BACKEND_DIR = '/path_to/err-backend-campfire'
```

to your config.py

## Authentication

You need to set your BOT_IDENTITY in your config.py as this:

```
BOT_IDENTITY = {
  'subdomain': 'yatta',
  'username' : 'errbot',
  'password' : 'changeme',
}
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
