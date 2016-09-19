# ISP-Tweeter
Python Script to let my ISP Know that my net is slower than what I paid for

You would have to check out [Twitter Apps](https://apps.twitter.com/) to be able to get your API Keys

```bash
# Clone this repository
$ git clone https://github.com/helium96/ISP-Tweeter
# Go into the repository
$ cd ISP-Tweeter
# Install Twython
$ pip install twython
# Install Speedtest-Cli
pip install speedtest-cli
#Run once....
python flow.py
#Run on an interval (900 seconds = 15 minutes)
$ watch -n 900 python flow.py
```
