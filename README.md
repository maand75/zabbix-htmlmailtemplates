# zabbix-htmlmailtemplates
Replaces the original problem and problem recovery message types in the html email media type

Update the files with your domain name in the url so the links for event and dashboard points to your environment

I also changed the subject to this
Problem: [{TRIGGER.SEVERITY} {HOST.HOST}] {EVENT.NAME}
Problem Recovery: [Resolved {HOST.HOST}] in {EVENT.DURATION}: {EVENT.NAME}

