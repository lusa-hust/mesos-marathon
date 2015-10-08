# deploy nginx into marathon

- chạy lệnh:
```
$ cd deployment/

# Đẩy lên cụm production
$ ansible-playbook -i production site.yml

# Đẩy lên cụm staging
$ ansible-playbook -i staging site.yml
```