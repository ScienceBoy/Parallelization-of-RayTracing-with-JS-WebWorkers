Programs to analyse the parallelization of RayTracing calculations on mobile phone CPU cores by using JavaScript WebWorkers

The basic change to WebWorkers can be depicted as in the following image:

![grafik](https://user-images.githubusercontent.com/101653815/166520179-064e3782-cc9b-4216-9f22-266fb32e07c7.png)

Each WebWorker runs independently and calculates its part of the image:

![grafik](https://user-images.githubusercontent.com/101653815/166520507-f736dbaa-d77a-4a79-b451-07561dd51e58.png)

By using WebWorkers, our analysis showed that the time to calculate RayTracing images can be reduced by up to 70-80% on Mobile phones and PCs.
