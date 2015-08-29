# ansible-isucon-pass/isucon4-qualifier

## Overview

Ansible playbook for [ISUCON4-qualifier](http://isucon.net/archives/41252218.html) tuning

## Requirement

- CentOS 6.x

## Usage

Remote:
```
git clone https://github.com/matsuu/ansible-isucon-pass.git
cd ansible-isucon-pass/isucon4-qualifier
echo 192.0.2.1 > hosts
ansible-playbook -i hosts playbook.yml
```

Local:
```
yum install -y epel-release git
yum install -y ansible
git clone https://github.com/matsuu/ansible-isucon-pass.git
cd ansible-isucon-pass/isucon4-qualifier
ansible-playbook -i local playbook.yml
```

## References

- [ISUCON4(2014) オンライン予選レギュレーション](http://isucon.net/archives/39979344.html)
- [ISUCON4 予選当日マニュアル](https://gist.github.com/mirakui/e394ed543415852d34a6)
- [isucon/isucon4](https://github.com/isucon/isucon4)
- [vagrant-isucon-pass](https://github.com/matsuu/vagrant-isucon-pass)
- [ansible-isucon](https://github.com/matsuu/ansible-isucon)
