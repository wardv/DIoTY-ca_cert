# DIoTY-ca_cert for your MQTT broker dioty.co
ca certificate for DIoTY (www.dioty.co)

Sample usage using the mosquitto client libraries:

mosquitto_pub -h mqtt.dioty.co -p 8883 -u &lt;your user-id&gt; -P &lt;your password&gt; -t &lt;topic&gt; -m &lt;message&gt; -r --cafile ./dioty_ca.crt


