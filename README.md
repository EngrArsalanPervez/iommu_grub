# iommu_grub

```bash
sudo nano /etc/default/grub
  GRUB_CMDLINE_LINUX_DEFAULT=".. intel_iommu=on iommu=pt"
sudo update-grub
sudo reboot
```
