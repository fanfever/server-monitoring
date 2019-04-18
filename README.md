# server-monitoring
monitor CPU&amp;RAM with jvm thread dump and email alters

## Example

`
bash server-monitoring.sh  --info=false --hostname=myAwesomeServer --from=server@yourdomain.com --to=admin@yourdomain.com --cpu=warning=10:critical=15 --memory=warning=30:critical=60 --disk=warning=99:critical=99:fatal=99
`

## Reference

[useful-scripts](https://github.com/oldratlee/useful-scripts)  
[server-monitoring](https://github.com/Freemius/server-monitoring)
