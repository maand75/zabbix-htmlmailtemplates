# zabbix-htmlmailtemplates
Replaces the original problem and problem recovery message types in the html email media type<br>
<br>
Update the files with your domain name in the url so the links for event and dashboard points to your environment<br>
<br>
I also changed the subject to this<br>
Problem: [{TRIGGER.SEVERITY} {HOST.HOST}] {EVENT.NAME}<br>
Problem Recovery: [Resolved {HOST.HOST}] in {EVENT.DURATION}: {EVENT.NAME}<br>
<br>
