##
# Configurations
##
# Endpoint URL for InfluxDB
veeamInfluxDBURL="TUIPDEINFLUXSERVER"
veeamInfluxDBPort="8086" #Default Port
veeamInfluxDB="telegraf" #Default Database

# Endpoint URL for login action
veeamUsername="TUUSERDEVBO"
veeamPassword="TUPASSDEVBO"
veeamRestServer="https://TUIPDESERVERVBO"
veeamRestPort="4443" #Default Port
*/30 * * * * /home/oper/veeamvbo.sh >> /var/log/veeamvbo.log 2>&1
