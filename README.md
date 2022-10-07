# River 600 Tests and Graphs
### Solarcharging to 100%, then Solarcharging and different load first AC and then ~100W DC until battery is empty.<br>
#### Battery jumps on linear DC discharging from 27% to 0%
1) Battery percentage over time, beneath linear output energy over time.<br>
Battery percentage graph shows some minutes 1%, this is wrong, raspi with home assistant was connected to River 600. When battery drops to zero, device shuts off, after a while of charging it starts again, then it shows 0%, well, less than 1% and home assistant takes for blackout time the last known value... 1%. <br>
![Screenshot_20221007-140807_Home_Assistant](https://user-images.githubusercontent.com/46202109/194623634-18b092c9-8a50-4484-a776-a16bc999b53d.png)
2) Here you see battery percentage and beneath solar input energy<br>
![Screenshot_20221007-140905_Home_Assistant](https://user-images.githubusercontent.com/46202109/194623667-f85a2f72-3354-4ac9-a9ae-8f819853fe5d.png)
3) Here you see input energy after full charge and beneath solar input and ac and dc output <br>
The same as in 1\). Output power is linear the last minutes before it drops to zero. Home assistant takes the last known value over blackout time. <br>
![Screenshot_20221007-141008_Home_Assistant](https://user-images.githubusercontent.com/46202109/194623686-e4b7da91-6a97-430a-8c23-fa661bec5bcc.png)
#### But nice too see, after a while of charging, raspi and homeassistant are starting automatically. :))
