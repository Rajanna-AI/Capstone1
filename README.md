# Capstone1

## A Monocular Camera Depth Estimation Approximation using Deep learning

Data is simluated using focal length, vertical view angle, horizontal view angle and pixel density in both vertical and horizontal as shown below :

![image](https://user-images.githubusercontent.com/77930435/187906312-8d647b72-3d24-4580-a445-91abfebed582.png)

![image](https://user-images.githubusercontent.com/77930435/187906096-2ed4636f-733d-4abf-b33c-033b0d2f0873.png)

# Typical pixel to distnace relationship shown below:

![image](https://user-images.githubusercontent.com/77930435/187906631-377e0c1f-ba86-41b0-885f-64e827f99b58.png)

## Implementation

![image](https://user-images.githubusercontent.com/77930435/187906705-1f2e3129-447b-4faa-b9e6-774507aaca0a.png)

# Test and validation result

	            MAE	           RMSE
	       Train	Test	   Train	Test
Model 1	2.0245	1.8609	2.6184	2.4958
Model 2	0.5060	0.5226	0.6550	0.6694
Model 3	0.1605	0.1675	0.2327	0.2494
Model 4	0.0623	0.0630	0.0837	0.0839

# Conclusion

Model 1 is taken as baseline model and all other models are compared with baseline model. It can be observed that model 2, MAE/RMSE is 75% less than baseline model. Similarly additional layers and neurons will reduce this to almost zero in model 4, but the cost of building the complex model is very high. Hence, we recommend model 2 for less critical applications like the one that has been tested.
