# Timeseries Analysis

## Download file on SageMaker Studio Notebook
1. Choose **File** tab on the top panel and go to **New**. Select **Termial**.

<img width="715" alt="start-terminal" src="https://user-images.githubusercontent.com/22031262/119379608-a91c9280-bcfa-11eb-81d8-4d25ebe84fef.png">

2. Copy following command and run on terminal. You get **timeseries-analysis** folder.

```
git clone https://github.com/jjk-dev/timeseries-analysis
```
![clone](https://user-images.githubusercontent.com/22031262/119379808-e54ff300-bcfa-11eb-9210-e5e8db00e4fb.png)

3. Select **tensorflow 2.x CPU Optimize** kernel.

![kernel](https://user-images.githubusercontent.com/22031262/119380138-48da2080-bcfb-11eb-998d-f1786fa2d2c5.png)

## Make some changes
1. Change kernel to **tensorflow 2.x GPU Optimize**. And compare the speed between CPU Optimized and GPU Optimized.
2. Make more accurate model
   - Change parameters
   - Add more layers
   - Change model
