# hp-wmi
HP WMI driver with thermal policy support


### Get current thermal policy
cat /sys/devices/platform/hp-wmi/thermal_policy

### Set thermal policy
echo X > /sys/devices/platform/hp-wmi/thermal_policy

| Profile                   | Value |
| ------------------------- |:-----:|
| Performance               | 0     |
| Default (HP reccomended)  | 1     |
| Cool                      | 2     |
