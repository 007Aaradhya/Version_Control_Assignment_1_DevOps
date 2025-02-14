# Version Control Assignment 1 - DevOps

## **Project Overview**
This project demonstrates the usage of **Subversion (SVN)**, **Mercurial (HG)**, and **Git** as version control systems. It includes step-by-step execution of commands along with explanations and screenshots. The assignment is hosted on **GitHub Pages** for easy access.

---

## **1. Contents of the Repository**
This repository contains the following files:
- **Aaradhya_500108360_Assignment1_DevOps.pdf** - Detailed documentation with commands, explanations, and screenshots.
- **README.md** - This file, explaining the project structure and usage.
- **Screenshots/** - (If applicable) Screenshots of executed commands.
- **demonstration_video.mp4** - (If applicable) Screen recording of the version control demonstration.

---

## **2. Demonstration of Version Control Systems**
### **Subversion (SVN) Commands**
```sh
svnadmin create my_svn_repo
svn checkout file:///path/to/my_svn_repo my_working_copy
cd my_working_copy
echo "Hello SVN" > file.txt
svn add file.txt
svn commit -m "Initial commit"
svn log
```

### **Mercurial (HG) Commands**
```sh
hg init my_hg_repo
cd my_hg_repo
echo "Hello Mercurial" > file.txt
hg add file.txt
hg commit -m "Initial commit"
hg log
```

### **Git Commands & GitHub Hosting**
```sh
git init
git add README.md Aaradhya_500108360_Assignment1_DevOps.pdf
git commit -m "Initial commit"
git remote add origin https://github.com/007Aaradhya/Version_Control_Assignment_1_DevOps.git
git branch -M main
git push -u origin main
```

---

## **3. Hosted GitHub Pages**
The assignment is hosted on GitHub Pages. You can access the PDF documentation here:
🔗 **[Assignment PDF](https://007aaradhya.github.io/Version_Control_Assignment_1_DevOps/Aaradhya_500108360_Assignment1_DevOps.pdf)**

---

## **4. How to Use This Repository?**
1. Clone the repository:
   ```sh
   git clone https://github.com/007Aaradhya/Version_Control_Assignment_1_DevOps.git
   ```
2. Navigate to the repository folder:
   ```sh
   cd Version_Control_Assignment_1_DevOps
   ```
3. View the documentation file:
   - Open **Aaradhya_500108360_Assignment1_DevOps.pdf** to read the assignment.
   - Access it directly via **GitHub Pages**.

---

## **5. Conclusion**
This assignment successfully demonstrates the usage of version control systems and GitHub Pages hosting. The commands were executed, and the results were documented with screenshots.

---

### **Prepared by:**
**Aaradhya Agrawal**  
**Submission to:** Mr. Prateek Raj Gautam

