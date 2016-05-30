- maybe a different take on the shell scripts
- lucid chart of layout?
- testkitchen

- some forking to handle for debian/ubuntu differences
- https://pypi.python.org/pypi/StringGenerator/0.1.9 as a filter_plugin (http://docs.ansible.com/ansible/developing_plugins.html) (https://github.com/lxhunter/ansible-filter-plugins)
  - fix password salt for deluged
- deluged: eh... can't encrypt deluge password properly

- route53
- fix deluged configs
- muck with history: http://www.computerhope.com/unix/uhistory.htm
- common: locales setup?
- common: look for an rbenv role: https://github.com/zzet/ansible-rbenv-role

- look into s3ql to replace encfs?
- aufs over unionfs
- look into spideroak to replace crashplan

- http://www.cyberciti.biz/faq/linux-inotify-examples-to-replicate-directories/
- hedonism: time-machine setup (http://bullcreekstudio.com/uncategorized/debian-wheezy-mavericks-time-machine-server/)
- get away from crappy python libraries: https://github.com/terencehonles/fusepy/commit/220ab76b5d1a95ffced0e48023abdea926ae6bfc. Splat conditional into ~/pyenv/versions/3.5.1/lib/python3.5/site-packages/acdcli/bundled/pyfuse.py
- pull in the different take on openvpn

- What's a good strategy to deal with vars needed in meta dependencies?
- https://tensile-runway-92512.appspot.com to refresh token
- deal with shifting plex media version
- Spotweb: best way to restore is to just let the retrieval run (maybe without ssl) instead of trying to restore the db.
  - And unfortunately disable ssl
- Figure out ways to routinely backup sickrage
- look into sonarr if sickrage is crapping out
- crontabs on hedonism to fix folder permission after moving completed items from sickrage and couchpotato
