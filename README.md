# django_sample

Exploration of Django through the *polling app* tutorial available on the [official documentation](https://docs.djangoproject.com/en/5.0/intro/tutorial01/).

The default SQLite server is used. Run the compiled CLI available at [their website](https://sqlite.org/download.html)  to explore data.

## Packaging
The example was packaged following the [advanced section of the tutorial](https://docs.djangoproject.com/en/5.0/intro/reusable-apps/), using [setuptools](https://setuptools.pypa.io/en/latest/userguide/quickstart.html).

The LICENSE is not valid and just contains *Hello World*. You can package the example by running `python setup.py dist` in [django-polls](/django-polls/) and install the app with pip.