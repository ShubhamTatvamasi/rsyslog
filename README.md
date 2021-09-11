# rsyslog

check status of System Logging Service:
```bash
sudo systemctl status rsyslog
```

edit logs to capture:
```bash
sudo vim /etc/rsyslog.d/50-default.conf
```

restart rsyslog:
```bash
sudo systemctl restart rsyslog
```

