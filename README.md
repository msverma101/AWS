AWS tutorials


#creating a collection called trainer
$ aws rekongnition create-collection --collection-id trainer

#Here the image is being associated with a name in collection id
$ aws rekognition index-faces --collection-id trainer --image "S2Object={Bucket=hands-on-rekognition, Name= Jhon.jpeg}" --external-image-id John

$ aws rekognition start-face-search --job-id

amazonElasticTranscoder - for stiching videos
https://aws.amazon.com/blogs/machine-learning/automated-video-editing-with-you-as-the-star/
