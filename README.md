# FIRST BOOT SERVICE

## **Please do not merge this branch!!!**

This branch was created in order to test a "*firstboot.service*".

Two files are required for the **firstboot.service**:

- [firstboot.service](./firstboot.service)
- [firstboot.sh](./firstboot.sh)

The file /etc/machine-id should not exist!!!

The file [firstboot.service](./firstboot.service) should be placed into /etc/systemd/system/.
The service should be enabled in the image: **sudo systemctl enable firstboot.service**

The script [firstboot.sh](./firstboot.sh) should be executable and at the moment it is placed in /root/.