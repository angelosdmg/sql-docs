---
# required metadata

title: Manage SQL Server on Linux - SQL Server vNext | Microsoft Docs
description: This topic provides links to common management tasks and tools for SQL Server running on Linux.
author: rothja 
ms.author: jroth 
manager: jhubbard
ms.date: 12/05/2016
ms.topic: article
ms.prod: sql-linux
ms.technology: database-engine
ms.assetid: 6bd8eb0b-593d-467e-87ea-ab1c4dbcd1ea

# optional metadata

# keywords: ""
# ROBOTS: ""
# audience: ""
# ms.devlang: ""
# ms.reviewer: ""
# ms.suite: ""
# ms.tgt_pltfrm: ""
# ms.custom: ""

---
# Manage SQL Server on Linux

There are several ways to manage SQL Server vNext CTP 1.2 on Linux. The following section provide a quick overview of different management tools and techniques with pointers to more resources.

## mssql-conf 
The **mssql-conf** tool configures SQL Server on Linux. For more information, see [Configure SQL Server on Linux with mssql-conf](sql-server-linux-configure-mssql-conf.md).

## Transact-SQL
Almost everything you can do in a client tool can also be accomplished with Transact-SQL statements. SQL Server provides [Dynamic Management Views (DMVs)](https://msdn.microsoft.com/library/ms188754.aspx) that query the status and configuration of SQL Server. There are also [Transact-SQL commands](https://msdn.microsoft.com/library/bb510741.aspx) for database management tasks. You can run these commands in any client tool that supports connecting to SQL Server and running Transact-SQL queries. Examples include [sqlcmd](sql-server-linux-connect-and-query-sqlcmd.md), [Visual Studio Code](sql-server-linux-develop-use-vscode.md), and [SQL Server Management Studio](sql-server-linux-manage-ssms.md).  

## SQL Server Management Studio on Windows
SQL Server Management Studio (SSMS) is a Windows application that provides a graphical user interface for managing SQL Server. Although it currently runs only on Windows, you can use it to remotely connect to your Linux SQL Server instances. For more information on using SSMS to manage SQL Server, see [Use SSMS to Manage SQL Server on Linux](sql-server-linux-manage-ssms.md).

## PowerShell
PowerShell provides a rich command-line environment to manage SQL Server on Linux. For more information, see [Use PowerShell to Manage SQL Server on Linux](sql-server-linux-manage-powershell.md).

## Next steps
For more information on how to get started using SQL Server on Linux, see [Get started with SQL Server on Linux](sql-server-linux-get-started-tutorial.md).

