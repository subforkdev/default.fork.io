
# DEFAULT.FORK.IO

This site is running live at [default.fork.io](https://default.fork.io). Built and hosted on [subfork.com](https://subfork.com).

## Get the source code

```bash
$ git clone https://github.com/subforkdev/default.fork.io
```

## Setup

```bash
$ python -m virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Create site

After [creating a new site](https://docs.subfork.com/creating-your-site/) on [subfork.com](https://subfork.com), change the domain value
in the `subfork.yml` file to the domain of your new site:

```yaml
domain: <domain>
```

Add Subfork [API keys](https://docs.subfork.com/creating-your-site/#api-keys)
to the environment or a `.env` file:

```bash
$ export SUBFORK_ACCESS_KEY=<access key>
$ export SUBFORK_SECRET_KEY=<secret key>
```

## Run locally

```bash
$ subfork run
```

## Deploy

```bash
$ subfork deploy -c <comment> --release
```
