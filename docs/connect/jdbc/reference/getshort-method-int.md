---
description: "getShort Method (int)"
title: "getShort Method (int) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
apiname: 
  - "SQLServerCallableStatement.getShort (int)"
apilocation: 
  - "sqljdbc.jar"
apitype: "Assembly"
ms.assetid: cd9773c1-b598-4adb-aaf6-0c0f589cbef5
author: David-Engel
ms.author: v-davidengel
---
# getShort Method (int)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves the value of the designated parameter as a **short** in the Java programming language given the parameter index.  
  
## Syntax  
  
```  
  
public short getShort(int index)  
```  
  
#### Parameters  
 *index*  
  
 An **int** that indicates the parameter index.  
  
## Return Value  
 A **short** value.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This getShort method is specified by the getShort method in the java.sql.CallableStatement interface.  
  
 This method is supported only on [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] data types that can safely return an integer value such as **smallint**, **tinyint**, and **bit**. Using this method on any other data types will cause an exception to be thrown.  
  
## See Also  
 [getShort Method &#40;SQLServerCallableStatement&#41;](../../../connect/jdbc/reference/getshort-method-sqlservercallablestatement.md)   
 [SQLServerCallableStatement Members](../../../connect/jdbc/reference/sqlservercallablestatement-members.md)   
 [SQLServerCallableStatement Class](../../../connect/jdbc/reference/sqlservercallablestatement-class.md)  
  
  
