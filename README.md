# Polyp-Segmentation
Polyp segmentation using U-Net in Tensorflow 2.0 using the CVC-ClinicDB (CVC-612) dataset. 

## How to implement this project
1. Clone this repository.
```sh
   $ git clone https://github.com/noeliamunozgarcia/Polyp-Segmentation.git
``` 
2. Navigate to the directory containing this `README` in a terminal.
```sh
    $ cd YOUR_PATH/Polyp-Segmentation/
``` 
3. Download the dataset from  <a href="https://www.dropbox.com/s/p5qe9eotetjnbmq/CVC-ClinicDB.rar?dl=0"> here </a>.
4. Copy the images from the "Ground Truth" folder to [/CVC-612/masks/](/CVC-612/masks/). <br/>
6. Copy the images from the "Original" folder to [/CVC-612/images/](/CVC-612/images/). <br/>
7. Run de data, model and train files.
8. Run de predict file.
9. The resulting segmented images can be found in the "results" folder.





