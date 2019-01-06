This is a pretrained model for the Pix2Pix written by [Jun-Yan Zhu](https://github.com/junyanz)

![Results from the Pretrained Model](Pix2Pix_Result.jpg)

Due to the file size limit of GitHub, the pretrained model is provided in a Deopbox [link](https://www.dropbox.com/s/w1netgcq7qkir74/checkpoints.zip?dl=0).

Clone the model provided by Jun-Yan Zhu.
Clone the sample dataset and pretrrained model on this page.
Then generate the results using
```bash
python test.py --dataroot ./datasets/architect_shader/ --direction BtoA --model pix2pix --name architect_shader
```
