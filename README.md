# gcp-shutdown-systemd
GCP has a bad timing issue when executing the shutdown script

This systemd service file will execute a script before shutting down, ahead of the GCP shutdown script which runs after all the services stop.
