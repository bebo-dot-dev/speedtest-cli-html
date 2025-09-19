# speedtest-cli-html

Maintains a speedtest html log file from ookla speedtest cli json output

* most recent speed test at the table output top
* logs process output to `log-speedtest.log`
* log rotate maintained html files keeping last 5

### Dependencies: 

* ookla speedtest cli for performing speed tests via speedtest.net (https://www.speedtest.net/apps/cli)
* jq for command line json parsing (https://stedolan.github.io/jq/)

![screenshot](https://github.com/jjssoftware/speedtest-cli-html/blob/master/Screenshot.2018.01.02.11.52.01.png  "screenshot")