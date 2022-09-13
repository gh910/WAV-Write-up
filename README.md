# WAV Write-up

Descrition : Someone sent an audio file to their friend trying to tell them their password, can you help us find it?

When looking at the strings of the audio file we notice that there is nothing interesting, but when we look at the hex of the file we notice that there is data inside
 

![Screenshot_2022-09-13_08_16_59](https://user-images.githubusercontent.com/80649768/189899762-2cfd810f-9870-4d1e-9df3-0e200002da69.png)


Now our first step is to extract this data from the audio file

This data is shown in hex


![Screenshot_2022-09-13_07_57_57](https://user-images.githubusercontent.com/80649768/189900405-49857812-5731-4306-895e-b02bf02a044f.png)


![Screenshot_2022-09-13_07_58_22](https://user-images.githubusercontent.com/80649768/189906991-da8079b5-5c5c-4028-b5ac-56a981fd254e.png)


After extracting this data, we convert it to ascii

Then we see that the flag is encrypted with rot13



![Screenshot_2022-09-13_07_59_01](https://user-images.githubusercontent.com/80649768/189908040-7fb4358e-3380-4468-994f-6f4b2be98a6b.png)


We decrypt this flag and then it appears to us correctly

![Screenshot_2022-09-13_07_59_38](https://user-images.githubusercontent.com/80649768/189908316-2ab49c69-3edc-44ed-9623-14c973c7960e.png)
