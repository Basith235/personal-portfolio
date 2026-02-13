# How to Upload Your Technical Report PDF

## ✅ **Link is Already Set Up!**

The "Technical Report" button for your Cobweb Channel project is now configured to open `cobweb-report.pdf`.

---

## 📝 **Steps to Add Your PDF:**

### **Option 1: Simple Local Method** (Recommended for Testing)

1. **Locate your PDF file** (your Cobweb Channel technical report)

2. **Rename it to:** `cobweb-report.pdf`

3. **Copy the file to your portfolio folder:**
   ```
   d:\CODING\portfoli1\
   ```

4. **That's it!** The link will work automatically when you click "Technical Report"

---

### **Option 2: GitHub Upload** (Recommended for Production)

1. **Create/Open GitHub Repository:**
   - Go to https://github.com
   - Create a new repository or use an existing one
   - Name it something like: `cobweb-thermal-analysis`

2. **Upload PDF:**
   - Click "Add file" → "Upload files"
   - Drag your PDF or click "choose your files"
   - Name it: `cobweb-coldplate-report.pdf`
   - Commit the changes

3. **Get the Link:**
   - Click on the uploaded PDF file
   - Click "Download" button (right side)
   - Copy the URL from your browser
   - It will look like: `https://github.com/YourUsername/cobweb-thermal-analysis/raw/main/cobweb-coldplate-report.pdf`

4. **Update index.html:**
   - Find line 919 in `index.html`
   - Replace `cobweb-report.pdf` with your GitHub URL

---

### **Option 3: Google Drive / Dropbox**

1. **Upload to Google Drive:**
   - Upload your PDF to Google Drive
   - Right-click → "Get link"
   - Set to "Anyone with the link can view"
   - Copy the link

2. **Convert to Direct Download:**
   - Change: `https://drive.google.com/file/d/FILE_ID/view?usp=sharing`
   - To: `https://drive.google.com/uc?export=download&id=FILE_ID`

3. **Update index.html:**
   - Replace `cobweb-report.pdf` with your Google Drive link

---

## 🎯 **Testing:**

1. Place your PDF in `d:\CODING\portfoli1\`
2. Rename it to `cobweb-report.pdf`
3. Visit http://localhost:3000
4. Click "Technical Report" on the Cobweb project
5. PDF should open in a new tab!

---

## 📌 **Tips:**

- **File size:** Keep PDFs under 10MB for web hosting
- **Naming:** Use lowercase, no spaces (use hyphens instead)
- **Format:** PDF is best for technical reports
- **Security:** Don't include sensitive/confidential information

---

## ❓ **If the Link Doesn't Work:**

1. Check the filename is exactly: `cobweb-report.pdf`
2. Check it's in the same folder as `index.html`
3. Check there are no spaces in the filename
4. Refresh your browser (Ctrl + F5)
