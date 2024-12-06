sudo yum install rhel-system-roles.noarch -y


pip install passlib

python -c "from passlib.hash import sha512_crypt; import getpass; print(sha512_crypt.using(rounds=5000).hash(getpass.getpass()))"

it will promot you to input a password

As an example

SecurePassword1!

$6$HBNwKSUSluaF7hez$FHju4qUVThXNjV.yA/9PCtgeiiHdWEda36TDCZe1ZpgRpa/jFUyGhw/kQNP6ywkNML5El83l3d2PPgfPIOLzg/


Using vault

ansible-vault create vault.yml


