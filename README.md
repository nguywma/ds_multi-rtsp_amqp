# ds_multi-rtsp_amqp
Deepstream python app for inference with rtsp stream and send message via rabbitmq
## all-in-one.py
Python code with real-time rtsp inference, saving frame, sending message to rabbitmq and output a rtsp stream. 
To run the code(sudo if nessesary): 
```bash
python3 all-in-one.py rtsp://username:password@address/
```
example 
```bash
python3 all-in-one.py rtsp://admin:ivsr2019@192.168.0.103/
```
