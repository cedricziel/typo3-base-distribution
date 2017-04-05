# TYPO3 CMS Base Distribution

Get going quickly with TYPO3 CMS.

## Prerequisites

* composer
* docker-compose

## Quickstart

* `composer create-project cedricziel/typo3-base-distribution project-name 8.7.*`
* `cd project-name`
* `docker-compose up -d`

**setup unattended:**

```
vendor/bin/typo3cms install:setup \
    --non-interactive \
    --database-user-name=typo3 \
    --database-user-password=typo3 \
    --database-host-name=127.0.0.1 \
    --database-port=33060 \
    --database-name=typo3 \
    --use-existing-database \
    --admin-user-name=admin \
    --admin-password=password \
    --site-setup-type=site
```

* `TYPO3_CONTEXT=Development php -S localhost:8000 -t web`
* open your browser at "http://localhost:8000"

## Tasks

* tbd

### Backup

* tbd

# License

GPL-2.0+
