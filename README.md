## Setup Instructions:

```bash
git clone git@github.com:Jubeki/statamic-multiple-assets-query-issue.git
cd statamic-multiple-assets-query-issue
composer install
cp .env.example .env
php artisan migrate --seed
php please eloquent:import-assets
php please eloquent:import-blueprints
php please eloquent:import-collections
php please eloquent:import-entries
php please eloquent:import-forms
php please eloquent:import-globals
php please eloquent:import-navs
php please eloquent:import-revisions
php please eloquent:import-taxonomies
php please eloquent:import-sites
php please eloquent:sync-assets
```

## CP Credentials:

```plain
admin@example.com
password
```

## Demo Images used for bug report

https://fastly.picsum.photos/id/352/200/300.jpg?hmac=JRE6d4eB1tvPUpBESG8XEM2_22EaXNe2luRrVkydr2E

https://fastly.picsum.photos/id/990/200/300.jpg?hmac=6QkvunJPzSUAgkuY7p_hlJq5SmEdhlV01fbh5cMzKgg

https://fastly.picsum.photos/id/666/200/300.jpg?hmac=FfmCCw-UuMgMhTLigoNVx2auMxtw-EtixqVwwxaefq0
