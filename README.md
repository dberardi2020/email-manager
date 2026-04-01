# email-manager

A Dockerized Python tool for auto-cleaning a Gmail inbox. Monitors an "Unsubscribe"
folder — any sender moved there gets blacklisted, and their future emails are
automatically deleted from your inbox.

## Usage
```sh
docker-compose up
```
On first run you will be prompted for your Gmail credentials, which are saved locally.
