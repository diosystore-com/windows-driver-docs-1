---
title: IPrintOemDriverPS COM Interface
description: IPrintOemDriverPS COM Interface
keywords:
- IPrintOemDriverPS
ms.date: 01/27/2023
---

# IPrintOemDriverPS COM Interface

[!include[Print Support Apps](../includes/print-support-apps.md)]

The `IPrintOemDriverPS` COM interface provides a rendering plug-in with access to utility operations supplied by the printer graphics DLL for Pscript5. These operations send a data stream to the print spooler and obtain driver-managed information.

The following table lists and describes all of the methods defined by the `IPrintOemDriverPS` interface.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Method</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriverps-drvgetdriversetting" data-raw-source="[&lt;strong&gt;IPrintOemDriverPS::DrvGetDriverSetting&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriverps-drvgetdriversetting)"><strong>IPrintOemDriverPS::DrvGetDriverSetting</strong></a></p></td>
<td><p>Returns the current status of printer features and other internal information.</p></td>
</tr>
<tr class="even">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriverps-drvwritespoolbuf" data-raw-source="[&lt;strong&gt;IPrintOemDriverPS::DrvWriteSpoolBuf&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriverps-drvwritespoolbuf)"><strong>IPrintOemDriverPS::DrvWriteSpoolBuf</strong></a></p></td>
<td><p>Sends printer data to the spooler.</p></td>
</tr>
</tbody>
</table>

For more information, see [Implementing Printer Driver COM Interfaces](implementing-printer-driver-com-interfaces.md).
