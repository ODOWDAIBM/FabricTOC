# Administration Guide

This section of the documentation explains how to administer a Hyperledger Fabric blockchain network.  You'll find this material helpful if you are new to Hyperledger Fabric, or if you want to learn "hands on" how to create and administer a blockchain, or if you want to find a specific administrative command or piece of reference information.  

#### [How the Administration Guide is organized](./HowOrganized/HowOrganized.md)

 + [Concepts, Tasks and References for this guide](./HowOrganized/ConceptsTasksReferences.md)
 + [Key Concepts](./HowOrganized/KeyConcepts.md)
 + [The DRIVENET sample](./HowOrganized/DriveNetSampleNetwork.md)
 + [Administrative Tasks](./HowOrganized/AdministrativeTasks.md)
 + [Reference Material](./HowOrganized/ReferenceMaterial.md)
 + [Glossary of Terms](./HowOrganized/GlossaryOfTerms.md)

#### [Key Concepts](./KeyConcepts/KeyConcepts.md)

  + [Network](./KeyConcepts/Network/Network.md)
  + [Consortia](./KeyConcepts/Consortia/Consortia.md)
    + [What is a consortium?](./KeyConcepts/Consortia/Consortia.md)
    + [Adding consortia to the network definition](./KeyConcepts/Consortia/Consortia.md)
    + [Changing Consortia](./KeyConcepts/Consortia/Consortia.md)
    + [DRIVENET consortia](./KeyConcepts/Consortia/Consortia.md)
  + [The Organizations in a network](./KeyConcepts/Organizations/Organizations.md)
    + [The initial organizations](./KeyConcepts/Organizations/Organizations.md)
    + [Adding new organizations to a network](./KeyConcepts/Organizations/Organizations.md)
    + [Organizations in DRIVENET](./KeyConcepts/Organizations/Organizations.md)
  + [The Principals in an organization](./KeyConcepts/Principals/Principals.md)
    + [Organizations, Organizational Units, Roles and Members](./KeyConcepts/Principals/Principals.md)
    + [Identifying Principals with Digital Certificates](./KeyConcepts/Principals/Principals.md)
    + [Principals in DRIVENET](./KeyConcepts/Principals/Principals.md)
  + [Identity and Trusted Membership](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
    + [What is a Certificate Authority?](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
    + [Why are CAs important?](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
    + [Root CAs and Intermediate CAs](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
    + [Membership Services Providers](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
    + [MSPs in DRIVENET](./KeyConcepts/IdentityandMembership/IdentityandMembership.md)
  + [Policies for Access Control](./KeyConcepts/Policy/Policy.md)
    + [What are policies?](./KeyConcepts/Policy/Policy.md)
    + [Why are policies important?](./KeyConcepts/Policy/Policy.md)
    + [Principals and resource access control](./KeyConcepts/Policy/Policy.md)
    + [Implicit and Explicit policies](./KeyConcepts/Policies/Policy.md)
    + [Policies for Changing Policies - Mod_Policies!](./KeyConcepts/Policy/Policy.md)
    + [Policies in DRIVENET](./KeyConcepts/Policies/Policy.md)
  + [Defining and starting a network](./KeyConcepts/Network/CreatingandUpdating.md)
    + [The Resources in a Network Definition](./KeyConcepts/Network/NetworkResources.md)
      + [How a network is defined](./KeyConcepts/Network/HowNetworkDefined.md)
      + [Managing the network definition](./KeyConcepts/Network/ManagingNetworkDefinition.md)
      + [The DRIVENET example network](./KeyConcepts/Network/DriveNetResources.md)
    + [Bootstrapping the network](./KeyConcepts/Network/CreatingandUpdating.md)
      + [The genesis block](./KeyConcepts/Network/CreatingandUpdating.md)
      + [Starting the network orderers](./KeyConcepts/Network/CreatingandUpdating.md)
      + [The DRIVENET network](./KeyConcepts/Network/CreatingandUpdating.md)
    + [Updating the network](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [Configuration transactions](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [Verifying network changes](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [A DRIVENET configuration transaction](./KeyConcepts/Network/UpdatingtheNetwork.md)
  + [Channels](./KeyConcepts/Channels/Channels.md)
    + [What is a Channel?](./KeyConcepts/Channels/Channels.md)
    + [Why are channels important?](./KeyConcepts/Channels/Channels.md)
    + [Channel Creation Policy](./KeyConcepts/Channels/Channels.md)
    + [Defining a Channel](./KeyConcepts/Channels/Channels.md)
    + [Updating a Channel](./KeyConcepts/Channels/Channels.md)
    + [DRIVENET channels](./KeyConcepts/Channels/Channels.md)
  + [Peers](./KeyConcepts/Peers/Peers.md)
    + [What is a peer?](./KeyConcepts/Peers/Peers.md)
    + [Peers and the ledger](./KeyConcepts/Peers/Peers.md)
    + [Peers and Identity](./KeyConcepts/Peers/Peers.md)
    + [Starting and Stopping Peers](./KeyConcepts/Peers/Peers.md)
    + [Joining a channel](./KeyConcepts/Peers/Peers.md)
    + [Changing a Peer](./KeyConcepts/Peers/eers.md)
    + [Peers in DRIVENET](./KeyConcepts/Peers/Peers.md)
  + [Smart Contracts and Chaincode](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [What is a Smart contract and chaincode?](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [Smart Contracts and the ledger](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [Installing a smart contract](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [Instantiating a smart contract](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [Upgrading a smart contract](./KeyConcepts/SmartContracts/SmartContracts.md)
    + [DRIVENET smart contracts](./KeyConcepts/SmartContracts/SmartContracts.md)
  + [Defining and starting a channel](./KeyConcepts/Network/CreatingandUpdating.md)
    + [The Resources in a Channel Definition](./KeyConcepts/Network/NetworkResources.md)
      + [How a channel is defined](./KeyConcepts/Network/HowNetworkDefined.md)
      + [Managing the channel definition](./KeyConcepts/Network/ManagingNetworkDefinition.md)
      + [The DRIVENET example network](./KeyConcepts/Network/DriveNetResources.md)
    + [Bootstrapping the channel](./KeyConcepts/Network/CreatingandUpdating.md)
      + [The genesis block](./KeyConcepts/Network/CreatingandUpdating.md)
      + [Starting the peers](./KeyConcepts/Network/CreatingandUpdating.md)
      + [The DRIVENET network](./KeyConcepts/Network/CreatingandUpdating.md)
    + [Updating the network](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [Configuration transactions](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [Verifying channel changes](./KeyConcepts/Network/UpdatingtheNetwork.md)
      + [A DRIVENET channel configuration transaction](./KeyConcepts/Network/UpdatingtheNetwork.md)      

#### [The DRIVENET sample network](./DriveNetSample/StartingDRIVENET.md)

  + [Starting DRIVENET](./DriveNetSample/StartingDRIVENET.md)
    + [Defining the initial network configuration](./DriveNetSample/StartingDRIVENET.md)
      + [Organizations and Certificate Authorities](./DriveNetSample/StartingDRIVENET.md)
      + [Mitchell and Regal organizations](./DriveNetSample/StartingDRIVENET.md)
      + [Verisign and TrustCorp as CAs](./DriveNetSample/StartingDRIVENET.md)
      + [Principals and Access Control Policies](./DriveNetSample/StartingDRIVENET.md)
    + [Defining rights for Mitchel and Regal](./DriveNetSample/StartingDRIVENET.md)
      + [Initial Policies for updating DRIVENET](./DriveNetSample/StartingDRIVENET.md)
      + [Bootstrapping the network](./DriveNetSample/StartingDRIVENET.md)
      + [DRIVENET genesis block](./DriveNetSample/StartingDRIVENET.md)
      + [Starting Mitchell's orderer](./DriveNetSample/StartingDRIVENET.md)
      + [Starting Regal's orderer](./DriveNetSample/StartingDRIVENET.md)
    + [Updating the network definition](./DriveNetSample/StartingDRIVENET.md)
      + [Changing the Mitchell and Regal Admin Policy from ANY to ALL](./DriveNetSample/StartingDRIVENET.md)
    + [Adding the first consortium](./DriveNetSample/StartingDRIVENET.md)
      + [Starting the manufacturing consortium](./DriveNetSample/StartingDRIVENET.md)
      + [Assigning rights to the Principals](./DriveNetSample/StartingDRIVENET.md)
    + [...](./DriveNetSample/StartingDRIVENET.md)
      + [Defining the first channel](./DriveNetSample/StartingDRIVENET.md)
  + [Growing DRIVENET](./DriveNetSample/GrowingDRIVENET.md)
  + [Expanding DRIVENET](./DriveNetSample/GrowingDRIVENET.md)

#### [Administrative Tasks](./AdminTasks/AdminTasks.md)

  + [How this section is organized](./AdminTasks/AdminTasks.md#HowOrganized)
  + [Certificate Authority Tasks](/.AdminTasks/CATasks.md)
    + [General CA Tasks](./AdminTasks/CATasks.md)
    + [Fabric CA Tasks](./AdminTasks/CATasks.md)
      + [Configuring a Fabric CA](./AdminTasks/CATasks.md)
      + [Starting a Fabric CA](./AdminTasks/CATasks.md)
      + [Stopping a Fabric CA](./AdminTasks/CATasks.md)
    + [External CA Tasks](./AdminTasks/CATasks.md)
  + [Network Tasks](./AdminTasks/NetworkTasks.md)
    + [Defining a network genesis block](./AdminTasks/NetworkTasks.md)
      + [Defining the network values](./AdminTasks/NetworkTasks.md)
      + [Defining the network version](./AdminTasks/NetworkTasks.md)
      + [Defining the network groups](./AdminTasks/NetworkTasks.md)
      + [Defining the network policies](./AdminTasks/NetworkTasks.md)
      + [Defining the network mod_policy](./AdminTasks/NetworkTasks.md)
    + [Changing a network definition](./AdminTasks/NetworkTasks.md)
      + [Updating the network values](./AdminTasks/NetworkTasks.md)
      + [Updating the network version](./AdminTasks/NetworkTasks.md)
      + [Updating the network groups](./AdminTasks/NetworkTasks.md)
      + [Updating the network policies](./AdminTasks/NetworkTasks.md)
      + [Updating the network mod_policy](./AdminTasks/NetworkTasks.md)
  + [Consortium Tasks](./AdminTasks/ConsortiumTasks.md)
    + [Creating a consortium](./AdminTasks/ConsortiumTasks.md)
    + [Updating a consortium](./AdminTasks/ConsortiumTasks.md)
    + [Deleting a consortium](./AdminTasks/ConsortiumTasks.md)
  + [Organization Tasks](./AdminTasks/OrganizationTasks.md)
    + [Adding an organization to a network](./AdminTasks/OrganizationTasks.md)
    + [Creating a genesis block](./AdminTasks/OrganizationTasks.md)
    + [Managing Organizations](./AdminTasks/OrganizationTasks.md)
  + [Managing Identity](./AdminTasks/ManagingIdentity.md)
    + [Using Policy](./AdminTasks/ManagingIdentity.md)
    + [Orderer](./AdminTasks/ManagingIdentity.md)
  + [Peer Tasks](./AdminTasks/PeerTasks.md)
    + [Determining a Peer's version](./AdminTasks/Peer/PeerVersion.md)
    + [Starting a peer](./AdminTasks/PeerTasks.md)
    + [DefAssociating an identity](./AdminTasks/PeerTasks.md)
    + [Submitting a Config transaction](./AdminTasks/PeerTasks.md)
    + [Adding an Organization to a network](./AdminTasks/PeerTasks.md)
    + [Changing Network Values](./AdminTasks/PeerTasks.md)
      + [Block height/size](./AdminTasks/PeerTasks.md)
      + [Hashing Algorithms](./AdminTasks/PeerTasks.md)
    + [Creating a channel](./AdminTasks/PeerTasks.md)
    + [Chaincode best practices](./AdminTasks/PeerTasks.md)
    + [Membership Services](./AdminTasks/PeerTasks.md)
      + [Using Fabric CA to set up an MSP](./AdminTasks/PeerTasks.md)
      + [Integrating LDAP Server Information](./AdminTasks/PeerTasks.md)
    + [Changing the policies on changing policies](./AdminTasks/PeerTasks.md)
      + [Mod Policy Best Practices](./AdminTasks/PeerTasks.md)
    + [Endorsement Policies](./AdminTasks/PeerTasks.md)
    + [Peer Operations](./AdminTasks/PeerTasks.md)
    + [Orderer operations](./AdminTasks/PeerTasks.md)

#### [Reference Material](./Reference/Reference.md)
  + [Command Reference](./Reference/Commands/Commands.md)
     + [Peer Commands](./)
       + [`Peer` command](./Reference/Commands/Peer/PeerCommand.md)
       + [`Peer channel` command](./Reference/Commands/Peer/PeerChannelCommand.md)
       + [`Peer channel fetch` command](./Reference/Commands/Peer/PeerChannelFetchCommand.md)
  + [Advanced Information](./Reference/Advanced/Advanced.md)
     + [Peers](./Reference/Advanced/PeersReference.md)
       + [Peer Version](./Reference/Advanced/Peer/VersionInfo.md)

#### [Glossary of Administrative Terms](./Glossary/Glossary.md)

  + [Alphabetically ordered list of terms](./)
    + [A-Z](./)