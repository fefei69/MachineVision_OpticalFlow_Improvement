# Gunnar Farneback Optical Flow Improvement
This is the final project of Machine Vision course in NSYSU.
I designed a new pipeline to improve Gunnar Farneback optical flow by applying GMM to subtract the background of the input image. 
Without the background or the uninterested region in the frame, the Gunnar Farneback Optical Flow can focus exclusively on the moving obejcets. Therefore, the optical flow seemed to be accurate than before.
![improved_OF](https://user-images.githubusercontent.com/69750888/207836281-313420ee-106b-4af0-b8e5-473fd4f65fdc.PNG)

# Use GMM to subtract background
![GMM](https://github.com/fefei69/MachineVision_OpticalFlow_Improvement/assets/69750888/55c27b5f-0eba-4e2a-b773-74fceacc92cb)

# Results Comparisons 
![opticalflow_compare_tvl1_car](https://github.com/fefei69/MachineVision_OpticalFlow_Improvement/assets/69750888/449a2a49-aa20-4aeb-85cd-679c806919fd)
![opticalflow_compare_TVL1](https://github.com/fefei69/MachineVision_OpticalFlow_Improvement/assets/69750888/5601638e-25be-42b2-946f-57ab4e00619f)