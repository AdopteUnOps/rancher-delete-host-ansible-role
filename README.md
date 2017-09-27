# rancher-delete-host-ansible-role

Delete rancher host from an existing rancher environment.

If "host_to_delete" is specified, only this host will be deleted and purged, otherwise all hosts of the environment will be removed.

Mandatory Variables
-------------------
```
rancher_api_key: "mykey"
rancher_api_secret: "mysecret"
rancher_project_name: "default"
rancher_project_id: 1234
```

Role Variables
--------------

```
host_to_delete: ""
rancher_master_url: "http://localhost:8080"
```
License
-------

Apache License 2
