---
date: 2026-10-18 17:33:00
title: Cash Advance Accountability Bizops MPI
subtitle: Fullstack Project (Fulltime Work)
image: /uploads/cash-advance-accountability-admin-summary.png
---
Work Period of Project: 6th October 2026 – 12th October 2026

The works I did in this Cash Advance Accountability menu:

![](/uploads/cash-advance-accountability-admin-summary.png){: width="1893" height="749"}

If user login as AP Admin, we can see the total of BON (Cash Advance) that haven’t had PJBS (Cash Advance Accountability), total of PJBS, total of Pending PJBS, and total of Fully Approved PJBS.

![](/uploads/cash-advance-accountability-form.png){: width="1893" height="749"}

User also can fill the form before submit the PJBS. “BON Sementara” (Cash Advance) selection has list of Fully Approved BON Sementara (Cash Advance). “TGL” field is today date by default. “Ajukan PJBS” button is disabled unless user input in one column of expense detail rows, but one full row filled is required. User can delete one of expense detail rows by clicking (x) in the edge of each row. User also can add a new row of expense detail by clicking “Tambah Baris”. “Reset Form” is used for clearing all inputs or selections in the form.

![](/uploads/cash-advance-accountability-validation.png){: width="1893" height="749"}

And there is validation if Bon Sementara Selection is left empty because it’s required, all the read only fields below it will automatically filled once it’s filled.

![](/uploads/cash-advance-accountability-matched.png){: width="1893" height="749"}

![](/uploads/cash-advance-accountability-more.png){: width="1893" height="749"}

![](/uploads/cash-advance-accountability-less.png){: width="1893" height="749"}

“Pengeluaran Total” will show amount of Jumlah, if it’s bigger than Bon Sementara (copy permohonan), “Status Selisih” will show “Kekurangan Biaya”. If it’s less than Bon Sementara (copy permohonan), “Status Selisih” will show “Kelebihan/Uang Dikembalikan”. And if it’s matched with Bon Sementara (copy permohonan), “Status Selisih” will show “Nihil/Sesuai BON”.

![](/uploads/cash-advance-accountability-confirmation.png){: width="1893" height="749"}

There would be a confirmation when user click “Ajukan PJBS” to avoid false data.

![](/uploads/cash-advance-accountability-successful-submit.png){: width="1893" height="749"}

If the submission is successful there will be a green bar notification with check. And the new row will show up on the top of rows in the table with status “Waiting Supervisor” and Current Approver is “Supervisor”.

![](/uploads/cash-advance-accountability-search-filter-admin.png){: width="1893" height="749"}

User can search based on No. PJBS, No. Bon, and Penanggung Jawab. User also can filter based on status, “Pending Approval” is for all statuses start with “Waiting”. Status “Fully Approved” will show rows with status “Fully Approved” and status “Rejected” will show rows with status “Rejected”.

![](/uploads/cash-advance-accountability-admin-print-form-no-history.png){: width="1893" height="749"}

“Form” button in table rows will have the details information of the row, signature columns, and Riwayat Management Approval which ready to print, if the Current Approver is Supervisor there will be no Riwayat Management Approval since Supervisor is the first Approver, means there is no Approver before Supervisor.

![](/uploads/cash-advance-accountability-print-review.png){: width="1893" height="749"}

“Print Form” button will show how the form will look like when it’s printed and user can click “Print” to print the form.

![](/uploads/cash-advance-accountability-admin-manage-approval-no-approval.png){: width="1903" height="733"}

And “Manage Approval” button in table rows will have the approval workflow and Audit Approval Batch besides the details information.

![](/uploads/cash-advence-accountability-approver-summary.png){: width="1903" height="733"}

If user login as Supervisor/General Manager Finance/Director Finance, we can see the total of PJBS, total of Pending PJBS, total of Fully Approved PJBS, and total of Rejected BON. User can search by No. PJBS, No. Bon, and Penanggung Jawab. User can filter based on status, “Pending Approval” is for all statuses start with “Waiting”. Status “Fully Approved” will show rows with status “Fully Approved” and status “Rejected” will show rows with status “Rejected”. And user also can filter based on current approval; “Supervisor”, “Manager”, “General Manager Finance”, and “Director Finance”.

![](/uploads/cash-advance-accountability-approver-print-form-no-history.png){: width="1903" height="733"}

“Form” button for Approver in table rows will show the same as AP Admin, it will have the details information of the row, signature columns, and Riwayat Management Approval which ready to print.

![](/uploads/cash-advance-accountability-approver-manage-approval-no-approval.png){: width="1899" height="903"}

“Manage Approval” button for Approver in table rows will also have the approval workflow and Audit Approval Batch besides the details information, but as well as the note column that is required to fill before deciding to “Approve” or “Reject”.

![](/uploads/cash-advance-accountability-approver-manage-approval-approve.png){: width="1899" height="893"}

After Approver filled the note column and clicked “Approve”, there will also be a green bar notification with check, then the note column and buttons will be disabled, besides, the workflow and Audit Approval Batch will be moving from previous Approver to the next Approver, the status also will change to be “Waiting <NextApprover>”.

![](/uploads/cash-advance-accountability-approver-manage-approval-reject.png){: width="1899" height="893"}

If Approver filled the note column and clicked “Reject”, there will be a blue bar notification with info icon, then the note column and buttons will also be disabled, besides, the workflow and Audit Approval Batch will show Rejected from Current Approver, the status also will change to be “Rejected”.

![](/uploads/cash-advance-accountability-approver-manage-approval-full-approved.png){: width="1899" height="893"}

The last “Approve” will show status and Audit Approval Batch to be “Fully Approved”.

![](/uploads/cash-advance-accountability-admin-status-current-approver-table.png){: width="1899" height="893"}

![](/uploads/cash-advance-accountability-approver-status-current-approver-table.png){: width="1899" height="893"}

Both tables either for AP Admin or Approver will show the same, current approver for “Rejected” status will be “Ditolak”, “Fully Approved” status will be “Selesai”, and “Waiting <NextApprover>” status will be the next Approver.

![](/uploads/cash-advance-accountability-admin-print-form-with-history.png){: width="1899" height="893"}

![](/uploads/cash-advance-accountability-approver-print-form-with-history.png){: width="1899" height="893"}

If the Current Approver is not Supervisor, both forms either for AP Admin or Approver will show Riwayat Management Approval with the histories of previous Approver; including the role, decision status, date and time, also the note from the Approver.

> ###### ​​​​​​​![](/uploads/information-technology-icon-clipart-1-1-1.png){: width="200" height="200"}

The technologies I use in this feature:<br>\- React.js (functional/hooks).<br>\- React Router DOM.<br>\- Material UI (MUI).<br>\- Dayjs.<br>\- Formik & Yup.<br>\- JWT Decode.<br>\- Notistack & SweetAlert2.<br>\- React to Print.<br>\- MySQL.<br>\- Express.js.<br>\- Node.js.<br>\- Joi.<br>\- JSON Web Token.