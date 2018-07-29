A model represents a database



# How to add fields to a model

### Use Migration to create a table, or add fields

    # Syntax
    rails g migration <migration_name> <list of fields>

    # for example
    rails g migration create_table_name field1:string field2:datetime field3:boolean field4:text

Ensure that the migration name has a verb, such as `create` or `rename`, etc. It'll help rails figure out what action it needs to take on the database
