##BluetoothLowEnergy
####Four projects are presented in different folders. These projects are for bluegiga BLE121LR module.
###Adv-based
####BLE project that transmit the maximun amount of data possible in an advertisement packet, using adv_non_conn_ind 
###conn-based
####Heart rate monitor simulator, sends notifications at the highest rate possible, using the timer. In each tick a notification is send.
###master_collector_modify
####BLE Master that connects to a heart rate monitor BLE device, discover the services and enable notifications. Via UART it counts the amount of notifications received.
###master_collector_modify_timer
####BLE Master as before, only that uses the timer to drop the connections in constant intervals. Useful for throughput testing. Via UART it counts the amount of notifications received. Dividing by the fix time, the throughput can be calculated. 
