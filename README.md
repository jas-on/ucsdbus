ucsdbus
===

Usage
---
<pre>
usage: ucsdbus [-h] [-r ROUTE] [-s STOP]

optional arguments:

  -h, --help            show this help message and exit

  -r ROUTE, --route ROUTE route for the bus

  -s STOP, --stop STOP  stop for the bus
</pre>

Tips
---
Try to enter route and stop names as correctly as possible.
The script uses a mixture of Levenshtein distance and substring to determine
which which routes and stops to pick.

There are _3_ modes of use:

1. no-args: you have to walkthrough the selection of route and stop
2. route provided: you have to choose the stop
3. route and stop provided: you get a listing of the upcoming bus times for that route and stop combination

