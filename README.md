Splunk Technology Add-on for Duo Security (TA-duo_security)
================================

This is a Splunk Technology Add-on App designed to consume duo security logs as a scripted input using the Duo Python API Client and input them into splunk.


 You must setup an [Admin API Application](https://duo.com/docs/adminapi) from Duo security to get the API keys needed for this setup.  This integration currently requires an Duo enterprise or platform subscription account.

Configure your settings and API key in splunk_conf/duo.conf

```
[duo]
; admin api integration key
ikey = <key value>

; admin api secret key
skey = <key value>

; API hostname
host = <api-1234567.duosecurity.com>
```
