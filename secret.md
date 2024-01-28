# Secret

Just kidding, it's just notes.

---

## How to publish (Firefox):

1. **Prepare Your Extension:**

   - Ensure that your extension files (`manifest.json`, `content.js`, `icon.png`) are ready.
   - Test your extension locally to make sure it works as expected.

2. **Create a Developer Account:**

   - You need a Firefox Account to create a Firefox Developer account.
     If you don't have one, create it [here](https://addons.mozilla.org/en-US/firefox/users/register).
   - Once you have a Firefox Account,
     go to the [Mozilla Add-ons Developer Hub](https://addons.mozilla.org/en-US/developers/).

3. **Submit Your Extension:**

   - Click on "Submit a New Add-on" on the Mozilla Add-ons Developer Hub.
   - Upload the ZIP file containing your extension files.
   - Provide information about your add-on, such as the name, description, version, and compatible applications.

4. **Configure Distribution & Privacy:**

   - Set distribution options and privacy settings as per your preferences.

5. **Submit for Review:**

   - Once all required information is filled, submit your add-on for review.
   - The Mozilla Add-ons team will review your extension to ensure it complies with their policies.

6. **Wait for Approval:**
   - Approval times may vary, and you'll receive notification once your extension is approved.

Remember to follow the [Mozilla Add-ons policies and guidelines](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/Distribution_policies)
to ensure your extension complies with the guidelines.

Please note that this information is based on the state of things as of my last knowledge update in January 2022,
and there might have been changes to the process or policies since then.
Always refer to the latest Mozilla Add-ons documentation for the most accurate and up-to-date information.

---

**Load Extension in Firefox:**

1. Open Firefox and navigate to `about:debugging#/runtime/`.
2. Click on the "This Firefox" tab on the left sidebar.
3. Click the "Load Temporary Add-on..." button.
4. Navigate to the directory containing your extension files and select the `manifest.json` file.
5. Your extension will be loaded temporarily, and you'll see it listed in the "Temporary Extensions" section.

---

## Checking Firefox Extension Review Status

1. **Visit the Developer Hub:**
   Go to the [Mozilla Add-ons Developer Hub](https://addons.mozilla.org/en-US/developers/).

2. **Sign In:**
   Sign in with the account you used to submit the extension.

3. **Navigate to "Manage My Submissions":**

   - Once logged in, look for a menu or section that allows you to manage your submissions.
   - This section is typically labeled "Manage My Submissions" or something similar.

4. **Check the Status:**

   - In the "Manage My Submissions" section, you should see a list of your submitted extensions.
   - Look for the specific extension you submitted and check its status.
   - The status will indicate whether it's under review, if it's approved, or if there are any issues.

5. **Review Email Notifications:**
   - Additionally, Mozilla usually sends email notifications regarding the status of your extension review.
   - Check your email associated with your Mozilla account for any messages from Mozilla Add-ons.

Remember that the review process can take some time, and the duration may vary. If there are specific issues or additional information needed during the review, Mozilla may reach out to you through the Developer Hub or email.

If you encounter difficulties or need more detailed information, you can also contact the [Mozilla Add-ons team](https://support.mozilla.org/en-US/kb/add-on-support-report-issue) for assistance.

---

Check later if not working:

- [onHistoryStateUpdated Event](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/webNavigation/onHistoryStateUpdated)
- [onCompleted Event](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/webNavigation/onCompleted)
