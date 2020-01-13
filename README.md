create-python-package
=====================

Python package scaffold builder

[![wercker status](https://app.wercker.com/status/92f0cf6945529d93502debb6d9edfe73/s/master "wercker status")](https://app.wercker.com/project/byKey/92f0cf6945529d93502debb6d9edfe73)

Installation
------------

```sh
$ pip install -U create-python-package
```

Docker image
------------

The image is available at [Docker Hub](https://hub.docker.com/r/dceoy/create-python-package/).

```sh
$ docker pull dceoy/create-python-package
```

Usage
-----

1.  Create a new package.

    Replace `newpackage` below with your package's name.

    ```sh
    $ mkdir newpackage
    $ create-python-package ./newpackage
    ```

2.  Test the command-line interface of the package. (optional)

    ```sh
    $ python -m venv venv
    $ source venv/bin/activate
    $ pip install -U ./newpackage
    $ newpackage --help
    $ newpackage --debug foo bar
    ```
