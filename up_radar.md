# HOW TO SET UP THE RADAR OHW (LINUX)

- Set up:
```
sudo ip link set can0 up type can bitrate 500000
```

- Verify the network:
```
candump can0
```

- Set down:
```
sudo ip link set can0 down
```
