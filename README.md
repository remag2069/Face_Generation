# Face_Generation
Generating new faces with neural nets, specifically using a feed forwards neural network. This program acts as a standalone decompressor, while my previous project [Face_recognition](https://github.com/remag2069/Face-recognition) (might be private) acts as a standalone compressor. so the training was done combining these two models. A face was fed to compressor, it gave a 128 size encodding as output, the decompressor got the encodding as input and is expected to regenerate the face. After training, giving the decompressor random 128 vectors would generate random faces. Here, the 128 vectors were arranged in order of correlation and the 10 least corelated features were selected for user interface.  


## Face reconstruction

![image](https://user-images.githubusercontent.com/51650745/131207765-9496f87e-54cd-4acf-82f7-ff360634b74f.png)  



## New faces

**ABOMINATIONS ALERT!!!!!**  
1. Face 1:  
  (0.0, 0.0, 0.45, 0.15, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0)  
  ![image](https://user-images.githubusercontent.com/51650745/131207881-6b40c947-e843-4dce-9894-302435bedd6f.png)

2. Face 2:  
  (0.0, 0.0, 0.45, 0.15, 0.0, 0.0, 0.0, 0.0, 0.0, -0.35)  
  ![image](https://user-images.githubusercontent.com/51650745/131207421-d8d451f5-6739-46c4-ba58-a16f56937db0.png)

3. Face 3:  
  (0.0, 0.0, 0.45, 0.15, 0.0, 0.0, 0.0, 0.0, 0.0, 0.55)  
  ![image](https://user-images.githubusercontent.com/51650745/131207463-c2abef4f-d665-4129-9be0-db605a757dd6.png)

4. Face 4:  
  (0.0, 0.0, 0.45, 0.15, 0.0, -0.4, 0.3, 0.0, 0.0, 0.55)  
  ![image](https://user-images.githubusercontent.com/51650745/131207502-c39b0c4f-23a5-4b9b-9f9f-48dbac3d2bcf.png)


5. Face 5:  
  (0.85, -0.4, 0.45, 0.15, 0.35, -0.4, 0.3, -0.5, -0.4, 0.55)  
  ![image](https://user-images.githubusercontent.com/51650745/131207535-2f2900c8-3e2b-4538-99f3-12d4b56b6923.png)

