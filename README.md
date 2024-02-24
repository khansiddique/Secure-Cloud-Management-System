# Secure-Cloud-Management-System
Secure Cloud Management System for Machine Learning


The main goal of this internship project was to mitigate the man-in-the-middle (MITM)
attack [2, 3] problem during communication with the point-to-site (P2S) virtual private
network (VPN) connection between the on-premise host system(i.e. Windows 10 PC) to
Microsoft Azure cloud computing systems. As a countermeasure against MITM attacks,
using a VPN connection on public networks would add an extra layer of security [4] and
self-certified encryption protocols had been developed which seems to bring a good defense [5],
as shown in Figure 1.1. Furthermore, it was executed a machine learning (ML) algorithm
such as autoencoder [6] algorithm of ITPower Solutions GmbH[1] into the Azure data science
virtual machine (DSVM) [7] for deep learning to evaluate the P2S VPN connection.

![StateofTheArt drawio](https://github.com/khansiddique/Secure-Cloud-Management-System/assets/44813868/b117093d-0a06-4338-90c9-0e2aeb563946)

Figure 1.1: Avoiding MITM Attacks

Further, it is very important to tackle the threat agents who create a threat happening
internally or externally to the organization such as a trusted attacker, malicious insider, and
malicious program logic to compromise system [8]. Further, Deyan Chen et. al. argued
that the data life cycle [9] (i.e. from generation to destruction of the data) needs to be
all-around analysis concerning data security and privacy protections in the cloud, such as
data generation, transfer, use, share, and storage.

![Copy of Azure_second_topology drawio](https://github.com/khansiddique/Secure-Cloud-Management-System/assets/44813868/83663616-af25-4d58-9d9d-f663fa807094)

Figure C.1: Securing network topology for P2S connection from Windows 10 to Azure DSVM
and mount the Azure file share.
