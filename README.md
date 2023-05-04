🗄
* `db.md` utils
* `python.md` library
* repos that need: golf, bookcase
 
# design

* _personal data warehouse_: generated personal data https://simonwillison.net/2020/Nov/14/personal-data-warehouses/
* these always seem like a waste of time https://krausefx.com//blog/how-i-put-my-whole-life-into-a-single-database
* _personal database_: hand curated https://tomcritchlow.com/2022/01/26/electric-tables/ https://bofh.org.uk/2019/02/25/baking-with-emacs/

STATUS QUO
* user: web app
* admin: script/proc, visidata, GUI https://realpython.com/python-contact-book/#step-5-creating-new-contacts
* back office: ask admin, use Basedash https://softwareengineeringdaily.com/2020/10/12/basedash-low-code-database-editor-with-max-musing/ https://www.basedash.com/

PEDAGOGY
* tldr: better at SQL if data 1) local 2) interesting
* small databases https://news.ycombinator.com/item?id=34558054

# impl

* check out the help section of pgcli, pgcli can now autocomplete joins?
* documentation https://github.com/k1LoW/tbls
* parser https://news.ycombinator.com/item?id=32560039

* visidata for now and add constraints later?
* ERD?
* https://stackoverflow.com/questions/2732356/list-of-all-tables-with-a-relationship-to-a-given-table-or-view
* https://stackoverflow.com/questions/8094156/know-relationships-between-all-the-tables-of-database-in-sql-server
* https://stackoverflow.com/questions/5499003/sqlite-list-all-foreign-keys-in-a-database
```python
# https://stackoverflow.com/a/59171912
SELECT * FROM pragma_foreign_key_list('reading');
# next step is running this from sqlite3
```

# data

## remote

connect to actual server
* PG exercises https://github.com/zachvalenta/pg-exercises
* https://data.stackexchange.com/help
* https://sqlpd.com/
* https://news.ycombinator.com/item?id=30631477

baked data
* Datasette https://csvbase.com/ fetching https://github.com/fatiando/pooch
* SQL.js https://selectstarsql.com/frontmatter.html#technicals https://github.com/sql-js/sql.js https://github.com/NUKnightLab/sql-mysteries
* https://news.ycombinator.com/item?id=34558054 https://news.ycombinator.com/item?id=34630153
* https://sqlbolt.com/
* https://dataschool.com/learn-sql/basic-practice/
* https://sql-playground.wizardzines.com/

## local

sources
* general https://github.com/awesomedata/awesome-public-datasets https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks https://corgis-edu.github.io/corgis/csv/ https://www.data-is-plural.com/archive/ https://redis.com/blog/datasets-for-test-databases/
* JSON https://github.com/jdorfman/awesome-json-datasets
* csv https://github.com/secretGeek/awesomecsv#data
* 📍 more in 🗄 `ml.md`? put these there? Paul Swanson videos?
> put in ML

Postgres
* PG Exercises https://pgexercises.com/gettingstarted.html https://github.com/AlisdairO/pgexercises/issues/28

SQLite
* executions https://selectstarsql.com/frontmatter.html#dataset
* housing https://www.zillow.com/research/data/
* music https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks
* shootings https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic
* verbos https://github.com/ghidinelli/fred-jehle-spanish-verbs

* HN https://github.com/dogsheep/hacker-news-to-sqlite https://news.ycombinator.com/submitted?id=luu
* movies https://simonwillison.net/2019/Feb/25/sqlite-utils/ https://github.com/jdorfman/awesome-json-datasets
* music https://corgis-edu.github.io/corgis/csv/music/ 

