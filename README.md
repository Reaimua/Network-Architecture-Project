# Network Architecture Diagram

## Overview
This Diagram was created in the attempt to gain a deeper understanding of the importance, use cases and overall structure of 2 and 3-tier network architectures. This project was done as the second part of the [6 Month Cloud Study Plan](https://www.madebygps.com/cloudcamp/) and serves as another step towards gaining valuable skills towards understanding and implementing cloud technologies. 

## 3-Tier Architecture
The 3-Tier Network Architecture comprises three distinct layers to establish a seamless connection for end users to the internet. This well-structured configuration encompasses the **Access, Distribution, and Core Layers**, each playing a vital role in ensuring efficient and reliable network functionality.
### Access Layer <a name="access-layer"></a>
The access layer serves as the initial point of connection for end-user devices. It acts as the gateway, facilitating integration of devices such as computers, smartphones, and other endpoints into the broader network infrastructure. The main focus of the access layer is to provide connectivity for users to access and interact with the rest of the network. 
### Distribution Layer
The distribution layer functions as the middleman between the access and core layers. It is responsible for managing and directing network traffic across the core layers and optimizing communication between various parts of the network. Typically this includes enhancement of network security through VLAN segmentation and improved resiliance through redundancy mechanisms. 
### Core Layer 
The core layer, is designed for high-speed and data transport between different distribution layers and across the entire network. It's main goal is to promote rapid and reliable communication. The core layer operates as a backbone, handling the bulk of network traffic while prioritizing speed. Redundancy and fault tolerance are critical to maintain continuous operation, and its design focuses on optimizing throughput and minimizing latency for complex and resilient networks.

### Advantages
- **Scalability**: Independent scaling of access, distribution, and core layers allows for more efficient resource allocation and better scalability to handle increasing network demands.
- **Modularity**: Clear separation into access, distribution, and core layers promotes modularity, making it easier to manage and update each layer independently.
- **Improved Performance and Redundancy**: Enhanced performance through efficient load balancing and improved redundancy. The distribution layer helps optimize traffic and reduce the risk of network failures.
- **Security**: Better security through segmentation and control at the distribution layer. VLANs and access controls can be implemented for improved network security.
  
### Disadvantages
- **Increased Complexity**: The additional layer introduces more complexity to the network design, requiring careful planning and configuration.
- **Higher Cost**: Implementing and maintaining three layers can be more expensive in terms of both hardware and management costs.
- **Latency**: The distribution layer may introduce some latency due to the need for traffic to pass through an intermediary layer.
- **Maintenance Challenges**: The increased modularity can lead to more challenging maintenance, especially if updates or changes are required across multiple layers.

## 2-Tier Architecture
The 2-Tier Network Architecture simplifies network design by using 2 essential layers: the Access Layer and the Collapsed Core Layer. This streamlined configuration aims to establish a direct and efficient connection for end users to the internet. The Access Layer facilitates user connectivity, while the Collapsed Core Layer handles the backbone of network traffic, optimizing performance and reliability.
### Access Layer
- Access Layer <a name="access-layer"></a>
- [See Above](#access-layer)
- 

### Collapsed Core Layer
-
### Advantages
-
### Disadvantages
-

# Considerations
- 
- d
- d
- d
- d
  
