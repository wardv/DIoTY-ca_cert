# DIoTY-ca_cert
ca certificate for dioty.co

Sample usage using the mosquitto client libraries:

mosquitto_pub -h mqtt.dioty.co -p 8883 -u <your user-id> -P <your password> -t <topic> -m <message> -r --cafile ./dioty_ca.crt


