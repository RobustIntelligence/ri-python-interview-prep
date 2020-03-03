# Robust Intelligence Python Interview Prep

We are looking forward to your interview at Robust Intelligence. A portion of the on-site interview will consist of a python coding exercise. We would like for you to do some setup in advance to ensure that you are good to go on the day of the interview. If you don't have a laptop, let us know and we will supply you with a loaner laptop on the day of your interview.

First, clone this repository (see the link on the top right).

We will be working with **Python 3** (Python 3.6 or later). See the [RealPython installation guide], if you haven't installed Python 3 yet.

We'll create a [virtual environment] with [venv]
and install some requirements that will be needed to run the interview code on the day of your on-site.

Create a new Python 3 environment called `interview_env` and _activate_ it
(Mac or Linux):

```bash
python3 -m venv ./interview_env
source ./interview_env/bin/activate
```

On Windows (assuming `cmd.exe`):

```batch
python -m venv .\interview_env
.\interview_env\Scripts\activate
```

Next, install the requirements into the activated virtual environment:

```bash
pip install -r requirements.txt
```

If everything installed correctly with no error messages, you are all set!

[RealPython installation guide]: https://realpython.com/installing-python/
[virtual environment]: https://realpython.com/python-virtual-environments-a-primer/
[venv]: https://docs.python.org/3/library/venv.html