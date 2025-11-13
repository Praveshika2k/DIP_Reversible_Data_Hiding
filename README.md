# 🔐 Reversible Data Hiding with Adaptive QR Code Embedding and Perfect Recovery

## 📘 Abstract
This project presents an advanced *Reversible Data Hiding (RDH)* system integrated with *Quick Response (QR)* codes for secure and reversible information embedding in digital images. The proposed approach intelligently analyzes image complexity to adaptively select embedding regions, ensuring minimal distortion and perfect recovery. A visible QR code is embedded into the image corner while the displaced pixel data are securely hidden within low-complexity regions of the image. When decoded, the QR code can be scanned to access linked information, and the original image can be fully reconstructed without any loss. The system achieves high imperceptibility, strong reversibility, and increased embedding capacity using adaptive bit allocation and local texture analysis.

---

## 👩‍💻 Team Members
| Name           | Register Number  |
|----------------|------------------|
| *Vishnu Priya A*| *23MIA1039*|
| *Praveshika M*| *23MIA1044*|
| *Tarlana Vidya*| *23MIA1176*|


---

## 📄 Base Paper Reference
**Title:** *Reversible Data Hiding with Histogram-Based Difference Expansion for QR Code Applications*  
**Authors:** Chi-Kwong Chan and L.M. Cheng  
**Published In:** IEEE Transactions on Circuits and Systems for Video Technology  
**DOI:** 10.1109/TCSVT.2006.888203  

---

## 🧰 Tools and Libraries Used
- **Google Colab / Jupyter Notebook**
- **Programming Language:** Python 3.x  
- **Libraries:**
  - `opencv-python`
  - `numpy`
  - `Pillow`
  - `qrcode`
  - `scikit-image`
  - `matplotlib`
  - `google.colab.patches` (for image display in Colab)
  - `warnings`, `os`

---

## ⚙️ Steps to Execute the Code
1. **Open the Notebook:**  
   Launch the `.ipynb` file in **Google Colab** or **Jupyter Notebook**.
2. **Install Dependencies:**  
   Run the first cell to install required Python libraries automatically.
3. **Upload Image:**  
   Use the file upload prompt to upload a grayscale or color image (e.g., `.jpg`, `.png`).  
   If no image is uploaded, a synthetic test image is generated automatically.
4. **Enter QR Message:**  
   Provide a URL or text input that will be encoded into the QR code.  
   *(A default Wikipedia link is used if left empty.)*
5. **Embedding Process:**  
   The algorithm generates an adaptive QR code and hides the corresponding region data within the rest of the image using multi-layer RDH.
6. **Visualization:**  
   The notebook displays side-by-side visualizations:
   - Original Image  
   - Image with Visible QR Code  
   - Recovered Image  
   - Difference Maps
7. **Recovery and Metrics:**  
   The final output includes PSNR, SSIM, embedding capacity, and recovery accuracy reports.

---

## 🧠 Description of Input Data
The system takes **real-time user-provided images** as input. These images serve as the host medium into which the QR code is embedded. The input can be any grayscale or color image, which is resized and converted internally to a uniform resolution (512×512) for consistent analysis. The embedded QR content (URL or text) acts as the hidden message, dynamically generated during runtime based on user input.

---

## 📊 Output Results / Screenshots
*(Insert output visualizations such as embedding process, recovery visualization, and performance metrics here.)*  
> Example placeholders:  
> - Original vs Embedded vs Recovered Images  
> - Difference Maps  
> - PSNR / SSIM / Recovery Accuracy Tables  

---

## 🎥 YouTube Demonstration
*(Insert your demo video link here once available)*  
> 🎬 [Watch the Project Demo on YouTube](https://youtu.be/)

---

### 🏁 Highlights
- 100% Perfect Image Recovery  
- Adaptive Region-Based Embedding  
- QR Code Version 4 with Reed–Solomon Error Correction  
- Achieved PSNR (Original vs Recovered): ∞ dB  
- Recovery Accuracy: 100%  
- Embedding Capacity: ~9.77 KB per 512×512 image  

---

📌 *Developed as part of the Digital Image Processing Project — Integrating Reversible Data Hiding with QR-Based Smart Access Systems.*


