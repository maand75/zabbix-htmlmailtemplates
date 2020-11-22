# zabbix-htmlmailtemplates
Replaces the original problem and problem recovery message types in the html email media type<br>
<br>
Includes direct links to triggered event and host dashboard<br>
<br>
Update the files with your domain name in the url so the links for event and dashboard points to your environment<br>
<br>
I also changed the subject to this<br>
Problem: [{TRIGGER.SEVERITY} {HOST.HOST}] {EVENT.NAME}<br>
Problem Recovery: [Resolved {HOST.HOST}] in {EVENT.DURATION}: {EVENT.NAME}<br>
<br>

Example new Average Problem with client supporting rounded boxes<br>
<img src="https://github.com/maand75/zabbix-htmlmailtemplates/blob/main/Images/Problem_Rounded.png"><br>
Example Recovered Average Problem with client supporting rounded boxes<br>
<img src="https://github.com/maand75/zabbix-htmlmailtemplates/blob/main/Images/Problem_Recovery_Rounded.png"><br>
<br>
Example new Average Problem with client not supporting rounded boxes<br>
<img src="https://github.com/maand75/zabbix-htmlmailtemplates/blob/main/Images/Problem.png"><br>
Example Recovered Average Problem with client not supporting rounded boxes<br>
<img src="https://github.com/maand75/zabbix-htmlmailtemplates/blob/main/Images/Problem_Recovery.png"><br>
