# QBitTorrent

This will deploy QBitTorrent to my Kubernetes cluster via Helm.

## Changing Credentials

The default admin credentials are insecure.

Username: admin Password: adminadmin

After first run, change this. Go to Tools -> Options and select the Web UI tab. There will be fields to set a new username/password for the app.

There is an alternate set of credentials in 1Password to use.

## Restrict Disk Cache

In the advanced section, restrict the disk cache to 2GB.