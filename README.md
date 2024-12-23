# dbt_northwind_aovivo
O profile.yml deve ter a seguinte estrutura:

```yaml
northwind:
  outputs:
    dev:
      dbname: northwind
      host: localhost
      pass: postgres
      port: 55432
      schema: public
      threads: 1
      type: postgres
      user: postgres
  target: dev
```
