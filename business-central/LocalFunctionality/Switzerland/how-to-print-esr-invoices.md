---
title: How to print ESR invoices [CH]
description: This article describes how you can print an Einzahlungsschein mit Referenznummer (ESR) payment slip invoices and coupons.
author: brentholtorf
ms.topic: conceptual
ms.devlang: al
ms.search.keywords:
ms.search.form: 3010531, 3010532
ms.date: 12/08/2023
ms.author: bholtorf
ms.service: dynamics-365-business-central
ms.reviewer: bholtorf
---
# Print ESR invoices in the Swiss version

You can print an Einzahlungsschein mit Referenznummer (ESR) payment slip in the following ways:  

- As part of the sales invoice ESR.  
- As a separate document called an ESR coupon.  

The sales invoice ESR report corresponds with the sales invoice that is accompanied by an additional ESR coupon. By using the sales ESR coupon report, you can print the blue deposit slip.  

> [!NOTE]  
> You must select a printer and select settings during the ESR payment module installation to print the deposit slip correctly. For more information, see the Printer Selection table.  

The following procedure describes how to print ESR sales invoices, but the same steps also apply for printing ESR coupons.  

## To print ESR invoices  

1. Choose the ![Lightbulb that opens the Tell Me feature.](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Invoice ESR**, and then choose the related link.  
2. In the **Sales Invoice ESR** batch job, on the **Options** FastTab, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**No. of copies**|Enter the required number of report copies.|  
    |**ESR Bank**|Select the ESR bank code that is to be printed in the report.<br /><br /> If the value in this field is \<Blank\> and the ESR payment method code isn't defined on the **ESR Setup** page, then the ESR main bank selected on the **ESR Setup** page will be printed.|  
    |**LogInteraction**|Specify if the interactions that you have with your contacts will be logged.|  
    |**ESR System**|Select the ESR system through which you can send new ESR coupons to customers. To use the ESR system that is used by the bank that you specify in **ESR Bank** field, select **Based on ESR Bank**.|  

3. Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.  

You can also reprint the sales invoice ESR report or sales ESR coupon report.  

## Related information  
 [Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md)   
 [Import ESR Payments](how-to-import-esr-payments.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]