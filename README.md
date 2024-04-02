# Local .terraform directories
**/.terraform/* - Игнорриет скрытый каталог .terraform вместе с содержимым, во всех директориях

# .tfstate files
*.tfstate - Игнорирует все файлы оканчивающиеся на ".tfstate"

*.tfstate.* - Игнорирует все файлы в которых в имени будет конструкция ".tfstate."

# Crash log files
crash.log - Игноруется конкретный файл 
crash.*.log - Игнорируются файлы названия которых начинаются на crash. и заканчиваются на .log 

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
*.tfvars - Игнорирует все файлы оканчивающиеся на .tfvars
*.tfvars.json - Игнорирует все файлы оканчивающиеся на .tfvars.json
 
# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf - Игноруется конкретный файл
override.tf.json - Игноруется конкретный файл
*_override.tf - Игнорирует все файлы оканчивающиеся на _override.tf 
*_override.tf.json - Игнорирует все файлы оканчивающиеся на  _override.tf.json

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrс - Игноруется конкретный файл
terraform.rc - Игноруется конкретный файл 

