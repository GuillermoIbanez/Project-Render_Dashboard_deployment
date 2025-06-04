<div align="center">
  <h1>Guillermo Ibanez | 🚀 Dashboard Deployment on Render</h1>
  <h1><img src="https://user-images.githubusercontent.com/74038190/221352987-68da234d-4d62-4e9d-9d7f-098dc657c2dc.gif" width="700" height="150"></h1>
</div>


<br>
---

## 📋 Summary

<p>
  <strong>🎯 Main Goal:</strong> Successfully deploy a Python Dash financial dashboard to the web using Render's free hosting platform, making it accessible to anyone with an internet connection.
</p>

<p>
  This project demonstrates the complete process of taking a locally-developed dashboard and deploying it as a live web application. The focus is on the deployment methodology, troubleshooting common issues, and achieving a working public URL without any hosting costs.
</p>

---

## 🛠️ Technologies

<table>
  <tr>
    <td><strong>🐍 Backend & Framework</strong></td>
    <td>
      • Python 3.x<br>
      • Dash (Web framework)<br>
      • Pandas (Data processing)<br>
      • Plotly (Visualizations)
    </td>
  </tr>
  <tr>
    <td><strong>📊 Data & Libraries</strong></td>
    <td>
      • NumPy (Numerical computing)<br>
      • openpyxl (Excel file handling)<br>
      • xlrd (Legacy Excel support)
    </td>
  </tr>
  <tr>
    <td><strong>🌐 Deployment & Server</strong></td>
    <td>
      • Render (Cloud platform)<br>
      • Gunicorn (WSGI server)<br>
      • Git & GitHub (Version control)
    </td>
  </tr>
  <tr>
    <td><strong>💻 Development Tools</strong></td>
    <td>
      • Terminal/Command Line<br>
      • Text Editor (VS Code/TextEdit)<br>
      • Web Browser (Testing)
    </td>
  </tr>
</table>

---

## 📝 Methodology

### **🔧 Step 1: Repository Setup**
- 📁 Created GitHub repository with dashboard code
- 📄 Converted Jupyter notebook (.ipynb) to Python script (.py)
- 📊 Uploaded Excel data file to repository
- 🔗 Updated file paths for deployment environment

### **📦 Step 2: Dependencies Configuration**
- 📋 Created `requirements.txt` file
- 🔧 Specified exact package versions for compatibility
- ⚠️ Resolved numpy/pandas version conflicts
- 📚 Added missing Excel reading libraries (xlrd)

### **🌐 Step 3: Render Platform Setup**
- 🔗 Connected GitHub repository to Render
- ⚙️ Configured build and start commands
- 🐍 Set Python environment detection
- 🔄 Enabled automatic deployments on git push

### **🐛 Step 4: Troubleshooting & Fixes**
- 🔍 **Server Import Error:** Fixed gunicorn app:server reference
- 🌐 **Port Binding Issue:** Updated host configuration to 0.0.0.0
- 📊 **Data Loading Problem:** Resolved Excel file path and dependencies
- ⏱️ **Cold Start Optimization:** Understood free tier limitations

### **✅ Step 5: Deployment Success**
- 🎉 Achieved successful build and deployment
- 🔗 Generated public URL for dashboard access
- 🧪 Tested functionality and data visualization
- 📱 Verified cross-device compatibility

---

## 🌐 Dashboard

<div align="center">
  <h3>🎯 Live Demo</h3>
  <p>Click this link to check out the dashboard on your web browser:</p>
  <br>
  <a href="https://project-dashboards-2.onrender.com" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20View%20Live%20Dashboard-Visit%20Now-brightgreen?style=for-the-badge" alt="Live Dashboard">
  </a>
  <br><br>
  <p><em>⏳ Note: First load may take 1-2 minutes due to free tier cold start. For a more reliable deployment check out the AWS deployment I did <a href="https://github.com/GuillermoIbanez/Project-AWS_Dashboard_Deployment" target="_blank">here</a>.</em></p>
</div>

---

<div align="center">
  <p>
    <strong>💡 Project completed successfully!</strong><br>
    <em>From local development to live web application in 5 steps</em>
  </p>
</div>
