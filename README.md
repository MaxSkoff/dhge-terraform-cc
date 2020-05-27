# dhge-terraform-cc

Ein einfaches Terraform Beispiel für die AWS.

## Getting Started

Folge den Anweisungen, um das Beispiel zum laufen zu bringen.

### Prerequisitions

Es wird die Terraform CLI benötigt.

https://www.terraform.io/

### Anpassen

In der `variables.tf` müssen die Variablen `secret` und `access` durch entsprechende Schlüssel von einem AWS Account ersetzt werden.

## Ausführen

```
terraform init
terraform apply
```

Entsprechenden Plan mit `yes` bestätigen und ausführen lassen.

## Bereinigen

`terraform destroy`
