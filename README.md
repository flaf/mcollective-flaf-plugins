# mcollective-flaf-puppet

This is my Debian package for the mcollective plugin (agent
and client) for Ubuntu Trusty and Debian Jessie. To work
correctly, you must put in the file `/etc/puppetlabs/mcollective/server.cfg` :

```ini
# Documentation here: https://github.com/puppetlabs/mcollective-puppet-agent
plugin.puppet.command = /opt/puppetlabs/puppet/bin/puppet agent
plugin.puppet.config = /etc/puppetlabs/puppet/puppet.conf
```

and restart the mcollective server.


