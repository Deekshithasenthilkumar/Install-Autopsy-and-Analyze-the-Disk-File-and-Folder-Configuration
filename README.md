# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results


<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/3e3c25ec-5e99-401d-9e69-cb612919c123" />

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/58a4a600-41c4-4766-965f-d3ff79e189d7" />

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/f36f3737-d4ac-4a80-a70d-b7f76b22a0f1" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/476668cf-a9ee-417e-a7e2-db32ea5dd8f5" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/e81fb119-ddc0-4290-a809-fb2663b4690d" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/eea5bdf0-84ee-4b0c-b948-d4e4dc228ed9" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/cca424b9-39a3-44c9-98fc-cbb061d24808" />






## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
