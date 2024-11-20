## Testing

Build docker nvim-computer image for testing purposes.

```sh
./build-dockers
```

Run a temporary Docker container via bash.

```sh
docker run --rm -it nvim-computer bash
```

## Instructions

Install ansible.

```sh
./install
```

Run ansible playbook.

```sh
ansible-playbook local.yml --ask-become-pass --ask-vault-pass
```
