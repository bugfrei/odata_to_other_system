In project1 ist ein einfache UI5 Projekt mit DataSource zu einem externen OData Service.

In der `ui5.yaml` ist ein Proxy zur Adresse des OData Service konfiguriert. Lokal (`ui5 serve`) funktioniert dies.

Wird die App deployed (`ui5-deploy.yaml` ist vorhanden und Konfiguriert) wird jedoch kein Proxy verwendet. Der Service wird auf dem System erwartet, auf das deployed wird.

Die Adresse der Service ist beim einer deployten Version also relativ zur Server-Adresse des S4 Systems.

