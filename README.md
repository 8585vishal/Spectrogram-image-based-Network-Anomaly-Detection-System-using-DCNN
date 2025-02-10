A Spectrogram Image-Based Network Anomaly Detection System Using Deep Convolutional Neural Network
Networks are always vulnerable to attacks and there are many algorithm exists to detect and combat such attacks but still attackers may find way to intrude into networks and then perform malicious operations. To enhance detection rate author of this paper employing Deep CNN algorithm which utilizes Spectrogram images generated using the short-time Fourier transform from the Network Intrusion dataset called CIC-IDS2017. Propose algorithm is called as Spectrogram Deep CNN (SDCNN). Signals generated from Spectrogram FFT technique contains accurate information about network packets and this CNN will get trained on such packet features. This features helps CNN in detecting malicious packets accurately. Author has modified CNN algorithm with extra layers called MAXPOOLING2D, RELU Function and Dense which help CNN in collecting optimized features from the dataset. Propose SDCNN is designed as a Fully Connected CNN algorithm.
To train CNN we have collected CID_IDS dataset and then convert all those dataset values into Spectrogram images and this images get trained with various deep learning algorithms called GRU, LSTM, CNN1D and propose SDCNN and in all algorithms propose SDCNN is giving better accuracy. Each algorithm performance is evaluated in terms of accuracy, precision, recall, FSCORE and Confusion Matrix.
To train above algorithms we have used below dataset CIC dataset
![image](https://github.com/user-attachments/assets/9b25c78b-2d52-4c79-b6cf-6e6f65717499)
![image](https://github.com/user-attachments/assets/3328095f-9db2-4a57-9259-4dd1c9cfefc5)
![image](https://github.com/user-attachments/assets/66a1b37e-4bbb-4be7-b95a-525bb0a69214)
![image](https://github.com/user-attachments/assets/0d922866-fda9-4f10-a2a3-64c831718dee)
![image](https://github.com/user-attachments/assets/074bb755-da1a-4330-84ff-3f5da732cb25)
![image](https://github.com/user-attachments/assets/f047686d-f9a4-4ad0-9163-2e20295610ac)
In above graph x-axis represents algorithm names and y-axis represents accuracy and other metrics in different colour bars and in all algorithms propose SDCNN has got high performance and now click on ‘Predict Intrusion using Test Data’ button to upload test data and then predict intrusion and in below screen we are showing test packet data


