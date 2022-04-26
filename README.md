<div align="center">

# Ansible Playbooks
  
❤ All my ansible playbooks collection
  
</div>
  
---
  
![Banner](https://www.ansible.com/hubfs/social-suggested-images/www.ansible.comhubfsImagesRed-Hat-Ansible_OG_1200x630.png)
  
---

### Test environment 

```sh
├── ansible.cfg
├── inventory
│   ├── group_vars
│   │   ├── aws_redhat_servers
│   │   ├── aws_ubuntu_servers
│   │   └── localhosts
│   └── hosts.txt
├── playbooks
│   ├── ...
└── ssh
    ├── centos-ssh.pem
    └── ubuntu-ssh.pem
```


### Collection

|   №   |          Title          |          Tested           |                             Link                              |
| :---: | :---------------------: | :-----------------------: | :-----------------------------------------------------------: |
|   1   | Docker & Docker-Compose | `Ubuntu 20.04`,`Centos 7` |            [playbook](./docker/install-docker.yml)            |
|   2   |      Elasticsearch      | `Ubuntu 20.04`,`Centos 7` | [without docker](./elastic/elasticsearch/elasticsearch.yaml) |
|   3   |         Kibana          | `Ubuntu 20.04`,`Centos 7` |        [without docker](./elastic/kibana/kibana.yaml)         |
|   4   |        Logstash         |                           |                                                               |
|   5   |        ELK-Stack        |                           |                                                               |
|   6   |                         |                           |                                                               |
|   7   |                         |                           |                                                               |
