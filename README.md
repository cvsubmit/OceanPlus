<<<<<<< HEAD
The code is provided for AAAI2021 double blind review.

### Install Environment
```
sh install.sh
```
-Note: all the results in the paper (including other methods) are performed with `vot-toolkit=0.2.0`.

### Install VOT workspace
please create workspace following the official [guidelines](https://www.votchallenge.net/howto/tutorial_python.html).


### Test
- Clone project
```
git clone https://github.com/cvsubmit/OceanPlus
```

- Download pretrained models

Download from [GoogleDrive](https://drive.google.com/drive/folders/1Z6gPsRcheK4ZPbxpAAM7OjyyeyKF7e4G?usp=sharing) and put them in `$tracker_path/snapshot`

- Modify scripts
Set the model path in line81 of `$tracker_path/tracking/vot_wrap.py` and `$tracker_path/tracking/vot_wrap_mms.py`.

- run

for model without MMS network:
```
set running script in vot2020 workspace (i.e. trackers.ini) to `vot_wrap.py`
```
for model with MMS network:
```
set running script in vot2020 workspace (i.e. trackers.ini) to `vot_wrap_mms.py`
```
We provided a reference of `trackers.ini` in `$tracker_path/trackers.ini`. Please find more running guidelines in VOT official [web](https://www.votchallenge.net/howto/tutorial_python.html).

The training code and testing scripts and hyper-parameters will be released after accepted. Thanks for your interest!
 
=======
# OceanPlus
Code for OceanPlus in AAAI blind review

The code will be uploaded asap.
>>>>>>> 9a25c675985f5cfe849c463072fa562823e549f1
