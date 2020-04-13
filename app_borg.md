# <img src="/images/borg_logo.svg" height="80px" alt="borg's logo"> Borg

[![Install Borg with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=borg) [![Integration level](https://dash.yunohost.org/integration/borg.svg)](https://dash.yunohost.org/appci/app/borg)

### Index

- [Useful links](#useful-links)

BorgBackup (short: Borg) is a deduplicating backup program. Optionally, it supports compression and authenticated encryption.

The main goal of Borg is to provide an efficient and secure way to backup data. The data deduplication technique used makes Borg suitable for daily backups since only changes are stored. The authenticated encryption technique makes it suitable for backups to not fully trusted targets.[¹]

## Useful links

+ Website: [bitwarden.com](https://bitwarden.com/)
+ Official documentation: [help.bitwarden.com](https://help.bitwarden.com/)
+ Application software repository: [github.com - YunoHost-Apps/bitwarden](https://github.com/YunoHost-Apps/bitwarden_ynh)
+ Fix a bug or an improvement by creating a ticket (issue): [github.com - YunoHost-Apps/bitwarden/issues](https://github.com/YunoHost-Apps/bitwarden_ynh/issues)

------

[¹]: [borgbackup.readthedocs.io](https://borgbackup.readthedocs.io/en/stable/#what-is-borgbackup)
