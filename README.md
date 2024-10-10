


```
python3 -m venv venv
```


```
source venv/bin/activate
python3 -m pip install ansible-builder
```


```
ansible-builder build --tag ghcr.io/phlpdtrt/awx-custom-ee:latest --container-runtime docker --verbosity 3
```


```
docker push <your_registry_name>/awx/ee:<your_base_ee_version>-custom
```