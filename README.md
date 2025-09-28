# 🎬 YouTube Auto Uploader

**Automate your YouTube video uploads with ease!** A powerful desktop application that monitors folders, queues videos, and uploads them automatically to YouTube with customizable settings.

---

## 📥 **DOWNLOAD LATEST VERSION**

### **[⬇️ Download YouTube Auto Uploader v1.0.1](https://github.com/NathanLCleary/YouTube-Auto-Uploader-Public/releases/latest)**

**File Size**: ~36MB | **Platform**: Windows 10/11 (64-bit) | **License**: Free for Personal Use

---

## ✨ **KEY FEATURES**

### 🤖 **Automated Workflow**
- **Folder Monitoring** - Automatically detects new videos in watch folders
- **Smart Queuing** - Organizes uploads with priority and scheduling
- **Batch Processing** - Upload multiple videos simultaneously
- **Auto-Retry Logic** - Handles failed uploads with intelligent retry system

### 🎮 **Gaming Integration**
- **Game Detection** - Pauses uploads during competitive gaming sessions
- **Performance Mode** - Low-priority processing to avoid frame drops
- **Custom Game Lists** - Configure which games trigger pause mode

### 🎨 **User Experience**
- **Modern GUI** - Clean, intuitive desktop interface
- **System Tray** - Runs quietly in background with tray notifications
- **Hotkey Support** - Quick access with customizable keyboard shortcuts
- **Real-time Monitoring** - Live upload progress and status updates

### ⚙️ **Advanced Configuration**
- **Template System** - Save and reuse video metadata templates
- **Auto-Title Generation** - Smart title creation based on file names
- **Privacy Controls** - Set default privacy levels and playlist assignments
- **File Management** - Auto-delete local files after successful upload

---

## 🖥️ **SYSTEM REQUIREMENTS**

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **RAM** | 4GB | 8GB+ |
| **Storage** | 100MB free space | 500MB+ |
| **Internet** | Stable broadband | High-speed broadband |
| **YouTube** | Google account with API access | YouTube channel |

---

## 📋 **COMPLETE INSTALLATION GUIDE**

### **Step 1: Download & Extract**
1. Click the download link above
2. Extract the ZIP file to a permanent location (e.g., `C:\YouTubeAutoUploader\`)
3. **Important**: Don't run from temporary folders or Downloads

### **Step 2: Get YouTube API Credentials**
**This is REQUIRED - the app won't work without it!**
**Note: During this step, please ensure you are signed into the correct Google account. Not doing so may result in uploading videos to a different Youtube channel**
1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select existing project
3. **Enable APIs**:
   - Search for "YouTube Data API v3"
   - Click "Enable"
4. **Create Credentials**:
   - Go to "Credentials" → "Create Credentials" → "OAuth 2.0 Client IDs"
   - Choose "Desktop Application"
   - Name it "YouTube Auto Uploader"
5. **Download JSON**:
   - Click the download button next to your credential
   - Rename the file to `client_secret.json`
   - Place it in the same folder as `YouTubeAutoUploader.exe`

### **Step 3: First Run Setup**
1. **Right-click** `YouTubeAutoUploader.exe` → **"Run as Administrator"** (first time only)
2. The app will create necessary folders and configuration files
3. **Authenticate**: Browser will open for YouTube account authorization
4. **Configure Settings**: Set your watch folder, upload preferences, etc.

### **Step 4: Auto-Startup Configuration**
**To run automatically when Windows starts:**

#### **Method 1: Built-in Auto-Startup (Recommended)**
1. Open the app settings
2. Check "Start with Windows"
3. The app will copy itself to the Windows startup folder

#### **Method 2: Manual Startup Setup**
1. Press `Win + R`, type `shell:startup`, press Enter
2. Copy `YouTubeAutoUploader.exe` to this folder
3. Or create a shortcut to the exe in this folder

#### **Method 3: Task Scheduler (Advanced)**
1. Open Task Scheduler (`taskschd.msc`)
2. Create Basic Task → "Start a program"
3. Point to `YouTubeAutoUploader.exe`
4. Set trigger to "When I log on"
5. Check "Run with highest privileges"

---

## 🎯 **QUICK START GUIDE**

### **Basic Workflow**
1. **Set Watch Folder**: Choose where you save videos (e.g., OBS recordings folder)
2. **Configure Defaults**: Set default title, description, tags, privacy level
3. **Start Monitoring**: Enable auto-upload and let it run in background
4. **Drop Videos**: Save videos to watch folder → automatic upload begins

### **Pro Tips**
- Use **template system** for consistent metadata across videos
- Enable **game detection** if you're a content creator
- Set **auto-delete** to save disk space after uploads
- Use **hotkeys** for quick access while gaming/recording

---

## 🛠️ **TROUBLESHOOTING**

### **Common Issues & Solutions**

#### **❌ App Won't Start**
- **Run as Administrator** (right-click exe → "Run as administrator")
- **Check antivirus** - add exe to exclusions if blocked
- **Verify extraction** - ensure all files extracted properly
- **Windows Defender** - allow app through SmartScreen

#### **❌ "No client_secret.json" Error**
- **Download credentials** from Google Cloud Console
- **Rename file** to exactly `client_secret.json`
- **Place in same folder** as the exe file
- **Check file permissions** - ensure it's readable

#### **❌ Upload Failures**
- **Check internet connection** - ensure stable broadband
- **Verify YouTube quota** - API has daily limits
- **File format support** - use MP4, AVI, MOV, MKV, FLV, WMV
- **File size limits** - YouTube has upload size restrictions

#### **❌ Performance Issues**
- **Enable low priority mode** in settings
- **Reduce concurrent uploads** (default: 1)
- **Close unnecessary programs** during uploads
- **Check disk space** - ensure sufficient free space

#### **❌ Authentication Problems**
- **Clear browser cache** and retry authorization
- **Use incognito/private mode** for authentication
- **Check Google account permissions** in account settings
- **Regenerate credentials** if persistent issues

---

## 🎫 **SUPPORT & BUG REPORTS**

### **Get Help**

#### **📋 Create a Support Ticket**
**[🎫 Open Support Ticket](https://github.com/NathanLCleary/YouTube-Auto-Uploader-Public/issues/new?template=support_request.md)**

**When reporting issues, please include:**
- Windows version (e.g., Windows 11 22H2)
- App version (check About dialog)
- Error messages (exact text or screenshots)
- Steps to reproduce the problem
- Log files (if available)

#### **🐛 Report Bugs**
**[🐛 Report Bug](https://github.com/NathanLCleary/YouTube-Auto-Uploader-Public/issues/new?template=bug_report.md)**

#### **💡 Feature Requests**
**[💡 Request Feature](https://github.com/NathanLCleary/YouTube-Auto-Uploader-Public/issues/new?template=feature_request.md)**

#### **📧 Direct Contact**
- **Email**: nathanlcleary@gmail.com
- **Response Time**: Usually within 24-48 hours
- **Priority Support**: Available for critical issues

---

## 📊 **VERSION HISTORY**

### **v1.0.1 (Current) - 2024-09-28**
- ✅ Fixed app data file handling
- ✅ Improved error handling and stability
- ✅ Enhanced setup instructions
- ✅ Better credential security

### **v1.0.0 - 2024-09-28**
- 🎉 Initial public release
- ✨ GUI interface with video management
- ⚡ Automated upload scheduling
- 📊 Real-time monitoring system
- 🔄 Batch processing capabilities
- 🎮 Gaming integration features

---

## 🔒 **PRIVACY & SECURITY**

### **Your Data is Safe**
- ✅ **No data collection** - Zero telemetry or analytics
- ✅ **Local processing** - Everything happens on your computer
- ✅ **Secure credentials** - API keys stored locally only
- ✅ **No cloud dependency** - Works entirely offline (except YouTube uploads)
- ✅ **Open source approach** - Transparent development process

### **What Data is Used**
- **YouTube uploads only** - Video files and metadata sent to YouTube
- **Local settings** - Preferences stored in local files
- **Upload history** - Tracked locally for queue management
- **No personal data** - No collection of personal information

---

## 📄 **LICENSE & TERMS**

**Free for Personal Use** - This software is provided free of charge for personal, non-commercial use.

**Commercial Use** - Contact for licensing if using in commercial environments.

**Disclaimer** - Software provided "as-is" without warranty. Use at your own risk.

---

## 🚀 **GET STARTED TODAY!**

### **[⬇️ Download YouTube Auto Uploader v1.0.1](https://github.com/NathanLCleary/YouTube-Auto-Uploader-Public/releases/latest)**

**Ready to automate your YouTube uploads?** Download now and start saving hours of manual upload time!

---

*Made with ❤️ for content creators who want to focus on creating, not uploading.*
