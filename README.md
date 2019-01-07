# fast-ai-aws-advanced


{
   "Type":"AWS::EC2::VolumeAttachment",
   "Properties" : {
      "Device" : String,
      "InstanceId" : String,
      "VolumeId" : String
   }
}

Launch normal ami via spot 




Attach using attach_data_layer

sudo chown ubuntu:ubuntu -R /home/ubuntu/src
rm -rf /home/ubuntu/data /home/ubuntu/fastai /home/ubuntu/src
sudo mkdir /work
sudo chown ubuntu:ubuntu /work
sudo mount /dev/xvdh /work
ln -s /work/fastai /home/ubuntu/fastai
ln -s /work/src /home/ubuntu/src
ln -s /work/data /home/ubuntu/data