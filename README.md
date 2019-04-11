# server-monitoring
monitor CPU&amp;RAM with jvm thread dump and email alters

## Example

`
bash server-monitoring.sh --debug=true --hostname=myAwesomeServer --from=server@yourdomain.com --to=admin@yourdomain.com --cpu=warning=20:critical=50 --memory=warning=30:critical=60 --disk=warning=40:critical=60:fatal=70
`

## Reference

[useful-scripts](https://github.com/oldratlee/useful-scripts)  
[server-monitoring](https://github.com/Freemius/server-monitoring)
