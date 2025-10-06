# Maryland IRC Support Letter Generator

**Live Tool:** https://w4ester.github.io/supportletters/

A streamlined web application that enables Maryland businesses to generate professional Industry-Recognized Credential (IRC) support letters in approximately 3 minutes.

---

## 📋 **Purpose**

The Maryland State Department of Education requires **2 letters of support per IRC** from different businesses for credential approval. This tool eliminates the traditional barriers (time, formatting complexity, unclear requirements) by providing an automated, guided process that ensures compliance with all MSDE requirements.

---

## ✅ **MSDE Requirements Met**

This tool ensures every generated letter meets all mandatory requirements:

1. ✅ **Company letterhead** - Logo upload and professional formatting
2. ✅ **Explicit hiring statement** - Letters automatically include: *"We actively look for [credential] when hiring"*
3. ✅ **Multiple credentials per letter** - Businesses can select multiple certifications in one letter
4. ✅ **Professional format** - Ready for immediate submission
5. ✅ **BLS employment data** - All letters include 2024 Bureau of Labor Statistics data (median wages, job openings, growth projections)
6. ✅ **Auto-email submission** - One-click send to occpcteprograms.msde@maryland.gov

---

## 🎯 **Supported Credentials (21 Total)**

### **Arts, Entertainment, and Design**
- Autodesk Certified Professional: 3ds Max (Animation and Game Design)
- Autodesk Certified User in Maya (Animation and Game Design)
- Apple Certified Pro: Final Cut Pro (Video and Audio Production)

### **Digital Technology**
- Microsoft Certified: Azure Data Scientist Associate (Machine Learning and Data Science)
- CompTIA A+
- CompTIA Network+
- CompTIA Security+
- CompTIA Cloud+
- CompTIA Data+ (Machine Learning and Data Science)
- AWS Certified Cloud Practitioner
- AWS Certified Solutions Architect – Associate

### **Health and Human Services**
- DANB Radiation Health and Safety (RHS) (Dental Assistant)
- NHA Certified Phlebotomy Technician (CPT)
- NHA Certified Clinical Medical Assistant (CCMA)
- NHA Certified Patient Care Technician (CPCT) (Physical Rehabilitation)
- NHA Certified Pharmacy Technician (CPhT)

### **Supply Chain and Transportation**
- ASE Automotive / Medium-Heavy Truck Certifications (T1-T8: All 8 truck certifications)

### **Architecture & Construction**
- HVAC Excellence Certifications

### **Financial Services**
- Microsoft Excel Expert 365/2019 (Financial Services and Accounting)

### **Management and Entrepreneurship**
- PMI Project Management Professional (PMP)
- PMI Certified Associate in Project Management (CAPM)

### **Public Service and Safety**
- IAEM Associate Emergency Manager (AEM) (Emergency Response)
- IAEM Certified Emergency Manager (CEM) (Emergency Response)
- FEMA Community Emergency Response Team (CERT) (Emergency Response)

---

## 🚀 **How It Works**

### **For Businesses (3-minute process):**

1. **Select Credential(s)**
   - Choose from dropdown menu
   - Can select multiple credentials (hold Ctrl/Cmd)
   - Example: Select all 8 ASE truck certifications in one letter

2. **Upload Company Logo** (Optional)
   - Drag & drop or click to upload
   - Supports PNG, JPG (max 2MB)
   - Logo appears on letter letterhead

3. **Enter Company Information** (5 simple fields)
   - Company/Organization name
   - Company address (optional)
   - Your name
   - Your title
   - Your email
   - Your phone (optional)

4. **Generate Letter**
   - Click "Generate Letter" button
   - Professional letter appears instantly with letterhead
   - Includes BLS employment data specific to credential
   - Includes explicit "we look for this certification when hiring" statement

5. **Submit to MSDE**
   - Click "Email Letter" button
   - Opens email client with:
     - **To:** occpcteprograms.msde@maryland.gov (pre-filled)
     - **Subject:** Letter of Support: [Credential Name] (pre-filled)
     - **Body:** Complete letter (pre-filled)
   - Alternatively: Copy to clipboard or print as PDF

---

## 📊 **Features**

### **Multi-Credential Support**
- ✅ One business can support multiple credentials in a single letter
- ✅ Hold Ctrl (Windows) or Cmd (Mac) to select multiple
- ✅ Perfect for: ASE (all 8 truck certs), Capitol Tech (multiple IT certs), etc.

### **BLS Employment Data Integration**
Every letter automatically includes 2024 Bureau of Labor Statistics data:
- Annual job openings nationally
- Median annual wage
- Projected growth rate (2024-2034)
- Occupation description

**Example Statistics Included:**
- CompTIA Security+: 16,000 openings, $124,910 median, 29% growth
- Azure Data Scientist: 23,400 openings, $112,590 median, 34% growth
- HVAC Excellence: 40,100 openings, $59,810 median, 8% growth
- Pharmacy Technician: Stable healthcare career prospects

### **Mobile Responsive**
- ✅ Works on desktop, tablet, and smartphone
- ✅ Businesses can complete on any device
- ✅ Perfect for busy professionals on-the-go

### **Professional Formatting**
- ✅ Times New Roman serif font
- ✅ Proper letter spacing and margins
- ✅ Print-ready / PDF-ready
- ✅ Professional business letter format

### **Privacy & Security**
- ✅ No data storage - all processing client-side
- ✅ No tracking or analytics
- ✅ Logo files processed in browser only
- ✅ Hosted on secure GitHub Pages (HTTPS)

---

## 📧 **Email Template for Businesses**

When reaching out to the 152 business contacts, use the customized email templates in `/email_letter.md` which are tailored by industry:

- **CVS Health Group** → Pharmacy Technician
- **Capitol Technology University** → All IT certifications
- **BGE** → HVAC, Electrical, Renewable Energy
- **Howard Community College** → All healthcare certifications
- **Construction Companies** → HVAC, Carpentry, Electrical, Plumbing
- **Cybersecurity Firms** → Security+
- **Media Professionals** → Final Cut Pro
- **And more...**

See `email_letter.md` for complete customized templates.

---

## 🎯 **Expected Outcomes**

### **Target: 38 Letters (2 per IRC × 19 programs)**

With 152 business contacts and this streamlined tool:
- **Reduced friction:** 30-minute task → 3-minute task
- **Higher response rate:** Easy process = more completions
- **Quality consistency:** All letters meet MSDE standards
- **Efficient tracking:** Clear subject lines for easy organization

### **Multi-Credential Strategy**
- One trucking company → All 8 ASE certifications (1 letter, 8 certs covered)
- Capitol Tech → Multiple IT certifications per department
- Healthcare facilities → Multiple NHA certifications
- Construction companies → Multiple trades certifications

---

## 🛠️ **Technical Details**

### **Technology Stack**
- **Frontend:** Pure HTML5, CSS3, JavaScript (ES6+)
- **Hosting:** GitHub Pages
- **Dependencies:** None (completely self-contained)
- **File Upload:** HTML5 FileReader API
- **Email:** Native mailto: protocol

### **Browser Compatibility**
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### **No Backend Required**
- All processing happens client-side in the browser
- No server costs or maintenance
- Instant deployment via GitHub Pages
- Works offline after initial page load

---

## 📁 **Repository Structure**

```
supportletters/
├── index.html              # Main application (complete standalone)
├── README.md              # This file
├── email_letter.md        # Customized email templates by industry
└── .github/
    └── workflows/         # GitHub Pages deployment (automatic)
```

---

## 🚀 **Deployment**

### **Live Site**
https://w4ester.github.io/supportletters/

### **Update Process**
1. Edit `index.html` in GitHub
2. Commit changes
3. GitHub Pages automatically deploys (1-2 minutes)
4. Changes live immediately

---

## 📞 **Support & Contact**

**William Forrester**  
Coordinator of School Programs  
Division of College and Career Pathways  
Maryland State Department of Education

📧 william.forrester@maryland.gov  
📞 (410) 767-0277  
🏢 200 W. Baltimore Street, Baltimore, MD 21201

---

## 📈 **Usage Instructions for MSDE Staff**

### **Sending to Business Contacts**

1. **Use customized email templates** from `email_letter.md`
2. **Send in batches of 25-30** to avoid spam filters
3. **Use BCC** (never CC - protect privacy)
4. **Track responses** in shared spreadsheet
5. **Follow up by phone** after 5 business days

### **Priority Groups (High Response Probability)**

**Week 1 Outreach:**
- CVS Health (5 contacts) → Pharmacy Technician
- Capitol Technology University (4 contacts) → All IT certs
- BGE (6 contacts) → HVAC, Electrical, Renewable Energy
- Howard Community College (2 contacts) → All healthcare

**Expected Result:** 10-15 letters from just these priority groups

---

## 🎓 **Benefits for Maryland Students**

### **Career Pathways Supported**
- 🎨 Animation & Game Design
- 🎬 Video & Audio Production
- 💻 Cybersecurity & IT
- 📊 Data Science & Analytics
- 🏥 Healthcare (5 different pathways)
- 🔧 Skilled Trades (HVAC, ASE)
- 💼 Business & Finance
- 🚨 Emergency Management

### **Economic Impact**
- **High-wage careers:** Many credentials lead to $75K-$125K+ median salaries
- **High-growth fields:** Several credentials in 20%+ growth occupations
- **Workforce pipeline:** Connects students to Maryland employers

---

## 🔄 **Version History**

### **v1.0 - October 2025**
- Initial release
- 19 IRC credential templates
- Multi-credential support
- BLS employment data integration
- Auto-email functionality
- Mobile responsive design

### **v1.1 - October 2025**
- Added Autodesk Maya template
- Added Microsoft Excel Expert template
- Updated CERT naming in Emergency Management
- Enhanced README documentation
- Reorganized credential groupings by career cluster

---

## ✨ **Key Differentiators**

**Why This Tool Works:**

1. **Removes Barriers:** 3 minutes vs. 30+ minutes traditional approach
2. **Ensures Compliance:** Every letter meets MSDE requirements automatically
3. **Industry-Specific:** BLS data proves economic value to committee
4. **Multi-Credential:** Businesses can efficiently support multiple certs
5. **Mobile-Friendly:** Complete on phone during lunch break
6. **Zero Training:** Intuitive interface requires no instructions

---

## 🎯 **Success Metrics**

**Goals:**
- ✅ 38+ letters collected (2 per IRC minimum)
- ✅ 80%+ of letters meet MSDE requirements (100% with this tool)
- ✅ 50%+ response rate from business contacts
- ✅ quick turnaround time for letter collection
