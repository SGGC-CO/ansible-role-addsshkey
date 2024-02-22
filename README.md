# ansible-role-addsshkey

Add SSH key to the server.

## Requirements

ansible-role-lsk

## Variables

1. inventory.ini

```yaml
ansible_user: username of the server
```

2. playbook.yml

```yaml
user: username of the server
```

## Dependencies

ansible-role-lsk

## Example Playbook

`tests/test.yml`

`cd tests` and run the playbook with the following command:

```yaml
ansible-galexy install -r requirements.yml
ansible-playbook -i inventory.ini test.yml --ask-become-pass
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
