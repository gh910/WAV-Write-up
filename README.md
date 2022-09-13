# WAV Write-up

Descrition : Someone sent an audio file to their friend trying to tell them their password, can you help us find it?

When looking at the strings of the audio file we notice that there is nothing interesting, but when we look at the hex of the file we notice that there is data inside

command : xxd sound_steg.wav | head 

![Screenshot_2022-09-13_08_16_59](https://user-images.githubusercontent.com/80649768/189899762-2cfd810f-9870-4d1e-9df3-0e200002da69.png)


Now our first step is to extract this data from the audio file

![Screenshot_2022-09-13_07_57_57](https://user-images.githubusercontent.com/80649768/189900405-49857812-5731-4306-895e-b02bf02a044f.png)


![Screenshot_2022-09-13_07_58_22](https://user-images.githubusercontent.com/80649768/189906991-da8079b5-5c5c-4028-b5ac-56a981fd254e.png)
