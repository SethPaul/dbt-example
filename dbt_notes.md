
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
mkdir dbt_folder_name && cd $_
python3 -m venv ./venv
source ./venv/bin/activate
pip3 install dbt-bigquery
dbt init dbt_project_name

vim ~/.dbt/profiles.yml
vim ./dbt_project.yml




dbt built documentation
https://github.com/Hiflylabs/awesome-dbt


https://medium.com/the-telegraph-engineering/dbt-a-new-way-to-handle-data-transformation-at-the-telegraph-868ce3964eb4

https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-building-tool-dbt-part-1-8cfa21ef97c5
project management/organization

https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-build-tool-dbt-part-2-a3581c76723c
- get the best out of your dbt_project.yml file.
- dbt makes you rethink some aspects of traditional data warehousing.
- dbt Macros usage.
- wrap dbt.

https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-build-tool-dbt-part-3-38cefad40e59
- How to orchestrate data pipelines and dbt models.
- Use dbt documentation and serve it to an entire organisation.


"dbt is an extremely powerful and flexible tool that quickly enables your team to build data-pipelines. This flexibility comes with a price.""



direnv
virtual env
awesome list
