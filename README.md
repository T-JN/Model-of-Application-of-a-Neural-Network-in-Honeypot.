# Model-of-Application-of-a-Neural-Network-in-Honeypot.
The paper presents the results of calculations and tests of using machine learning methods to manage Honeypot. The Honeypot and the data circulating in it were managed on the basis of a generative-adversarial network. Accuracy, precision, recall, and specificity were chosen as evaluation parameters. To assess the quality of application of the generative-adversarial network, there was a criterion, the minimum discriminatory threshold (Fscore). 
    A Honeypot was deployed in a virtual environment based on the Hyper-V hypervisor. Modeling of various attacks (DGA attack, port scanning attack, brute-force attack of access details to an edge device, TCP/UDP SYN attack) was carried out and the behavior of a Honeypot during its management, a generative-adversarial network, was assessed. The generative adversarial network managing the decoy infrastructure was connected to an intrusion detection system with machine learning to improve the accuracy of Fscore determination and generate stochastic values for datasets circulating in the decoy infrastructure. The theoretical calculations and practical tests carried out prove the possibility of creating a Honeypot with minimal operator intervention.

The research was conducted in a software-defined network based on the Windows Server 2016 Standard operating network with the Hyper-V role installed (https://www.microsoft.com/en-us/evalcenter/download-windows-server-2016), 
OS Ubuntu 21.04 is chosen as the execution environment (https://ubuntu.com/download/desktop/thank-you?version=22.04&architecture=amd64). 
Software development was carried out in IDE CLion (https://www.jetbrains.com/help/clion/configuring-available-python-interpreters.html).
Malware Bazaar Database.  https://bazaar.abuse.ch/browse/
Malware database.    http://vxvault.net/ViriList.php
Malware repository.  https://avcaesar.malware.lu/
Viruses repository.  https://virusshare.com/ 


