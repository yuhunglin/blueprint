## Installation

- `bundle install`
- `cp .env.sample .env`
- <fill in env variables>
- <get group_vars>
- vagrant plugin install vagrant-env
- vagrant up


## Credits

- https://github.com/enginyoyen/ansible-best-practises/

## Assumptions
- Debian jessie
-- when necessary, raspbian
- Systemd (for better or worse)
- Python is pre-installed on system
- Aptitude is installed on system
- Swapon if memory is an issue

## Notes:
- acd-cli:
  - http://blog.woralelandia.com/2012/07/16/fuse-mount-options/
  - reference: http://blog.woralelandia.com/2012/07/16/fuse-mount-options/
- backup?:
  - http://www.howtogeek.com/50794/keep-rsync-from-using-all-your-bandwidth/
  - http://serverfault.com/questions/461306/make-a-cronjob-wait-for-previous-rsync-job-to-finish
  - http://speakmy.name/2013/05/20/automatic-backups-with-ruby-and-linux-shell-part-2/
  - maybe a separate one for moving files and actual compressed backups?
