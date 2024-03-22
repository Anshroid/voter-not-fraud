# voter-not-fraud

Ever wanted to not commit vote fraud? Run this code to avoid doing so.

1) Make sure you have [python](python.org) installed on your computer
2) Ensure the dependencies are installed: `pip install -r requirements.txt`
3) Clone this repo, and open `cfg.json` in a text editor (do step 4 and 5 first if the file does not exist):
    - `n_threads` controls the number of instances to run simultaneously
    - `headless` should be `true` if you do not want to see the chrome windows
    - `random_chance` is the chance of casting a (weighted) random vote instead of the good joke
4) `python voting-beano.py`
5) If you want to stop execution, use `Ctrl-C`