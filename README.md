# FeDNet-BSPC
Official code for **FeDNet: Feature Decoupled Network for Polyp Segmentation from Endoscopy Images** Submitted to BSPC

Code is coming soon if paper is accepted.





## Prediction Result
The prediction result is place at [here](https://github.com/suyanzhou626/FeDNet-BSPC/tree/main/predcit_map). Everyone can compared it with other methods.




## Visualization
![result](https://github.com/suyanzhou626/FeDNet-BSPC/blob/main/figs/visualize_predictions.png?raw=true)





## Learning ablilty


| model                               | publish   |     CVC-ClinicDB     |                      |                     |                      |                      |                     |        Kvasir        |                      |                      |                      |                     |                     |
|-------------------------------------|-----------|:--------------------:|:--------------------:|:-------------------:|:--------------------:|:--------------------:|:-------------------:|:--------------------:|:--------------------:|:--------------------:|:--------------------:|:-------------------:|:-------------------:|
|                      |           |         mDice        |         mIoU         |     $F^w_\beta$     |      $S_\alpha$      |    $E_\phi^{mean}$   |         MAE         |         mDice        |         mIoU         |      $F^w_\beta$     |      $S_\alpha$      |   $E_\phi^{mean}$   |         MAE         |
| UNet         | MICCAI'15 |         0.823        |         0.755        |        0.811        |         0.889        |         0.954        |        0.019        |         0.818        |         0.746        |         0.794        |         0.858        |        0.893        |        0.055        |
| UNet++        | TMI'19    |         0.794        |         0.729        |        0.785        |         0.873        |         0.931        |        0.022        |         0.821        |         0.743        |         0.808        |         0.862        |        0.910        |        0.048        |
| ResUNet++    | JBHI'21   |         0.846        |         0.786        |        0.840        |         0.891        |         0.939        |        0.014        |         0.807        |         0.727        |         0.777        |         0.840        |        0.882        |        0.052        |
| SFA         | MICCAI'19 |         0.700        |         0.607        |        0.647        |         0.793        |         0.885        |        0.042        |         0.723        |         0.611        |         0.670        |         0.782        |        0.849        |        0.075        |
| PraNet          | MICCAI'19 |         0.899        |         0.849        |        0.896        |         0.936        |  0.979 |        0.009        |         0.898        |         0.840        |         0.885        |         0.915        |        0.948        |        0.030        |
| ACSNet      | MICCAI'20 |         0.908        |         0.857        |        0.903        |         0.934        |         0.964        |        0.012        |         0.906        |         0.849        |         0.892        |         0.914        |        0.950        |        0.026        |
| HarDNet-MSEG | Arxiv'21  |         0.902        |         0.856        |        0.904        |         0.927        |         0.961        |        0.009        |         0.905        |         0.855        |         0.901        |         0.914        |        0.947        |        0.025        |
| EU-Net     | CRV'21    |         0.902        |         0.846        |        0.891        |         0.936        |         0.959        |        0.011        |         0.908        |         0.854        |         0.893        |         0.917        |        0.951        |        0.028        |
| CaraNet               | SPIE'21   |         0.921        |         0.876        |        0.921        |         0.939        |         0.976        |        0.008        |         0.913        |         0.859        |         0.904        |         0.919        | 0.956 |        0.025        |
| SANet          | MICCAI'21 |         0.916        |         0.859        |        0.909        |         0.940        |         0.972        |        0.012        |         0.904        |         0.847        |         0.892        |         0.915        |        0.949        |        0.028        |
| MSNet       | MICCAI'21 |         0.915        |         0.866        |        0.911        |         0.947        |         0.970        |        0.008        |         0.902        |         0.847        |         0.891        |         0.923        |        0.945        |        0.029        |
| UACANet-S      | MM'21     |         0.916        |         0.870        |        0.917        |         0.940        |         0.965        |        0.008        |         0.905        |         0.852        |         0.897        |         0.914        |        0.948        |        0.026        |
| UACANet-L      | MM'21     | 0.926 | 0.880 | 0.928 |         0.943        |         0.974        | 0.006 |         0.912        |         0.859        |         0.902        |         0.917        |        0.955        |        0.025        |
| Polyp-PVT    | Arxiv'22  |  0.937 |  0.889 | 0.936 |  0.949 |  0.985 | 0.006 | 0.917 | 0.864 |  0.911 | 0.925 | 0.956 | 0.023 |
| baseline                            |           |         0.921        |         0.875        |        0.920        | 0.947 |         0.969        | 0.007 | 0.915 |  0.866 | 0.910 |  0.930 |  0.885 | 0.928 |  0.950 | 0.978 | 0.007 |  0.924 |  0.876 |  0.918  |  0.933  |  0.963 |  0.021 |







## Thanks to the repo
+ [PraNet](https://github.com/DengPingFan/PraNet/blob/master/lib/PraNet_Res2Net.py)
+ [UACANet](https://github.com/plemeri/UACANet) (especially, python version evaluation toolbox.)
