# Under-Water-Image-Compression-using-VQ-Vaes

- This repository contains the implementation of a deep VQ Vae model which was trained for 75 epochs on the Underwater LSUI Under Water Image Dataset.
-  Acheived a compression ratio of 139:1 all the while retaining visual quality.
- Uses a preprocessing pipeline consisting of color balancing, CLAHE-based contrast enhancement, and gamma correction to reduce underwater color cast, improve visibility, and highlight fine details.
- Incorporated a combined Perceptual + MSE loss, where perceptual loss leverages selected layers of a pretrained VGG19 network to capture feature-level differences to improve the reconstruction.


# VQ-VAES Results : 
groundtruth vs. generated(reconstructed)

<img width="999" height="332" alt="Screenshot 2025-09-06 at 10 46 30 PM" src="https://github.com/user-attachments/assets/0ef3d5a3-d4b6-43ed-a465-3737e47d0287" />
<img width="1000" height="331" alt="Screenshot 2025-09-06 at 10 46 50 PM" src="https://github.com/user-attachments/assets/c8543f2a-8f7a-4300-b902-b5266d0d97db" />
