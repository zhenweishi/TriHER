# Triple-class HER2 expression (TriHER)

This repository supports the research study "MRI-based Deep Learning Model for Triple-class HER2 Expression Classification in Breast Cancer: A Large-scale Multicenter Study." To safeguard the study's intellectual property during the peer review process, we have elected to defer publication of the analysis code and trained models until the manuscript completes journal review. For inquiries regarding this work, please feel free to contact our team.


# Welcome to TriHER

Accurate assessment of Human epidermal growth factor receptor 2 (HER2) expression is crucial for guiding treatment strategies in breast cancer, especially with the advent of trastuzumab deruxtecan targeting HER2-low patients. Current clinical methods rely on invasive biopsy and immunohistochemistry (IHC), which are limited by sampling bias and interobserver variability. Here, we present a novel machine learning framework that integrates a pretrained foundation model with a classifier to non-invasively predict HER2 expression categories (HER2-zero, HER2-low, HER2-positive) from dynamic contrast-enhanced magnetic resonance imaging (DCE-MRI).This scalable and reproducible approach offers a promising alternative to traditional methods, enabling more precise treatment stratification and advancing the clinical utility of artificial intelligence (AI) in breast cancer care.

## Clinical workflow
Current clinical guidelines classify HER2 status into binary categories based on immunohistochemistry (IHC) analysis and fluorescence in situ hybridization (FISH): HER2-positive (IHC 3+ or IHC 2+ with FISH amplification) and HER2-negative (IHC 0/1+ or IHC 2+ without FISH amplification). However, emerging evidence indicates that up to 60% of HER2-negative cases exhibit low HER2 expression (HER2-low, defined as IHC 1+ or 2+ without FISH amplification), which remains undetected under the traditional binary framework.Here, we propose a novel framework that integrates a pretrained foundation model with a machine learning classifier to predict triple-class HER2 expression (hereafter TriHER) from DCE-MRI data.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c3f41e65-bbc9-4d4e-8858-7bc27fa9359b" width="1000" height="230">
</p>

## Clinical Application

We highlight four representative cases to illustrate TriHER’s ability to differentiate subtle imaging features associated with HER2 expression. In each group (Patients A and B, Patients C and D), patients exhibited identical clinicopathological characteristics and were concordantly categorized as HER2-negative under the conventional binary HER2 classification. However, TriHER successfully discriminated HER2-zero by diverse subtle imaging patterns, thereby enabling precision stratification for T-DXd therapy eligibility.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad221e53-dd06-4b71-8925-efedfdc466fb" width="1000" height="720">
</p>


## Main Developers
 - [Dr. Zhenwei Shi](https://github.com/zhenweishi) <sup/>1, 2
 - MSc. Zhitao Wei <sup/>1, 2
 - MD. Chiting Wong <sup/>1, 2
 - [Dr. Chu Han](https://chuhan89.com) <sup/>1, 2
 - MD. Changhong Liang <sup/>1, 2
 - MD. Zaiyi Liu <sup/>1, 2

<sup>1</sup> Department of Radiology, Guangdong Provincial People's Hospital (Guangdong Academy of Medical Sciences), Southern Medical University, China <br/>
<sup>2</sup> Guangdong Provincial Key Laboratory of Artificial Intelligence in Medical Image Analysis and Application, China <br/>


## Contact

📧 For collaboration inquiries: [Contact Email](shizhenwei@gdph.org.cn)

