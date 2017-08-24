# cf-code-submit
submit code to codeforces from command line

## Uses
Set contest or gym ID. Example: `cf con 844` or `cf gym 101482`
Submit code to a problem, will guess problem. Example: `cf submit` or `cf submit a.cpp`
Specify a problem with `-p` or `--prob`. Example: `cf submit code.cpp -p 844a`
Watch the status of submission with `-w` or `--watch`. Example: `cf submit a.cpp -p 844a -w` 
Look at status of the last submission. Example: `cf peek`
Watch the status of the last submission. Example: `cf watch`
Store login info (username and password), will prompt you to enter password. Example: `cf login` or `cf login henryx` 

## Dependencies
robobrowser
