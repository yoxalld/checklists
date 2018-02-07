# Pantheon to Local by Flywheel
This is a basic overview of how to set up a site made on Pantheon so it runs in LbF.
- create site in Local.
- rename app/public to `app/_public`
- clone pantheon repo into `app/public`
- create file `app/public/wp-config-local.php`
- copy contents of `app/_public` over to new `wp-config-local.php`
- remove `table_prefix`, `ABSPATH`, and `wp_settings` lines as they are included in the Pantheon config file already.