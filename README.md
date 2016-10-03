#BluetoothLowEnergy
#Four projects are presented in different folders.
#Adv-based
#BLE project that transmit the maximun amount of data possible in an advertisement in adv_non_conn_ind 
#conn-based
#heart rate monitor simulator, that send notifications at the highest rate possible, achiving a higher throughput
#master_collector_modify
#BLE Master that connects to a heart rate monitor BLE device, discover the services and enable notifications. Via UART it counts the amount of notifications received.
#master_collector_modify_timer
#BLE Master as before, only that uses the timer to drop the connections in constant intervals. Useful for throughput testing. Via UART it counts the amount of notifications received. Dividing by the fix time, the throughput can be calculated. 
