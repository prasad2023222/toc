# toc

Create a simple and professional PowerPoint presentation for a **Manufacturing Quality Management System (QMS) – Document Change Request (DCR) Module**.

Keep it business-focused and easy to understand. Do not include programming, database, API, or technical implementation details.

### Slide 1 – Title

**Manufacturing QMS – Document Change Request (DCR)**
Subtitle: Controlled Document Management

### Slide 2 – Purpose

The DCR module manages the creation and modification of controlled documents.

Objectives:

* Manage new documents
* Manage changes to existing documents
* Approval/rejection workflow
* Automatic revision management
* Correct ISO document storage
* Master Table maintenance
* Complete document history

### Slide 3 – Two Types of DCR

**1. New Document DCR**

* Employee wants to create a completely new document
* System assigns a new Document Number
* Example: `PROD-WI-001`

**2. Existing Document DCR**

* Employee wants to modify an existing document
* Document Number remains the same
* Revision number increases after approval

Example:

`PROD-WI-001 Rev 1 → PROD-WI-001 Rev 2`

### Slide 4 – New Document DCR Flow

Show:

**Employee Creates New DCR**
↓
**Enter Document Details**
↓
**Upload Document**
↓
**Submit**
↓
**Reviewer**
↓
**Approve / Reject**

If Approved:
↓
**Assign New Document Number**
↓
**Calculate Page Count**
↓
**Save Document in ISO Folder → Correct Department**
↓
**Add Document to Master Table**

### Slide 5 – Existing Document DCR Flow

Example:

Current document:

**Document No: PROD-WI-001**
**Revision: 1**
**Pages: 5**

Employee submits a change.

↓

**Upload Updated Document**

↓

**Reviewer Approves**

↓

System creates:

**PROD-WI-001 – Revision 2**

↓

**Save approved document in ISO Folder → Correct Department**

↓

**Update Master Table**

### Slide 6 – Approval Process

Reviewer checks:

* Department
* Document details
* Reason for change
* Uploaded document
* Page count
* Other required information

Two options:

**Approve**
→ Continue document update process

**Reject**
→ Enter rejection reason
→ DCR closed
→ Master Table remains unchanged
→ Document is not published as an approved document

### Slide 7 – After Approval

Clearly show that **three important actions happen after approval**:

**1. Revision / Document Number**

* New document → assign new Document No.
* Existing document → create next Revision

**2. ISO Folder Storage**

* Approved document is saved automatically
* Inside the correct ISO folder
* Inside the correct Department folder

Example:

**ISO Folder**
→ **Production**
→ **Work Instructions**
→ **PROD-WI-001 Rev 2**

**3. Master Table Update**

* Document Number
* Revision
* Page Count
* Revision Date
* Status

### Slide 8 – Master Table Example

Show:

| Document No | Revision | Pages | Revision Date | Status     |
| ----------- | -------: | ----: | ------------- | ---------- |
| PROD-WI-001 |        1 |     5 | 05-03-2026    | Superseded |
| PROD-WI-001 |        2 |     7 | 08-10-2026    | Current    |

Explain:

**The Document Number remains the same.
The Revision, Pages, Date and Status are updated after approval.**

For a new document:

| Document No | Revision | Pages | Revision Date | Status  |
| ----------- | -------: | ----: | ------------- | ------- |
| PROD-WI-002 |        1 |     6 | 08-10-2026    | Current |

### Slide 9 – Complete DCR Workflow

Show one clear end-to-end diagram:

**Employee**
↓
**Create DCR**
↓
**New Document OR Existing Document**
↓
**Upload Document**
↓
**Submit**
↓
**Reviewer**
↓
**Approve / Reject**

If **Rejected**:
→ Rejection Reason
→ DCR Closed
→ No Master Table Update
→ No Approved Document Storage

If **Approved**:
→ Document No. / New Revision
→ Calculate Page Count
→ Save to **ISO Folder → Correct Department**
→ Update **Master Table**
→ Keep Previous Revision as History
→ DCR Completed

### Slide 10 – Benefits

* Easy document submission
* Controlled approval process
* Automatic revision management
* Automatic page count
* Correct ISO folder storage
* Master Table automatically maintained
* Previous revisions preserved
* Better traceability
* Less manual work
* Controlled document lifecycle

### Design Requirements

Use a clean, simple corporate manufacturing/QMS style.

Use flowcharts, icons, and simple tables.

Keep text minimal and easy to understand.

The most important message of the presentation should be:

**DCR Submitted → Reviewed → Approved → New Document/Revision Created → Saved in Correct ISO Department Folder → Master Table Updated**

Do not include code, database design, API architecture, or other technical implementation details.
