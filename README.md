# wp-plugin-migrate-db-pro

## Using this plugin in a composer project

**For your project's composer.json file**
* Add this to the repositories section
```
    {
      "type": "vcs",
      "url": "https://github.com/PartnerComm/wp-plugin-migrate-db-pro.git"
    }
```

* Add this to the require section. Note, update the version to the latest release in the repo
```
    "pcomm/wp-migrate-db-pro": "2.3.*"
```
* Don't forget to separate lines with commas

## Updating this plugin
* Log in to our account on [deliciousbrains.com](https://deliciousbrains.com/)
* Go to Licenses > Downloads
* Download the latest files
* Clone this repo if you don't have it locally
* Update the files in the repo with the newly downloaded files
* Commit the updates, tag it with the current plugin version number and push your changes up

## Changelog
### 2.3.3 - May 19, 2022
- Bug fix: WP Migrate no longer initializes on pages outside of WP Admin in order to improve front-end performance
- Bug fix: Pulling themes or plugins without the database now works on the first attempt
- Bug fix: Migrations without the database are now compatible with PHP 8 or above
- Bug fix: Network-to-network migrations via the CLI now process without warnings
- Bug fix: Compatibility mode path now uses the proper case to avoid errors with case-sensitive file systems
### 2.3.2
Changelog: [https://deliciousbrains.com/wp-migrate-db-pro/doc/changelog/](https://deliciousbrains.com/wp-migrate-db-pro/doc/changelog/)