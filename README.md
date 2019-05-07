# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-virtualNetworkGateway/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:33+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified virtual network Gateway connection.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The name of the virtual network gateway connection.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified virtual network gateway connection by resource group.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The name of the virtual network gateway connection.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a virtual network gateway connection tags.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The name of the virtual network gateway connection.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a virtual network gateway connection in the specified resource group.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The name of the virtual network gateway connection.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The virtual network gateway connection shared key name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The virtual network gateway connection name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.

*Tags:* `VirtualNetworkGatewayConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The virtual network gateway connection reset shared key Name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a xml format representation for vpn device configuration script.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayConnectionName` - _required_ - The name of the virtual network gateway connection for which the configuration script is generated.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the local network gateways in a resource group.

*Tags:* `LocalNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified local network gateway.

*Tags:* `LocalNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `localNetworkGatewayName` - _required_ - The name of the local network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified local network gateway in a resource group.

*Tags:* `LocalNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `localNetworkGatewayName` - _required_ - The name of the local network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a local network gateway tags.

*Tags:* `LocalNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `localNetworkGatewayName` - _required_ - The name of the local network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a local network gateway in the specified resource group.

*Tags:* `LocalNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `localNetworkGatewayName` - _required_ - The name of the local network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all virtual network gateways by resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified virtual network gateway.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified virtual network gateway by resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a virtual network gateway tags.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a virtual network gateway in the specified resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the connections in a virtual network gateway.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Generates VPN profile for P2S client of the virtual network gateway in the specified resource group. Used for IKEV2 and radius based authentication.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `peer` - _required_ - The IP address of the peer
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The GetBgpPeerStatus operation retrieves the status of all BGP peers.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `peer` - _optional_ - The IP address of the peer to retrieve the status of.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The Get VpnclientIpsecParameters operation retrieves information about the vpnclient ipsec policy for P2S client of virtual network gateway in the specified resource group through Network resource provider.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The virtual network gateway name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group. The profile needs to be generated first using generateVpnProfile.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Resets the primary of the virtual network gateway in the specified resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `gatewayVip` - _optional_ - Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Resets the VPN client shared key of the virtual network gateway in the specified resource group.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### The Set VpnclientIpsecParameters operation sets the vpnclient ipsec policy for P2S client of virtual network gateway in the specified resource group through Network resource provider.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a xml format representation for supported vpn devices.

*Tags:* `VirtualNetworkGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `virtualNetworkGatewayName` - _required_ - The name of the virtual network gateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-virtual-network-gateway-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
