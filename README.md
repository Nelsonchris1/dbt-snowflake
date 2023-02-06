The dbt funcdermental course provides a very comprensive introduction to dbt cloud IDE, DBT models, Connecting dbt to respective datawarehouses, Testing and deploying dbt model.

In this little project,  I created fine grained access to snowflake warehouse by creating development and production environment evironment and granting access to certain users.

To repplicate:

1. clone the repo
2. create profiles.yml in usr dir
3. edit profiles.yml with repective credentials
4. test connection with `dbt debug`
5. run `dbt build` to execute
