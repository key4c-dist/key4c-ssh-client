# key4c-ssh-client

## 1. Usage
```bash
% ./key4cSshClient -help
Usage: ./key4cSshClient [Options] <Profile>

Options:
[CLI Common]
  -k, --publicKey           show public-Key
  -v, --version             show version

[Connect SSH Server]
  -h, --host value          host address (default: "", or $K4C_SSH_HOST)
  -p, --port value          port number (default: "0", or $K4C_SSH_PORT)
  -u, --user value          user account (default: "", or $K4C_SSH_USER)

[Key4c Config]
  -c, --config value        configuration file (default: "./config.json", or $K4C_SSH_CONFIG)
```

### 1.1. configuration file(config.json)
```json
{
  "key4c": {
    "uuid": "<<KMS_UUID>>",
    "apiKey": "<<KMS_API_KEY>>",
    "kmsKeyId": "<<KMS_KEY_ID>>"
  },
  "appConfig": {
    "logFile": "<<Your Log File>>"
  }
}
```
