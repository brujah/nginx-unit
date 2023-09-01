# nginx-unit

andreas@dev1:~/nginx-unit$ sudo curl -X PUT --data-binary @config.json --unix-socket        /var/run/control.unit.sock http://localhost/config/

{
        "error": "Failed to apply new configuration."
}
