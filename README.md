# supabase-cities-template

A basic example of supabase migrations/functions deployment

To make database changes:

1. Open supabase studio and make the changes.
2. ```npx supabase db diff -f <migration_name>``` (add ```--linked``` if want to connecto the remove)