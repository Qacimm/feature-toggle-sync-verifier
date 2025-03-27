## About
A comparision script which compares the state of the feature toggles bw FMS (gearbox) and galileo


## How to run

1. Open galileo web app, go to network tab (refresh if you can't see any requests) and copy the cookie (entire thing) from one the api request
2. export COOKIE=<cookie>
4. Add vars (one in each line, ALL CAPS) you want to compare in vars.txt (add empty line after the last variable else it will be ignore by the script)
3. ./comparison vars.txt <env> (use dev/prod to compare vars on qa/prod respectively)

