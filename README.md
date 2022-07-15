# NETOLOGY-DEVOPS21
first line

# Описание правил игнорирования terraform/.gitignore 

# будут игнорироваться файлы с буквосочетанием .tfstate
*.tfstate
*.tfstate.*

# будут игнорироваться файлы логов с буквосочетанием 
crash.log
crash.*.log

# будут исключаться все файлы с буквосочетанием .tfvars
*.tfvars
*.tfvars.json

# будут игнорироваться файлы с буквосочетанием

override.tf
override.tf.json
*_override.tf
*_override.tf.json


# будут игнорироваться файлы конфигурации CLI
.terraformrc
terraform.rc