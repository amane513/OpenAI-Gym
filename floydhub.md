### Install floydhub
pip install -U floyd-cli  
floyd login  

### Start floydhub
floyd init _directory name_   

### Execute on floydhub
$ floyd run \  
--gpu \  
--data mckay/datasets/mnist/1:mnist \  
--env tensorflow-1.3 \  
"python train.py"  

