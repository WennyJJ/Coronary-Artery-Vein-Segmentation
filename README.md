# Coronary-Artery-Vein-Segmentation
These are the official prediction results of the AVDNet on the ASOCA dataset for follow-up research. <br>
ASOCA: Automated Segmentation of Coronary Artery Challenge (The original data can be obtained from https://asoca.grand-challenge.org) <br>
*******************
The original paper **"AVDNet: Joint Coronary Artery and Vein Segmentation with Topological Consistency"** is the first study to segment coronary artery and vein vessels simultaneously from the CCTA images. Please check https://www.sciencedirect.com/science/article/abs/pii/S1361841523002591 for detailed ideas. <br>
![asoca](./images/overview.png) <br>
*******************
In [AVDNet_ASOCA_pred](./AVDNet_ASOCA_pred), predictions of 40 training cases in ASOCA are produced by the AVDNet. There are more details of the arteries in the inference results from AVDNet than in the ASOCA annotations, and the veins are also provided. <br>
![asoca](./images/asoca.png) <br>
## Reference
If you find AVDNet and its predictions helpful, please consider citing the following paper:<br>
`@article{wang2023avdnet,` <br>
  `title={AVDNet: Joint coronary artery and vein segmentation with topological consistency},` <br>
  `author={Wang, Wenji and Xia, Qing and Yan, Zhennan and Hu, Zhiqiang and Chen, Yinan and Zheng, Wen and Wang, Xiao and Nie, Shaoping and Metaxas, Dimitris and Zhang, Shaoting},` <br>
  `journal={Medical Image Analysis},` <br>
  `pages={102999},` <br>
  `year={2023},` <br>
  `publisher={Elsevier}` <br>
`}`
