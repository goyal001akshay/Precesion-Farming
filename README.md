
# Precision Farming

## Application:
	Health-Smart Secure Farming (HSSF)
## Target Problem
### How to achieve “health-smart secure farming” such that the following 3 conditions can be satisfied:

#### Precise monitoring 
of the crop growing conditions, weather (temperature, humidity, etc.) and soil (moisture, pH, etc.) so that we can learn new “integrated crop growth models”

#### Detecting
 specific problems related to productive farming, including input/output wastage, pests and diseases, and controlling farming activities such that crops grow healthily.

#### Scalable 
control and distributed security must be ensured for food safety.


### The 3 problems that can solved by Health-Smart Secure Farm Management:

#### 1. Precise Farm Monitoring via IoT: 
The benefits that farmers get from IoT application in agriculture are twofold. First, these systems help farmers decrease production costs and waste by optimizing the use of inputs. In addition, IoT can increase yields by improving their decision-making with more and accurate data. (http://blogs.worldbank.org/ic4d/agriculture-20-how-internet-things-can-revolutionize-farming-sector)
Integrated Crop Growth Model Learning: Learning new crop growth models by monitoring climate, soil, farming activities (irrigation, adding fertilizers, and applying pesticides) and crop growing conditions. Heterogeneous data fusion among the above data types is performed in LPWAN gateways to learn new integrated crop growth models. For example, for grapes, spring frost frequently damages opening buds and young shoots, and in some regions early fall frost can defoliate vines before harvest. Thus, frost detection for grape growers is required to avoid crop wastage (ref. Quora).
#### 2. Model-Predictive Plant Health Control:

##### i. Plant pathology level identification (NTTU levels: 1-5)
##### ii. Health-conscious farming:
Precise watering: underwatering/overwatering exacerbate disease (root exudation: roots exposed to water-saturated soil for 18 hours, underwatering results in more susceptible to cankers)
Precise fertilizing: high levels of nitrogen fertilizers results in ammonia toxicity and exacerbate disease via pathogens such as Rhizoctonia, Pythium, Phytophthora, Fusarium, Armillaria, Sclerotium, Pseudomonas, Corynebacterium, powdery mildews, rusts, cyst nematodes and many others.
Use of biomedical pesticides (Taitung University)

#### 3. Food safety and distributed supply-chain security: 
HLF Blockchain design.




## References:

### Intigrating Kubernetes with hyperledger fabric
https://medium.com/wearetheledger/a-first-attempt-at-hyperledger-fabric-kubernetes-66e43b12a211
https://blog.alexellis.io/kubernetes-in-10-minutes/
https://medium.com/@SystemMining/setup-kubenetes-cluster-on-ubuntu-16-04-with-kubeadm-336f4061d929
https://hackernoon.com/how-to-deploy-hyperledger-fabric-on-kubernetes-1-a2ceb3ada078

### fabric chain code:
https://www.ibm.com/developerworks/cloud/library/cl-ibm-blockchain-chaincode-development-using-golang/index.html

### blockchain app
https://chainhero.io/2017/07/tutorial-build-blockchain-app/#build-a-docker-compose-file


### deploying hlf in kubernetes
https://hackernoon.com/how-to-deploy-hyperledger-fabric-on-kubernetes-1-a2ceb3ada078

### hlf sdk chainhero:
https://chainhero.io/2017/07/tutorial-build-blockchain-app/
        sdk for nodejs
          https://fabric-sdk-node.github.io/Client.html#createChannel

### How to setup and build Hyperledger Fabric Blockchain Applications
https://domsteil.com/2017/04/22/how-to-setup-hyperledger-fabric-v1-0-on-aws/

### udemy docker course
https://www.udemy.com/docker-for-developers/learn/v4/t/lecture/5456328?start=0

### chaincode from ibm blockchain
https://www.youtube.com/watch?v=rf6c5tcqvNE

### networking in containers
https://thenewstack.io/container-networking-breakdown-explanation-analysis/

### kubernetes clustering
https://builders.intel.com/docs/networkbuilders/multiple-network-interfaces-in-kubernetes-application-note.pdf

https://medium.com/google-cloud/understanding-kubernetes-networking-pods-7117dd28727

https://thenewstack.io/hackers-guide-kubernetes-networking/

### chaincode for tuna supply chain
https://github.com/hyperledger/education/blob/master/LFS171x/fabric-material/chaincode/tuna-app/tuna-chaincode.go


### ibm adding a new org in the network
https://www.ibm.com/developerworks/cloud/library/cl-add-an-organization-to-your-hyperledger-fabric-blockchain/index.html


#### Apart from project great cli tool for ubuntu:
https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb


