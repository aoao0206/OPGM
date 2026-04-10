# OPGM: Optical Property-Guided Spectral Line Screening Method for LIBS Analysis

## Spectral line selection code
This repository provides the implementation of the proposed Optical Property-Guided Spectral Line Screening Method (OPGM), which performs physics-constrained spectral line selection for LIBS data.

The method integrates:
- Wavelength-domain filtering (removal of molecular bands and laser interference)
- Peak detection
- Intensity and signal-to-noise ratio (SNR) filtering
- Self-absorption recognition
- Line broadening validation
- Sampling adequacy verification
- Cross-validation with the NIST atomic spectral database

## 📥 Code Download

The Spectral line selection method code:  
Link: https://pan.baidu.com/s/1MRAE5BGYMiBpDU97z1YWKw?pwd=hust  
Password: hust  



## Validation Data

This dataset is provided to evaluate the effectiveness and robustness of the proposed Optical Property-Guided Spectral Line Screening Method (OPGM) under different scenarios.

### 📊 Dataset Description
The data consist of raw LIBS spectra collected under various experimental conditions. Each spectrum is represented as high-dimensional wavelength–intensity pairs (typically covering 200–900 nm).

The original spectra contain approximately **10,000–40,000 variables**, which are reduced to a compact set of **~500 physically validated spectral lines** after applying the proposed screening method :contentReference[oaicite:0]{index=0}.

---

## 🔍 Two Validation Protocols

### 1️⃣ Cross-time validation
This protocol evaluates the robustness and generalization ability of the model under temporal variations in data acquisition.

The dataset is divided into:
- **Test 1**: Training and validation set  
- **Test 2**: Independent test set  
- **Test 3**: Independent test set  

Notes:
- Test 2 and Test 3 are not used during training  
- They are used to assess model performance under different acquisition times  


### 2️⃣ Cross-sample validation
This protocol evaluates the generalization capability of the method across different material systems and matrix conditions.

Two representative datasets are included:

#### (1) Polygonatum dataset
- Herbal material dataset  
- Similar elemental composition to goji berry but with different matrix properties  
- Used to evaluate robustness under **similar elements but different matrices**

#### (2) Coal dataset
- Highly heterogeneous material dataset  
- Contains complex compositions and strong matrix effects  
- Used to evaluate robustness under **complex and diverse material conditions**

Experimental results demonstrate that the proposed method maintains strong discriminative capability and stability across different sample types :contentReference[oaicite:1]{index=1}.

---

## 📦 Data Content

Each sample includes:
- Wavelength (nm)
- Intensity (a.u.)
- Class label (if applicable)

The dataset can be used for:
- Spectral line screening and feature selection
- Evaluation of physical reliability (SNR, self-absorption, broadening)
- Classification and regression tasks
- Generalization analysis (cross-time and cross-sample)

## 📥 Download

The augmented dataset:  
Link: https://pan.baidu.com/s/1s1d3Bal6BIMrH4AVMDCbog?pwd=LIBS
Password: LIBS  

