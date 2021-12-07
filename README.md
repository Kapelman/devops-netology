# devops-netology
The repository for all devops-netology`s homeworks

Hello, Kaplin@Vladimir


# Local .terraform directories
# Игнорируется каталог .terraform в любой директории и субдиректории, а также все файлы в этом каталоге
**/.terraform/*

# .tfstate files
# Игнорируется файл как заказчивающийся на .tfstate, в т.ч. если у файла есть любое расширение 
*.tfstate
*.tfstate.*

# Crash log files
# Игнорируется файл crash.log
crash.log

# Exclude all .tfvars files, which are likely to contain sentitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
# Игнорируются все файлы, окончивающиеся на .tfvars, кол-во символом неважно.
*.tfvars

# Ignore override files as they are usually used to override resources locally and so
# are not checked in

#Игнорируются файлы override.tf, override.tf.json, а также все файлы, имена которых оканчиваются на _override.tf и _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Include override files you do wish to add to version control using negated pattern
#
# Файл example_override.tf исключение, он будет учитываться.
!example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*
# Исключаются все файлы, имя которых содержит tfplan
*tfplan*

# Ignore CLI configuration files
# Исключаются файлы .terraformrc и  terraform.rc
.terraformrc
terraform.rc

