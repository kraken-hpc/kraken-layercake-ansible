# roles/kraken-systemd

This role will set up systemd services for kraken if it was built by hand.  

This role is also responsible for creating the `config.yaml` file and starting/enabling the service.

See [defaults/main.yml](defaults/main.yml) for `config.yaml` options.