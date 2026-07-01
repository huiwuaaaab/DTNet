## Dataset Information
All datasets used in this work are obtained directly from their official open-source repositories, including NWPU VHR-10 and DIOR remote sensing benchmarks.

### Data Download Channel
Due to the large data volume of original remote sensing images, we provide a Baidu Netdisk download link for researchers' convenience:
- Download Link: [Fill your Baidu Netdisk URL here]
- Extraction Code: [Fill your extraction code here]

### Dataset Description
1. **NWPU VHR-10 Dataset**
    - Official Source: Publicly released open remote sensing target detection benchmark
    - Main contents: High-resolution aerial remote sensing images with 10 common object categories
2. **DIOR Dataset**
    - Official Source: Public large-scale optical remote sensing detection dataset
    - Main contents: Diverse scene remote sensing images covering 20 object categories

### Supplementary Materials (Minimal Dataset)
The minimal dataset that supports all core experimental conclusions of this paper is provided in the above shared file, which includes:
- Primary processed data: Test set annotation files, model prediction outputs, quantitative mAP evaluation results
- Metadata: Category mapping table, evaluation metric calculation rules, image parameter descriptions
- Analysis & training code: Data preprocessing, model training, inference and evaluation scripts
- Supporting document: This README file for dataset structure interpretation

### Notes
1. All raw image copyrights belong to the original dataset publishers; this shared file is only for academic research reproduction.
2. If the link expires, you can acquire the complete raw dataset via the official repositories referenced in our paper.
3. Confidential or proprietary information has been completely removed from all shared data.

## Code Reproduction Guide
1. Configure the experimental environment according to the requirements in `requirements.txt`
2. Unzip the downloaded dataset files and modify the data path in the training script
3. Run `train.py` to reproduce the training process of our proposed detection model
4. Run `eval.py` to reproduce all quantitative comparison results in the manuscript
