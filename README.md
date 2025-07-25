# Instagram Insights Analyzer

A secure, client-side web tool to analyze your Instagram followers and following data. This tool allows you to upload your official Instagram data export to see mutual relationships, identify users who don't follow you back, and view when these connections were made. All data processing happens directly in your browser, ensuring your information remains private.

## ✨ Features

* **🔒 Secure & Private:** Your Instagram data files are processed locally in your browser and are never uploaded to any server.

* **📊 Data Analysis:** Get a quick overview with summary cards for your total followers, following count, mutuals, and users who don't follow you back.

* ** Interactive Table:** View a combined list of all users from your followers and following lists.

* **✅ Relationship Status:** Clearly see your relationship with each user:

  * **Mutual:** You follow each other.

  * **Not Following Back:** You follow them, but they don't follow you.

  * **Following You:** They follow you, but you don't follow them back.

* **🗓️ Timestamp Data:** See the date you followed someone and the date they followed you in separate columns.

* **🔍 Search & Filter:** Instantly search for any username and filter the table by relationship status.

* **⇅ Sortable Columns:** Sort the entire table by username, status, or either of the timestamp columns.

* **📤 Data Export:** Export your current filtered and sorted view to various formats including TXT, CSV, JSON, and HTML.

## 🚀 How to Use

1. **Download Your Data from Instagram:**

   * You must request your data directly from Instagram. Go to your Instagram profile and navigate to **Settings → Accounts Center → Your Information and Permissions**.

   * Click on **Download Your Information** and then use the [Request a download](https://www.instagram.com/download/request) link.

   * When requesting, make sure to select only **Followers and following** for the information type, **JSON** for the format, and **All time** for the date range.

   * Instagram will email you a link to download a `.zip` file. Unzip it to find `followers_1.json` and `following.json`.

2. **Open the Tool:**

   * Simply open the `index.html` file in your web browser (like Chrome, Firefox, or Safari).

3. **Load Your Files:**

   * Use the file input fields to select your `followers_1.json` and `following.json` files.

4. **Analyze:**

   * Click the "Analyze Data" button and the tool will process your files and display the results.

## 🛠️ Technologies Used

* **HTML5:** For the basic structure of the web page.

* **Tailwind CSS:** For modern and responsive styling.

* **JavaScript (ES6):** For all client-side logic, including file reading, data processing, and DOM manipulation. No external libraries or frameworks are needed.
