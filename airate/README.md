# airate

Use AI for static analysis of C#, C++, Java, JavaScript, PHP, Python, and TypeScript projects.

## Setup the environment

Follow the instructions at the top of the [supercharger README](https://github.com/catid/supercharger/) to set up the environment, and to run a worker server.

Install additional dependencies:

```bash
conda install libclang

# Install additional requirements from airate directory
pip install -r airate/requirements.txt
```

## Test airate

```bash
python airate/airate.py --node localhost --port 5000 airate/tests/
```