# laravel-softdelete
Laravel SoftDelete

By default laravel uses a column `deleted_at` for softdeletes
This class requires `deleted` CHAR(1) DEFAULT NULL

and replaces all eloquents that uses SoftDelete to use `deleted` instead of `deleted_at` queries

**Prerequisites**

Tables should have `deleted` column - `deleted` CHAR(1) DEFAULT NULL


**Todo**

Auto add deleted column when creating table (schema)
