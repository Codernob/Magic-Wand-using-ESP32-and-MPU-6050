![image](https://user-images.githubusercontent.com/55651740/177567887-6abbc73e-ce5c-44dd-be5d-0d2a9b987182.png)
![image](https://user-images.githubusercontent.com/55651740/177567920-3baab21c-adb9-4771-b66a-beb04c54973b.png)<br>
In this project, we will make a gesture using magic wand and the esp32 will recognize it as one of two gestures: expelliarus or lumos. <br>
![image](https://user-images.githubusercontent.com/55651740/177568933-4671b4d3-4ba7-45a7-be95-4bf843b5f4b4.png)<br>
the same project is implemented in Arduino BLE 33 Sense and Sparkfun Edge. But they were unavailable in bangladesh at the time of making this project; so we chose ESP32.<br><br>
![image](https://user-images.githubusercontent.com/55651740/177569214-b85db7e4-bb5d-4f93-9d68-383b4a28c110.png)
![image](https://user-images.githubusercontent.com/55651740/177569242-9e343f95-0e27-49c1-a3e7-2e24301a960e.png)
![image](https://user-images.githubusercontent.com/55651740/177569263-f665c584-d371-4a81-9dcd-4c1ff489c962.png)
![image](https://user-images.githubusercontent.com/55651740/177569290-f7540cb7-7926-4f0a-8cff-dcb8f866b58a.png)
![image](https://user-images.githubusercontent.com/55651740/177569320-d6a85dc3-a9e5-4740-8dcb-88512b555e44.png)
![image](https://user-images.githubusercontent.com/55651740/177569340-6b408a96-6150-4e32-b662-2b03e6423b76.png)
![image](https://user-images.githubusercontent.com/55651740/177569356-342cf180-a490-40ec-acd9-583c1e42727c.png)
![image](https://user-images.githubusercontent.com/55651740/177569384-41ff8c23-d75c-4f30-a573-006e9009ae84.png)
![image](https://user-images.githubusercontent.com/55651740/177569406-b5b4be8a-2c83-42ab-9cb6-b15070005139.png)
![image](https://user-images.githubusercontent.com/55651740/177569426-244febee-998e-4b46-907b-e9895f0cac64.png)
![image](https://user-images.githubusercontent.com/55651740/177569451-5807df98-b754-41d7-a88a-8da266119500.png)<br>
We have three classes to predict : Expelliarmus(E), Lumos(L) or Idle(I). Whichever class's probability is higher, that class is our prediction. Here, probability for I (0.85) is higher than probability of E(0.03) and L(0.11); so it predicts that the wand is idle(I).  <br> <br>
![image](https://user-images.githubusercontent.com/55651740/177569473-f9fab380-e210-4e2c-a49c-aebbef068d84.png)


