
https://blog.getdbt.com/what-exactly-is-dbt/

"a command line tool that enables data analysts and engineers to transform data in their warehouses more effectively"
It’s a little bit like, but much more than, Looker PDTs

dbt’s only function is to take code, compile it to SQL, and then run against your database

Jinja
If statements, for loops, filters, macros, and more

dbt’s goal is not to be a library of SQL transformations, but rather to give users powerful tools to build, and share, their own transformations
dbt transforms analysts from tool-users into tool-makers.

https://docs.getdbt.com/tutorial/setting-up

## Process

mkdir [dirname] && cd $_
python3 -m venv ./venv
source ./venv/bin/activate
pip3 install dbt-bigquery
dbt init [name of project]

vim ~/.dbt/profiles.yml
vim ./dbt_project.yml


dbt built documentation
https://github.com/Hiflylabs/awesome-dbt
