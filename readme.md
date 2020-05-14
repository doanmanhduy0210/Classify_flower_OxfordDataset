Create virtualenv invironment. 

https://docs.python-guide.org/dev/virtualenvs/

follow comanline: 

virtualenv -p python3 env_flower

source env_flower/bin/activate

!pip install -r requiment.txt

dataset download here: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/

classification 102 classes. 

classify flower and not flower

search similarity problems. 

reference: https://engineering.fb.com/data-infrastructure/faiss-a-library-for-efficient-similarity-search/


using CNN Model. 

augmentation with albumentation: https://github.com/albumentations-team/albumentations

imgaug: https://imgaug.readthedocs.io/en/latest/ 

github: https://github.com/doanmanhduy0210/Imgaug_albumentation_Data


### + how push large file storage to github ?   vấn đề khi dùng Github. 
large file storage github . 

okey lets solve it. 

just search follow link : https://packagecloud.io/github/git-lfs/install 

git lfs install

git lfs track "file_name"

git add .gitattributes

git add file_name 

git commit -m "Add design file"

git push origin master


