# IntelliHire 🚀

**Smart Hiring, Made Simple.**

IntelliHire is your AI-powered assistant for recruitment! It helps make hiring faster and easier by using an **advanced AI model** to automate time-consuming tasks like reviewing Job Descriptions (JDs) and CVs, shortlisting candidates, and preparing for interviews.

---

## ✨ IntelliHire: What It Does

Recruiting can be overwhelming. IntelliHire uses its **smart AI model** to help you:
* Quickly understand what each job requires.
* Automatically read and get key info from CVs (PDFs, images, text).
* Match the right CVs to the right jobs.
* Create a shortlist of the best candidates.
* Get ready to contact them for interviews.

---

## 🎯 The Problem We're Solving

**(Hackathon Problem ID: R1-05 - Enhancing Job Screening)**

Traditional hiring is tough:
* **Too Time-Consuming:** Recruiters can spend about **23 hours** screening CVs for just one hire (Eddy.com).
* **Costly & Slow:** Manual work makes hiring take longer and cost more.
* **Prone to Errors & Bias:** Humans can make mistakes or be unintentionally biased.
* **Hard to Scale:** Many companies get too many CVs to review them all properly (TestGorilla).

**Result:** Longer hiring times, higher costs, and potentially missing out on great talent.

---

## 💡 Our Solution: IntelliHire

IntelliHire tackles these issues with its "AI helper" agents:
1.  **Smart JD Analysis:** The AI understands job descriptions.
2.  **Efficient CV Processing:** The AI reads CVs and extracts key details.
3.  **Accurate Matching:** AI compares CVs to job needs.
4.  **Automated Shortlisting:** Creates a list of top candidates based on your rules.
5.  **Easy Interview Prep:** Helps you contact shortlisted candidates.

**Benefits:**
* Saves lots of time.
* More accurate and fair.
* Faster shortlisting.
* Lets recruiters focus on people, not paperwork!

---

## 🚀 Core Features

* **Easy Job Input:** Add job details and what you're looking for (skills, experience, etc.).
* **AI JD Helper:** Summarizes JDs and finds key requirements using our **trained AI model**.
* **CV Uploader:** Upload up to **10 CVs at once** (PDF, Word, text, images from camera/files).
* **AI CV Reader:** Extracts info from CVs using our **AI model**.
* **AI Matching:** Scores how well each CV fits the job.
* **Automated Shortlisting:** Creates a top candidate list based on your settings.
* **Interview Assistance:** Helps start the interview process.
* **History Tracking:** Saves all your jobs and shortlists.

---

## 🛠️ Tech Stack

* **App:** Flutter (Dart) – For Android & iOS.
* **Backend Logic:** Python Cloud Functions on Firebase – Securely runs our AI tasks.
* **AI Engine:** **A sophisticated trained AI model** (accessed securely from our backend).
* **Database:** Firebase Firestore – Stores all app data.
* **Login:** Firebase Authentication.

---

## 🌊 How IntelliHire Works (System Flow)

### High-Level Flowchart

*(This is where you'll insert your flowchart image!)*

**A quick text description of the flow:**
1.  Recruiter enters Job Details in the Flutter app.
2.  A Python Cloud Function uses the **AI model** to understand the JD & saves it.
3.  Recruiter uploads CVs in the app.
4.  Another Cloud Function uses the **AI model** to read each CV, compare it to the JD, and score it. Results are saved.
5.  Recruiter tells the app to create a shortlist.
6.  A Cloud Function applies the recruiter's rules to the scores and marks the top candidates.
7.  Recruiter views the shortlist and can start contacting candidates.

### Simple Architecture

* **Flutter App:** The part the recruiter uses.
* **Python Cloud Functions:** Secure "helpers" in the cloud that use the **AI model**.
* **Firebase:** Handles login and data storage.
* **AI Model (via API):** The "brain" that understands text and helps with analysis.

---

## 🤖 Our "AI Helper" Team (Logical Agents)

IntelliHire's smarts are organized into logical "agents" working in the backend:

* **JD Helper:** Understands JDs using the **AI model**.
* **CV Helper:** Reads CVs and extracts info using the **AI model**.
* **Matching Helper:** Compares CVs to JDs using the **AI model's** understanding.
* **Shortlisting Helper:** Applies recruiter rules to pick the top candidates.
* **Interview Helper:** Helps start the interview process (currently via your phone's email app).

---

## 📱 Application Screenshots

*(Add your app screenshots here! This helps people see what IntelliHire looks like.)*

* `[Screenshot of Login Screen]`
* `[Screenshot of Job Description Entry Screen]`
* `[Screenshot of CV Upload Interface (showing file/camera options)]`
* `[Screenshot of Candidate List with AI Scores]`
* `[Screenshot of Shortlisted Candidates View]`

---

## 📂 File Structure (A Quick Look)

### Flutter App (`lib/` folder)
