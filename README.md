# ansible_splunk

How to run the playbook (upgrade from splunkd to systemd)<br/>
`ansible-playbook -b -K playbooks/0050-upgrade-to-systemd.yml --tags "upgrade"`

How to run the playbook (downgrade from systemd to splunkd)<br/>
`ansible-playbook -b -K playbooks/0050-upgrade-to-systemd.yml --tags "downgrade"`

How to run the playbook (only run unit file when on systemd)<br/>
`ansible-playbook -b -K playbooks/0050-upgrade-to-systemd.yml --tags "unit_file"`

