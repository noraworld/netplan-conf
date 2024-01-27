# netplan-conf

```shell
sudo systemctl unmask systemd-networkd
sudo systemctl enable systemd-networkd
sudo systemctl start systemd-networkd

sudo rm -r /etc/netplan
sudo ln -s $PWD/etc/netplan /etc

sudo netplan apply
```
