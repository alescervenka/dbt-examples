## Installation

```
mkdir -p ~/.python/
python3 -m venv ~/.python/dbt-env
source ~/.python/dbt-env/bin/activate
python -m pip install dbt-core dbt-postgres
```
## Create a project

See this [guide](https://docs.getdbt.com/guides/manual-install?step=3) for more.

```
# cd /my/path/to/dbt-examples
dbt --version
dbt init jaffle_shop
cd jaffle_shop
dbt debug
```

## Materializing the table and the view

```
dbt run
```

## Generating documentation

```
dbt docs generate
dbt docs serve
```

## Revisit this section of the guide

[Build models on top of other models](https://docs.getdbt.com/guides/manual-install?step=11)

## Proper documentation

[Here](https://docs.getdbt.com/docs/core/connect-data-platform/connection-profiles)