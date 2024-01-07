# Polyp-Segmentation
Polyp segmentation using U-Net in Tensorflow 2.0 using the CVC-ClinicDB (CVC-612) dataset. 

## How to implement this project
1. Clone this repository.
```sh
   $ git clone https://github.com/noeliamunozgarcia/Polyp-Segmentation.git
``` 
2. Navigate to the directory containing this `README` in a terminal.
```sh
    $ cd YOUR_PATH/ISIC-2019-v2/
``` 
3. Download the dataset from  <a href="https://www.dropbox.com/s/p5qe9eotetjnbmq/CVC-ClinicDB.rar?dl=0"> here </a>.
4. Copy the images from the "Ground Truth" folder to the /CVC-612/masks directory.
5. Copy the images from the "Original" folder to the /CVC-612/images directory.
6. Run de data, model and train files.
7. Run de predict file.
8. The resulting segmented images can be found in the "results" folder.





