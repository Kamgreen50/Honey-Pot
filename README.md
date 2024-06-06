# Honeypot Deployment On Azure Cloud Platform
Deploy and configure a honeypot on the Azure cloud platform 
## Introduction

As a cybersecurity specialist, I know the need for techniques such as honeypots to track down and stay alert to potential threats. Honeytrap schemes detect and learn about the attack tactics, procedures, and engines (TTPs) of malicious threat actors by using discrete, hard-supervised computer resources or network endpoints that attract them. One of the many advantages of a honeypot is that it can help create a channel for understanding the threat environment, reduce the time required to resolve events and improve network security. In this tutorial, I have covered the utilization of the honey pot concept, a key component of the Azure cloud platform. By strategically placing honeypots, they can improve their defensive stance by obtaining comprehensive intelligence about these dangers. The manual clearly and practically covers the fundamentals of starting the honeypots and the essential functions of the Azure environment. As threats become more sophisticated, cybersecurity experts are advised to choose services for optimal performance, network configurations, and monitoring to create more robust defences to fend off new threats. This tutorial aims to provide the information and skills needed to set up and maintain different types of honeypots on Azure and quickly respond to cyberattacks, strengthening their defences against online threats.

### Prerequisites

These are the requirements;
- An Azure account with a valid subscription.
- Azure login credentials.
- Putty installed on your local machine.
 <br>
 
I'll set up an Azure virtual machine (VM) that will be the foundation for hosting the honeypots and thwarting intruders. Putty will allow remote access to the virtual machine and activate its features. I will set up and deploy the honeypot on the Azure cloud platform.

## Deployment Phase

During the setup phase, I'll use virtual machines to construct cloud computing systems on Microsoft Azure. After logging in to the Azure portal, I'll select a virtual machine image and size from the Azure Marketplace that is good with me and configure it. To strengthen the network structure of the virtual machines, I'll set up a networking topology of VNETs, subnets, and network security groups. After making the final selection, I will build the virtual machines (VMs) and verify their connectivity to ensure they can easily maintain the connection to the Azure environment.

<br>

To Create a Virtual Machine and Configure it, I'll follow the steps below;
- Log in to the Azure Portal.
- Create a new virtual machine.
- Choose an appropriate image and size.
- Configure the basic settings, including VM name, region, and authentication type.
<br>

![honeyport-1](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/386dae55-3985-4c2c-a3ab-cd2029b7946b)




### Network Configuration
- Set up VNETs, subnets, and network security groups.
- Configure inbound and outbound security rules.
<br>

![honeyport-2](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/b8a172c6-022f-46f9-86e1-0b6e092e6939)



## Installation and Configuration Phase

Now, I will deploy and modify the virtual machine into a fully functional honeypot. This involves creating decoy programs that mimic real systems, functioning as honeypots or imitating vulnerabilities to detect, identify, or mitigate intrusions. Additionally, I will set up and fine-tune logging and monitoring tools, which are crucial for identifying and analyzing threats. These tools will help register and sort harmful activities in the honeypot. I will also support identifying weak points and simulating actual assaults as part of our fundamental security measures, eventually enabling ethical hackers to eavesdrop.

### Install Putty

I have installed Putty on my Kali machine to enable remote access to the honeypot instance on the Azure platform. This allows me to efficiently monitor and control the honeypot environment from my Kali system.
<br>

![honeyport-3](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/7045dcdc-1e98-4068-81f6-822608a26928)
![honeyport-4](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/4680a0f4-c66a-4645-a383-4e70b1200b5c)


### Access the Virtual Machine

I connect to the server using Putty by navigating to its IP address. I use the same credentials generated while setting up the virtual machine. After logging in, I start configuring and overseeing the virtual machine instance.
<br>

![honeyport-6](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/2a607f85-beb2-4dca-b7f4-30524d2542f4)



### Install Necessary Tools
Install the necessary tools required for a functional honeypot.

```bash
sudo apt update
sudo apt upgrade -y
sudo git clone https://github.com/telekom-security/tpotce
sudo cd tpotce/iso/installer/
sudo ./install.sh --type=user
```
<br>

![honeyport-7](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/6c17cf8f-313b-4439-8ccc-44ad4922b601)
![honeyport-8](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/eff623e1-6bc4-4de1-bfb1-27b57727caa6)



## Testing and Validation Phase

I must undergo several procedures when testing and evaluating my honeypot device to determine its strength and viability. I aim to ensure that the honeypot will subsequently integrate with the Azure environment. I will first examine the network settings to avoid hiccups between the honeypots and other devices on the same network. After that, I ensure all the equipment and units can identify attacks and react quickly to honeypots, which greatly aid in creating security regulations. To test the detection and reaction capabilities of my honeypot, I also conduct assault scenario drills. This gives me techniques to consider cyberattacks' dangers and assess the honeypot's effectiveness under different assault scenarios. To ensure it works properly, it's crucial to test the honeypot thoroughly. This technology can only secure other organizational resources or cyber assets.

### HoneyPot web interface
I will set up a web interface like Kibana to manage and monitor the honeypot.

<br>

![honeypot-9](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/048316cf-c4fa-4adc-9caa-ecae43965a35)
![honeypot-10](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/93d1374c-325f-432e-92cb-707243a958f5)
![honeypot-13](https://github.com/Kamgreen50/Honey-Pot/assets/148400787/c572b285-eb86-43ee-8996-29bd03ba03a4)

## Conclusion

The honeypot's deployment in Azure has yielded various insights and implications for defence systems in cyberspace. Research findings will be produced, including information on the tools and techniques used by an attacker, the viability of security precautions, and threat intelligence. Cyber honeypots are a useful tool that can be used to detect threats before they become urgent and to improve incident response teams' readiness. 

### HappyLearning
