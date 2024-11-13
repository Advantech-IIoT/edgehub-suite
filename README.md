# Edgehub Suite

This repository contains various components and modules for the Edgehub, a solution designed for IIoT (Industrial Internet of Things) applications. 

**EdgeHub Core Services**
|Service|Description|
|-|-|
|EdgeHub Device Agent Service| As a bridge between the Platform REST API service and the EdgeHub, it establishes connections and manages communication.|
|Platform REST API Service|Offers REST APIs for monitoring and managing device-related tasks, providing a convenient interface for device management.|
|JWT Authentication Service|Enables users to sign in using usernames and passwords. This service verifies credentials and issues tokens, granting users access to device resources and the Platform Portal.|
|AppHub-Edge|Allows users to manage the applications on the EdgeHub|

**Installation Package Bundle**
|Name|Agents Included|
|-|-|
|EdgeHub Suite|Encompasses all EdgeHub core services, ensuring a comprehensive package to facilitate various aspects of device management and application deployment.|
|EdgeHub Suite Compact|Comprises all EdgeHub core services, excluding AppHub-Edge. This version can be used as a patch within the **Applications** feature.|
|EdgeHub Suite Full|Contains all EdgeHub core services and WISE-Agent 1.4.45 (Windows only), providing an extensive suite to cater to various operational needs.|

## Usage

Please refer to [this document](https://docs.wise-paas.advantech.com/en/Guides_and_API_References/1676956646152508777/1677046206377513884/1677136527449095897/).
