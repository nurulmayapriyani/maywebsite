---
date: 2025-08-20 17:00:00
title: Return Tax Sales Tracking
subtitle: Fullstack Project (Fulltime Work)
image: /uploads/return-tax-cover.png
---
Work Period of Project: 25th July 2025 – 20th August 2025  

The works I did in this Return Tax feature:

![](/uploads/return-tax-filter.png){: width="1893" height="749"}

At "Pajak Retur" tab, user can filter Return No, Principal, Status, Return Period, and Creation Date.

![](/uploads/return-tax-filter-return-no.png){: width="1893" height="749"}

User can type any return number in the "Return No" field, they can search more than one return number.

![](/uploads/return-tax-filter-principal.png){: width="1893" height="749"}

User can filter by principal name in the "Principal" field.

![](/uploads/return-tax-filter-status.png){: width="1893" height="749"}

User can select status in the "Status" field.

![](/uploads/return-tax-filter-return-period.png){: width="1893" height="749"}

User can filter by return period in the "Return Period" field.

![](/uploads/return-tax-filter-creation-date.png){: width="1893" height="749"}

User also can filter by creation date in the "Creation Date" field.

![](/uploads/return-tax-download-btn.png){: width="1893" height="749"}

![](/uploads/return-tax-download-modal.png){: width="1893" height="749"}

![](/uploads/return-tax-download-csv.png){: width="1893" height="749"}

“Download“ button is always enabled even when user doesn't select any row(s). It will open a modal which contains three inputs; Principal, Start Date, and End Date. When user clicks "Submit" button, it will download a CSV file which contains return data(s) based on Principal, Start Date, and End Date that user input before clicking "Submit" button.

![](/uploads/return-tax-cetak-retur-btn.png){: width="1903" height="733"}

![](/uploads/return-tax-cetak-retur-pdf.png){: width="1903" height="733"}

“Cetak Retur” button will be enabled for all statuses, this button is for generating pdf file(s) which contain selected row(s).

![](/uploads/return-tax-status-completed.png){: width="1903" height="733"}

If the status is “Completed” then there is only “Cetak Retur” button that is enabled other than “Download” button.

![](/uploads/return-tax-status-draft.png){: width="1899" height="903"}

If the status is “Draft”, then the buttons that are enabled except “Cetak Retur” and “Download” are “Delete All” and “Approve All”.

![](/uploads/return-tax-approve-btn.png){: width="1899" height="893"}

![](/uploads/return-tax-approve-confirm.png){: width="1899" height="893"}

![](/uploads/return-tax-approve-success.png){: width="1899" height="893"}

“Approve All” button is used to approve selected row(s). 

![](/uploads/return-tax-approve-after-success.png){: width="1899" height="893"}

After successfully approved, the status of selected row will be changed from “Draft” to “Approved”.

![](/uploads/return-tax-status-approved.png){: width="1899" height="893"}

If the status is “Approved”, then the button that is enabled except “Cetak Retur” and “Download” is “Generate All” button. 

![](/uploads/return-tax-generate-btn.png){: width="1899" height="893"}

![](/uploads/return-tax-generate-confirm.png){: width="1899" height="893"}

![](/uploads/return-tax-generate-success.png){: width="1899" height="893"}

![](/uploads/return-tax-generate-zip.png){: width="1899" height="893"}

![](/uploads/return-tax-generate-xml.png){: width="1899" height="893"}

"Generate All" button is used for generating a zip file which contains selected row(s) in XML format.

![](/uploads/return-tax-generate-after-success.png){: width="1899" height="893"}

After successfully generated, the status of selected row will be changed from “Approved” to “XML Generated”.

![](/uploads/return-tax-status-xml-generated.png){: width="1899" height="893"}

If the status is “XML_Generated”, then the buttons that are enabled except “Cetak Retur” and “Download” are “Reject All” button, “Generate All” button, and “Finish All” button.

![](/uploads/return-tax-reject-btn.png){: width="1899" height="893"}

![](/uploads/return-tax-reject-confirm.png){: width="1899" height="893"}

![](/uploads/return-tax-reject-reason-modal-empty.png){: width="1899" height="893"}

![](/uploads/return-tax-reject-reason-required-warning.png){: width="1899" height="893"}

![](/uploads/return-tax-reject-reason-modal-filled.png){: width="1899" height="893"}

![](/uploads/return-tax-reject-success.png){: width="1899" height="893"}

“Reject All” button is used to reject selected row(s). The reason of rejection is required otherwise there will be a warning show up.

![](/uploads/return-tax-reject-after-success.png){: width="1899" height="893"}

After successfully rejected, the status of selected row will be changed from “XML Generated” to “Rejected”.

![](/uploads/return-tax-finish-btn.png){: width="1899" height="890"}

![](/uploads/return-tax-finish-confirm.png){: width="1899" height="890"}

![](/uploads/return-tax-finish-success.png){: width="1899" height="890"}

“Finish All” button is used for finishing selected row(s).

![](/uploads/return-tax-finish-after-success.png){: width="1899" height="890"}

After user clicked “Finish All” button, the status will be changed from “XML Generated” to “Completed”.

![](/uploads/return-tax-status-rejected.png){: width="1899" height="890"}

If the status is “Rejected”, then the button that is enabled except “Cetak Retur” is “Delete All” button.

![](/uploads/return-tax-delete-btn.png){: width="1899" height="890"}

![](/uploads/return-tax-delete-confirm.png){: width="1899" height="890"}

![](/uploads/return-tax-delete-success.png){: width="1899" height="890"}

“Delete All” button is used to delete selected row(s).

![](/uploads/return-tax-delete-after-success.png){: width="1899" height="890"}

After successfully deleted, the selected row(s) will be deleted from “Rejected”.

![](/uploads/invoice-import-template-download.png){: width="1893" height="749"}

![](/uploads/invoice-import-template-excel.png){: width="1893" height="749"}

At “Impor Faktur” tab, user can download excel template file on “link download template”.

![](/uploads/invoice-import-upload-file.png){: width="1893" height="749"}

![](/uploads/invoice-import-file-uploaded-submit.png){: width="1893" height="749"}

After that, user can upload excel template file that is already filled on “Drag file here or click to upload”, and click “Submit File”.

![](/uploads/invoice-import-submit-sucess.png){: width="1893" height="749"}

![](/uploads/invoice-import-submit-after-success.png){: width="1893" height="749"}

If it’s success, the new row data will show up with status “Completed”.

![](/uploads/invoice-import-submit-failed.png){: width="1893" height="749"}

![](/uploads/invoice-import-submit-after-failed.png){: width="1893" height="749"}

If it's failed, the new data will still show up but with status “Incomplete”.

> ###### ​​​​​​​![](/uploads/information-technology-icon-clipart-1-1-1.png){: width="200" height="200"}

The technologies I use in this feature:<br>\- React.js (functional/hooks).<br>\- Next.js.<br>\- Formik.<br>\- React-pdf/renderer.<br>\- Dayjs.<br>\- Moment.<br>\- Xlsx.<br>\- Yup.<br>\- React-dropzone<br>\- React-hook-form.<br>\- Sweetalert2.<br>\- Material UI.<br>\- Jszip.<br>\- Xmlbuilder2.<br>\- MySQL.<br>\- Express.js.<br>\- Nest.js.