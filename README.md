# An interactive blockchain built on Python and Flask

### A basic implementation of the consensus algorithm with a rudimentary proof of work model to demonstrate the underlying concepts of the blockchain

## Package Requirements

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed.
2. Install [pipenv](https://github.com/kennethreitz/pipenv).

```
$ pip install pipenv
```

3. Create a _virtual environment_ and specify the Python version to use.

```
$ pipenv --python=python3.6
```

4. Install requirements.  

```
$ pipenv install
```

5. Run the server:
    * `$ pipenv run python blockchain.py`
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`
