# MDFIDNet: Multi-Domain Feature Integration Denoising Network

Welcome to the official repository for **MDFIDNet**, a novel image denoising model leveraging **Multi-Domain Feature Integration** to achieve superior denoising performance. 

---

## Abstract
In the realm of computer vision, image denoising remains a formidable challenge with profound implications for fields like medical imaging, remote sensing, and photography. Despite notable advancements in deep learning, there are enduring challenges: current convolutional neural networks (CNNs) frequently struggle with training complexities due to their emphasis on increased network depth. At the same time, these networks often fail to adequately consider the crucial role of gradient information in the denoising process. Furthermore, there is a distinct gap in leveraging transform domain analysis in image denoising. 

This study addresses these limitations with **MDFIDNet**, a novel triple-phase attentive fusion network tailored for image denoising. MDFIDNet integrates three independent feature extraction pipelines:
- A **Frequency Domain Processing Pipeline (FDP)** enhanced by a multi-scale convolutional attention block (MSCAB).
- A **Spatial Domain Processing Pipeline (SDP)** focusing on detail feature preservation.
- A **Gradient Domain Processing Pipeline (GDP)** driven by multidirectional gradient information.

Experimental validation demonstrates that MDFIDNet surpasses existing benchmarks, exhibiting robust performance across diverse datasets. Comprehensive ablation studies underscore the individual contributions of each network component, elucidating the novel advancements that underpin MDFIDNet’s superior denoising efficacy.  

The source code and further details are available in the repository.  
🔗 [https://github.com/debashis15/MDFIDNet](https://github.com/debashis15/MDFIDNet)  

**Keywords**: Computer vision · Deep Learning · Image denoising · Gradient information · Real images · Experimentation · Training Complexity

---

## Publication
This work has been **accepted at ICPR 2024** (International Conference on Pattern Recognition).  
The corresponding paper provides a comprehensive explanation of the architecture, methodology, and performance metrics.

---

## Code and Data
The **code** and **datasets** used in this study will be published very soon. Stay tuned for updates!

---

## Results and Metrics
If you require **results**, **metric values**, or additional details, feel free to reach out to the corresponding author:

- **Debashis Das**
  - Email 1: [ddebashisdas2108@gmail.com](mailto:ddebashisdas2108@gmail.com)
  - Email 2: [debashis_2221cs31@iitp.ac.in](mailto:debashis_2221cs31@iitp.ac.in)

---

## Citation
If you find this work helpful, please consider citing our paper:

@InProceedings{10.1007/978-3-031-78125-4_27,
  author="Das, Debashis and Maji, Suman Kumar",
  title="MDFIDNet: Multi-domain Feature Integration Denoising Network",
  booktitle="Pattern Recognition",
  year="2025",
  publisher="Springer Nature Switzerland",
  isbn="978-3-031-78125-4"
}


---

## Contact
For further queries, feedback, or collaborations, please contact **Debashis Das** using the emails provided above.

---
## Repo Structure
MDFIDNet/
├── datasets/               # Datasets used for training and evaluation
├── models/                 # Model architecture and implementation
├── utils/                  # Utility functions and helper scripts
├── experiments/            # Scripts for running experiments
├── results/                # Precomputed results and metrics
├── README.md               # This file
└── requirements.txt        # Python dependencies
Thank you for your interest in MDFIDNet!
