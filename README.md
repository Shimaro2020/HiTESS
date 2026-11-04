# HiTeSS_VAD
The code of Hierarchical Sequence Selection for Video Anomaly Detection with Weak Labels
## Datasets
The following datasets were used and extracted using the I3D pre-trained network
* UCF Crime Dataset (https://www.crcv.ucf.edu/projects/real-world/)
* XD Violence Dataset (https://roc-ng.github.io/XD-Violence/)
## I3D Weights (https://github.com/dlpbc/keras-kinetics-i3d/releases)
* **WEIGHTS_PATH:**
  * rgb_kinetics_only_weights
  * flow_kinetics_only_weights
  * rgb_imagenet_and_kinetics_weights
  * flow_imagenet_and_kinetics_weights
* **WEIGHTS_PATH_NO_TOP:**
  * rgb_kinetics_only_weights_no_top
  * flow_kinetics_only_weights_no_top
  * rgb_imagenet_and_kinetics_weights_no_top
  * flow_imagenet_and_kinetics_weights_no_top


## I3D Features
* i3d_net.py
* dataset_utility.py
* process_dataset.py

## Citation

```bibtex

@article{abiew2026hierarchical,
  title={Hierarchical temporal sequence segmentation for weakly supervised video anomaly detection},
  author={Abiew, Nuku Atta Kordzo and Gao, Lijian and Mao, Qirong},
  journal={Expert Systems with Applications},
  volume={295},
  pages={128753},
  year={2026},
  doi={10.1016/j.eswa.2025.128753}
  publisher={Elsevier}
}
```

---
## TODO
The code will be released soon, please wait!
