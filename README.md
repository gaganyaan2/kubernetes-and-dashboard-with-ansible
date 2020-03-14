### kubernetes-and-dashboard-with-ansible

1. Update the hosts in hosts file

2. Run ansible code to install k8 and dashboard
`ansible-playbook -i hosts dependency.yml`
`ansible-playbook -i hosts master.yml`
`ansible-playbook -i hosts worker.yml`
`ansible-playbook -i hosts dashboard/dashboard.yml`

3. Dashboard will be accessible from https://<b>$Master_ip</b>:30080/