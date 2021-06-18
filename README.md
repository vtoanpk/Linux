# Linux
Linux Opera System.

## Remote Server with .ssh key file

- `sudo ssh -i ~/.ssh/ls_dev_key root@128.199.123.111`

## Copy file from Server to Client

- `scp -i ~/.ssh/ls_dev_key root@139.59.107.184:/app/import_data.sql /home/vt/Desktop`

If permission denied

chmod 600 ~/.ssh/ls_dev_key

sudo chmod 600 /path/to/my/key.pem

sudo chmod 755 ~/.ssh

mkdir -p ~/.ssh && chmod 700 ~/.ssh
mv -i /home/vt/Downloads/ls_dev_key ~/.ssh/
sudo chmod 755 ~/.ssh
chmod 600 ~/.ssh/ls_dev_key

## Run ngrok with https

- `ngrok http 3000 -host-header="localhost:3000"`

## Check process program running in Linux

- `ps aux | grep <name_program>`



psql -U postgres -d saleor1 < /home/vt/Downloads/data-server.sql



git reset --soft HEAD~1

