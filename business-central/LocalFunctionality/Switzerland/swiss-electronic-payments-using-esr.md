---
title: Swiss Electronic Payments Using ESR [CH]
description: This topic explains the different tasks you can accomplish with the Einzahlungsschein mit Referenznummer (ESR) electronic payment method debtor service.
author: brentholtorf
ms.topic: conceptual
ms.devlang: al
ms.search.keywords:
ms.search.form: 3010531, 3010532
ms.date: 06/21/2021
ms.author: bholtorf
ms.service: dynamics-365-business-central
ms.reviewer: bholtorf
---
# Swiss Electronic Payments Using ESR in the Swiss Version
The Einzahlungsschein mit Referenznummer (ESR) electronic payment method is an electronic debtor service that allows the customer to bill open invoices in Swiss Francs (CHF) and Euros (EUR), and to post incoming payments efficiently. The reference number, or code line, contains all relevant bookkeeping data.  

With ESR electronic payments, you can do the following:  

- Send ESR payment slips with unique reference numbers on the invoices. Because of the unique ESR reference numbers, the payments for settlement are automatically applied to the related invoices. For more information, see [Print ESR Invoices](how-to-print-esr-invoices.md).  

- Download the ESR files from the bank daily. The files contain information about all paid invoices.  

- Import the ESR files and create payment lines automatically for each payment. For more information, see [Import ESR Payments](how-to-import-esr-payments.md).  

> [!NOTE]  
>  Before you can use the ESR module, you must set up the bank, bank account, and file name. You must also specify whether ESR or ESR+ should be used.

When you have evaluated the setup information, you can adjust the invoice form, and you can create a test series that you can ask your bank or postal service to validate.  

When you set up number series for invoices, you must follow these guidelines:  

- Use a maximum of eight digits.  
- Use only numeric characters.  
- Do not precede numbers with zeros.  

## Related information  
 [Swiss Electronic Payments](swiss-electronic-payments.md)   
 [Print ESR Invoices](how-to-print-esr-invoices.md)   
 [Import ESR Payments](how-to-import-esr-payments.md)   
 [Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Making Payments](../../payables-make-payments.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]