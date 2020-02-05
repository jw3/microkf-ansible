Kubeflow on Microk8s wth Ansible 
===

```shell script
ansible-playbook site.yml
```

### default configuration

| Software   | Version  | 
|------------|----------|
| Microk8s   | 1.17     |
| Kubeflow   | 0.7.1    |


### environment

| Field                   | Description                                | Default Value              |
|-------------------------|--------------------------------------------|----------------------------|
| playbook_http_proxy     | Specified http proxy for playbooks         |                            |
| playbook_https_proxy    | Specified https proxy for playbooks        |                            |
