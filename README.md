# aap-eda
Ansible Automation Platform Event Driven Ansible Learning Content

#Command for hitting a rulebook locally 
curl -H 'Content-Type: application/json' -d "{\"message\": \"Ansible is good\"}" http://aapeda.it22.local:5000/endpoint

curl -H 'Content-Type: application/json' -d "{\"message\": \"Ansible is good\"}" 192.168.100.213:5000/endpoint
http://192.168.100.213:6000/endpoint


#Installing IdM Server 
ipa-server-install -n idm.it22.local -r IDM.IT22.LOCAL -a i4info-t4tech@22 -p i4info-t4tech@22 --mkhomedir --no-ntp --auto-reverse --setup-dns --no-forwarders --unattended