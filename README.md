# devops-netology Сергей Леонов

##Задание 1 (описание .gitignore в папке terraform)
- `**/.terraform/*` - игнорирует все файлы внутри каталога terraform;
- `*.tfstate` - игнорирует все файлы с расширением ".tfstate"
- `*.tfstate.*` - игнорирует файлы где в любом месте используется ".tfstate."
- `crash.log` - игнорирует файл с наименованием "crash.log"
- `*.tfars` - игнорирует все файлы с расширением ".tfvars"
- `override.tf` - игнорирует файлы с наименованием "override.tf"
- `override.tf.json` - игнорирует файлы с наименованием "override.tf.json"
- `*_override.tf` - игнорирует файлы с окончанием "_override.tf"
- `*_override.tf.json` - игнорирует файлы с окончанием "_override.tf.json"
- `.terraformrc` - игнорирует скрытый файл с наименованием ".terraformrc"
- `terraform.rc` - игнорирует файл с наименованием. "terraform.rc"
