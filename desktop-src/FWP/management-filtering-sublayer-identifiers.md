---
title: Filtering sublayer identifiers (Fwpmu.h)
description: WFP API management filtering sublayer identifier constants.
ms.assetid: 4c8dbe35-e84b-4490-bf7a-7ff8b94e2022
topic_type:
- apiref
api_name:
- FWPM_SUBLAYER_EDGE_TRAVERSAL / FWPM_SUBLAYER_TEREDO
- FWPM_SUBLAYER_INSPECTION
- FWPM_SUBLAYER_IPSEC_DOSP
- FWPM_SUBLAYER_IPSEC_FORWARD_OUTBOUND_TUNNEL
- FWPM_SUBLAYER_IPSEC_TUNNEL
- FWPM_SUBLAYER_LIPS
- FWPM_SUBLAYER_RPC_AUDIT
- FWPM_SUBLAYER_SECURE_SOCKET
- FWPM_SUBLAYER_TCP_CHIMNEY_OFFLOAD
- FWPM_SUBLAYER_TCP_TEMPLATES
- FWPM_SUBLAYER_UNIVERSAL
api_location:
- fwpmu.h
api_type:
- HeaderDef
ms.topic: reference
ms.date: 05/02/2024
---

# Filtering sublayer identifiers

The Windows Filtering Platform (WFP) sublayer identifiers are each represented by a GUID.

These identifiers are defined as follows.

<dl> <dt>

<span id="FWPM_SUBLAYER_EDGE_TRAVERSAL________________________FWPM_SUBLAYER_TEREDO"></span><span id="fwpm_sublayer_edge_traversal________________________fwpm_sublayer_teredo"></span>**FWPM\_SUBLAYER\_EDGE\_TRAVERSAL / FWPM\_SUBLAYER\_TEREDO**
</dt> <dd> <dl> <dt>



Edge traversal filters are added to this sublayer.

> [!Note]  
> For Windows 7 and later, use **FWPM\_SUBLAYER\_EDGE\_TRAVERSAL**.

 


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_INSPECTION"></span><span id="fwpm_sublayer_inspection"></span>**FWPM\_SUBLAYER\_INSPECTION**
</dt> <dd> <dl> <dt>



This is the lowest weighted sublayer. It is used only for inspection filters.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_IPSEC_DOSP"></span><span id="fwpm_sublayer_ipsec_dosp"></span>**FWPM\_SUBLAYER\_IPSEC\_DOSP**
</dt> <dd> <dl> <dt>



IPsec DoS Protection filters are added to this sublayer.

> [!Note]  
> Available only on Windows Vista with SP1, Windows Server 2008, and later.

 


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_IPSEC_FORWARD_OUTBOUND_TUNNEL"></span><span id="fwpm_sublayer_ipsec_forward_outbound_tunnel"></span>**FWPM\_SUBLAYER\_IPSEC\_FORWARD\_OUTBOUND\_TUNNEL**
</dt> <dd> <dl> <dt>



IPsec forward outbound tunnel filters are added to this sublayer.

> [!Note]  
> Available only on Windows 7, Windows Server 2008 R2, and later.

 


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_IPSEC_TUNNEL"></span><span id="fwpm_sublayer_ipsec_tunnel"></span>**FWPM\_SUBLAYER\_IPSEC\_TUNNEL**
</dt> <dd> <dl> <dt>



IPsec tunnel filters are added to this sublayer.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_LIPS"></span><span id="fwpm_sublayer_lips"></span>**FWPM\_SUBLAYER\_LIPS**
</dt> <dd> <dl> <dt>



Legacy IPsec filters are added to this sublayer.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_RPC_AUDIT"></span><span id="fwpm_sublayer_rpc_audit"></span>**FWPM\_SUBLAYER\_RPC\_AUDIT**
</dt> <dd> <dl> <dt>



RPC audit filters are added to this sublayer. These filters audit RPC incoming calls as part of C2 and common criteria compliance.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_SECURE_SOCKET"></span><span id="fwpm_sublayer_secure_socket"></span>**FWPM\_SUBLAYER\_SECURE\_SOCKET**
</dt> <dd> <dl> <dt>



Secure socket filters are added to this sublayer.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_TCP_CHIMNEY_OFFLOAD"></span><span id="fwpm_sublayer_tcp_chimney_offload"></span>**FWPM\_SUBLAYER\_TCP\_CHIMNEY\_OFFLOAD**
</dt> <dd> <dl> <dt>



TCP Chimney Offload filters are added to this sublayer.


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_TCP_TEMPLATES______________________"></span><span id="fwpm_sublayer_tcp_templates______________________"></span>**FWPM\_SUBLAYER\_TCP\_TEMPLATES** 
</dt> <dd> <dl> <dt>



TCP template filters are added to this sublayer.

> [!Note]  
> Available only on Windows 8, Windows Server 2012, and later.

 


</dt> </dl> </dd> <dt>

<span id="FWPM_SUBLAYER_UNIVERSAL"></span><span id="fwpm_sublayer_universal"></span>**FWPM\_SUBLAYER\_UNIVERSAL**
</dt> <dd> <dl> <dt>



This sublayer hosts all filters that are not assigned to any of the other sublayers.


</dt> </dl> </dd> </dl>

**FWPM_SUBLAYER_IPSEC_SECURITY_REALM**

Microsoft IPsec security realm filters are added to this layer. See [IPsec security realm](/openspecs/windows_protocols/ms-ikee/1ebd9e40-e671-45f3-b019-fd42e6be80ea).

**FWPM_SUBLAYER_MPSSVC_WSH**

Windows Service Hardening filters are added to this sublayer.

**FWPM_SUBLAYER_MPSSVC_WF**

Windows Firewall filters are added to this layer. These filters include those from rules added through Windows Firewall.

**FWPM_SUBLAYER_MPSSVC_QUARANTINE**

Windows Quarantine filters are added to this sublayer. Quarantine layer filters apply when an IP Interfaces is ‘quarantined’ – when the IP Interface is changing state and Windows is resolving its Firewall Profile.

**FWPM_SUBLAYER_MPSSVC_EDP**

Windows Enterprise Data Protection filters are added to this sublayer. This is now called Windows Information Protection. See [Protect your enterprise data by using WIP](/windows/security/information-protection/windows-information-protection/protect-enterprise-data-using-wip).

**FWPM_SUBLAYER_MPSSVC_TENANT_RESTRICTIONS**

Microsoft Tenant Restrictions version 2 filters are added to this sublayer. See [Set up tenant restrictions v2](/entra/external-id/tenant-restrictions-v2).

**FWPM_SUBLAYER_MPSSVC_APP_ISOLATION**

Windows Application Isolation filters are added to this sublayer. These filters apply to applications running in an App-Container and requires App-Container network capabilities.

## Requirements

| Requirement | Value |
|-------------------------------------|------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                     |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                               |
| Header<br/>                   | <dl> <dt>Fwpmu.h</dt> </dl> |
