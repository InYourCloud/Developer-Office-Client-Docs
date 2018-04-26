---
title: "Minimizing Log File Space Usage"
 
 
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: overview
  
localization_priority: Normal
ms.assetid: d527c313-35ad-c30e-6ea1-ddfeff1fe890
description: "A log file may fill quickly (thus halting the server) if there is a large volume of activity on an SQL Server database. You can set the log file to Truncate on Checkpoint to significantly extend the life of the log file for a database."
---

# Minimizing Log File Space Usage

A log file may fill quickly (thus halting the server) if there is a large volume of activity on an SQL Server database. You can set the log file to **Truncate on Checkpoint** to significantly extend the life of the log file for a database. 
  
 **To enable Truncate on Checkpoint in Microsoft SQL Server 6.5**
  
1. Start Microsoft SQL Server Enterprise Manager, open the tree for the Server, and then open the Database Devices tree.
    
2. Double-click the name of the database on which this feature will be enabled.
    
3. From the **Database** tab, select **Truncate**. 
    
4. From the **Options** tab, select **Truncate Log on Checkpoint**, and then click **OK**. 
    
 **To enable Truncate on Checkpoint in Microsoft SQL Server 7.0**
  
1. Start Microsoft SQL Server Enterprise Manager, open the tree for the Server, and then open the Databases tree.
    
2. Right-click the name of the database on which this feature will be enabled and choose **Properties**. 
    
3. From the **Options** tab, select **Truncate Log on Checkpoint**, and then click **OK**. 
    
For more information about the **Truncate on Checkpoint** feature, see the Microsoft SQL Server documentation. 
  
