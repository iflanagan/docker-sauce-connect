 
Pre-requisites:

install docker 

pull down this repo

build image 

docker build -t .

make note of the image ID:

run the image 

docker run -it iflanagan/sctunnels:firsttag <SAUCEUSERNAME> <SAUCEACCESSKEY> <Web/HEADLESS/RDCEU/RDCUS> <TunnelId>
