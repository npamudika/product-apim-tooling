## apimcli set

Set configuration

### Synopsis


Set configuration parameters. Use at least one of the following flags
* --http-request-timeout <time-in-milli-seconds>
* --tls_renegotiation_mode <never|once|freely>
* --export-directory <path-to-directory-where-apis-should-be-saved>

```
apimcli set [flags]
```

### Examples

```
apimcli set --http-request-timeout 3600 --export-directory /home/user/exported-apis
apimcli set --http-request-timeout 5000 --export-directory C:\Documents\exported
apimcli set --http-request-timeout 5000
apimcli set --tls_renegotiation_mode freely
```

### Options

```
      --export-directory string    Path to directory where APIs should be saved (default on Unix, including macOS "$HOME/.wso2apimcli/exported", default on Windows "%HOME%\.wso2apimcli\exported")
  -h, --help                       help for set
      --http-request-timeout int   Timeout for HTTP Client (default 10000)
```

### Options inherited from parent commands

```
  -k, --insecure   Allow connections to SSL endpoints without certs
      --verbose    Enable verbose mode
```

### SEE ALSO
* [apimcli](apimcli.md)	 - CLI for Importing and Exporting APIs and Applications
