# Summary Agendas Meeting - 19 Sep 2023
*************************
Progress:

1. Set up and connect hardware [Done]
2. Install Ubuntu Desktop 22 [Done]
3. Network Configuration: *Able to connect to the internet [Done]
4. Able to remote access [via Teamviewer or SSH] [Done]

*************************
Planning next steps [In progress]:

1. Set up a Git repository and invite every member to join.
2. Install Docker.
3. k3s Kubernetes installation (1 node) + Rancher for GUI.
4. Install Docker Desktop to try running containerized services.
5. Initial DoS testing? [Need to discuss scenarios for experiment setup.]
6. Study Calico and its implementation: an open-source networking and network security solution for containers, commonly used in Kubernetes clusters to provide networking capabilities. [*Not sure about technical details or setup yet, but it seems to be a popular tool in K8S :)]

*************************
Discussions:

BENG Students' Literature Reviews:

1. DoS attack scenarios experiment for our BENG students:

1.1 LDoS: Low-rate DoS attack sent at a rate lower than what would typically trigger immediate alarms or detection.

1.2 "ANCIBLE" to deploy our program for the experiment to create repeatable DoS attack scenarios.

1.3 For our research, we need to focus on the specific layers targeted in a DoS attack, which typically include the network layer, transport layer, and application layer. Understanding and analyzing the impact of DoS attacks on these layers will be crucial for our study.

1.4 Implementing a honeypot for anomaly detection of DoS attacks.

1.5 Achieving real-time DoS detection using Machine Learning (Random Forest in this paper): Preprocess the data by dividing it into 70% for training and 30% for validation. The claim of achieving 99.6% accuracy will require careful feature selection, appropriate data preprocessing (e.g., normalization, handling missing values), tuning hyperparameters of the Random Forest model, and ensuring a representative and balanced dataset.

1.6 Detecting and Mitigating Distributed Denial of Service (DDoS) Attacks on SDN-Based Machines: This paper proposes algorithms to detect and handle DDoS attacks using Software-Defined Networking (SDN) for effective mitigation. The algorithms outlined in the paper aim to enhance the security of SDN-based systems against DDoS attacks.