---
title: IPrintOemDriverUni COM Interface
description: IPrintOemDriverUni COM Interface
keywords:
- IPrintOemDriverUni
ms.date: 01/27/2023
---

# IPrintOemDriverUni COM Interface

[!include[Print Support Apps](../includes/print-support-apps.md)]

The `IPrintOemDriverUni COM` interface provides a rendering plug-in with access to utility operations supplied by the printer graphics DLL for Unidrv. These operations send a data stream to the print spooler, and obtain driver-managed information.

The following table lists and describes all of the methods defined by the **IPrintOemDriverUni** interface.

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
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetdriversetting" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvGetDriverSetting&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetdriversetting)"><strong>IPrintOemDriverUni::DrvGetDriverSetting</strong></a></p></td>
<td><p>Returns the current status of printer features and other internal information.</p></td>
</tr>
<tr class="even">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetgpddata" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvGetGPDData&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetgpddata)"><strong>IPrintOemDriverUni::DrvGetGPDData</strong></a></p></td>
<td><p>Enables rendering plug-ins to obtain data defined in a printer's <a href="/windows-hardware/drivers/#wdkgloss-generic-printer-description--gpd-" data-raw-source="&lt;em&gt;generic printer description (GPD)&lt;/em&gt;"><em>generic printer description (GPD)</em></a> file.</p></td>
</tr>
<tr class="odd">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetstandardvariable" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvGetStandardVariable&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvgetstandardvariable)"><strong>IPrintOemDriverUni::DrvGetStandardVariable</strong></a></p></td>
<td><p>Enables rendering plug-ins to obtain the current value of Unidrv's <a href="standard-variables.md" data-raw-source="[standard variables](standard-variables.md)">standard variables</a>.</p></td>
</tr>
<tr class="even">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvunitextout" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvUniTextOut&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvunitextout)"><strong>IPrintOemDriverUni::DrvUniTextOut</strong></a></p></td>
<td><p>Enables a rendering plug-in using a device-managed drawing surface to easily output text strings.</p></td>
</tr>
<tr class="odd">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvwriteabortbuf" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvWriteAbortBuf&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvwriteabortbuf)"><strong>IPrintOemDriverUni::DrvWriteAbortBuf</strong></a></p></td>
<td><p>Enables a rendering plug-in to reset a printer after a user has terminated a print job.</p></td>
</tr>
<tr class="even">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvwritespoolbuf" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvWriteSpoolBuf&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvwritespoolbuf)"><strong>IPrintOemDriverUni::DrvWriteSpoolBuf</strong></a></p></td>
<td><p>Sends printer data to the spooler.</p></td>
</tr>
<tr class="odd">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvxmoveto" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvXMoveTo&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvxmoveto)"><strong>IPrintOemDriverUni::DrvXMoveTo</strong></a></p></td>
<td><p>Notifies Unidrv of cursor x-position changes.</p></td>
</tr>
<tr class="even">
<td><p><a href="/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvymoveto" data-raw-source="[&lt;strong&gt;IPrintOemDriverUni::DrvYMoveTo&lt;/strong&gt;](/windows-hardware/drivers/ddi/prcomoem/nf-prcomoem-iprintoemdriveruni-drvymoveto)"><strong>IPrintOemDriverUni::DrvYMoveTo</strong></a></p></td>
<td><p>Notifies Unidrv of cursor y-position changes.</p></td>
</tr>
</tbody>
</table>

For more information, see [Implementing Printer Driver COM Interfaces](implementing-printer-driver-com-interfaces.md).
