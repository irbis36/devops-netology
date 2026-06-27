# devops-netology
## Описание курса DevOps

## Игнорируемые файлы
Благодаря добавленному .gitignore будут игнорироваться следующие файлы:
- `.terraform/` — локальные каталоги Terraform
- `*.tfstate`, `*.tfstate.*` — файлы состояния Terraform
- `crash.log`, `crash.*.log` — файлы логов аварийного завершения
- `*.tfvars`, `*.tfvars.json` — файлы с чувствительными данными (пароли, ключи)
- `override.tf`, `*_override.tf` — файлы локальных переопределений
- `.terraform.tfstate.lock.info` — файлы блокировки
- `.terraformrc`, `terraform.rc` — файлы конфигурации CLI

## Fix branch test line
IDE commit test via Git GUI