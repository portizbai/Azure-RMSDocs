---
title: class mip::HttpOperation 
description: Documents the mip::httpoperation class of the Microsoft Information Protection (MIP) SDK.
author: msmbaldwin
ms.service: information-protection
ms.topic: reference
ms.collection: M365-security-compliance
ms.author: mbaldwin
ms.date: 01/28/2019
---

# class mip::HttpOperation 
Interface that describes a single HTTP operation, implemented by client app when overriding [HttpDelegate](class_mip_httpdelegate.md).
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public const std::string& GetId() const  |  Gets operation ID.
public std::shared_ptr\<HttpResponse\> GetResponse()  |  Get response, if any.
public bool IsCancelled()  |  Get cancellation status of operation.
  
## Members
  
### GetId function
Gets operation ID.

  
**Returns**: Operation ID
The corresponding [HttpRequest](class_mip_httprequest.md) and [HttpResponse](class_mip_httpresponse.md) will have the same ID
  
### GetResponse function
Get response, if any.

  
**Returns**: Response
  
### IsCancelled function
Get cancellation status of operation.

  
**Returns**: Cancellation status