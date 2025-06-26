
### ✅ **Solution to Link Battery Sample Documents with Metadata in Power BI**

To ensure each battery sample and its related documents (test reports, certificates, images) can be tracked and reported in Power BI, I followed this structured approach:

---

### **Step 1: Create Metadata in Microsoft Lists**

* I created an Excel sheet containing metadata like SampleId,	SampleName,DateCollected, BatchNumber, TestLocation,	Technician,	Manufacturer,	TestType,	Result,	and Comments.
* This data was uploaded into a **Microsoft List** to store and manage sample records in a structured way.

---

### **Step 2: Upload Documents to SharePoint Library**

* I uploaded sample-related documents (e.g., `BAT001_Report.pdf`, `BAT001_Image.jpg`) to a **SharePoint Document Library**.
* A **SampleId column** was added to the library and made **mandatory** for all uploads, ensuring correct linkage to each sample.

---

### **Step 3: Import and Transform Data in Power BI**

* Both the Microsoft List and SharePoint Library were connected to **Power BI**.
* I applied transformations like:

  * Setting correct data types
  * Removing unnecessary columns
  * Creating **relationships** using `SampleId`
  * Grouping or merging data as needed

---

### **Step 4: Build Interactive Report**

* In Power BI, I created a report with:

  * A **SampleId slicer** for quick filtering
  * Tables showing metadata and clickable links to documents
* This allows users to enter a SampleId and instantly view all related details and files.

---

### ✅ Final Result

This setup ensures every sample and its documents are fully linked, searchable, and viewable within Power BI for easy tracking and reporting.

