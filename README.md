# Cloud-Storage-Setup

**COMPANY NAME**: CODTECH IT SOLUTIONS

**NAME**: ANWAY DHARKAR

**INTERN ID**: CT08WPV

**DOMAIN**: CLOUD TECHNOLOGY

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTOSH

**DESCRIPTION**: 
🚀 Step 1: Create a Cloud Storage Bucket
                    Login to Google Cloud Console: https://console.cloud.google.com/.
                    Select your project (or create one if you haven't).
                    Navigate to Storage → Browser → Click + Create Bucket.
                    Bucket Name: Enter a globally unique name (my-unwritten-chapters).
                    Region: Choose a region close to you.
                    Storage Class: Choose Standard for this example.
                    Access Control: Select Uniform (simpler permissions).
                    Click Create.
                    ![Screenshot 2025-03-10 133323](https://github.com/user-attachments/assets/ba7c7de1-f323-488c-8966-dc5ec82effd3)

📂 Step 2: Upload Example Files
          Open your created bucket.
          Click Upload Files.
          Upload any example files (My words.PDF).
          Once uploaded, you should see the file in the list.
          ![Screenshot 2025-03-10 134348](https://github.com/user-attachments/assets/e5e79b38-e786-49d7-8189-9baab76828d1)

🔐 Step 3: Configure Access Permissions
            Go back to the bucket settings.
            Click Permissions.
            Click Add Principal.
            In the Principal field, enter:
            allUsers → To make it public.
            Under Role, select:
            Storage Object Viewer.
            Click Save.
            ![Screenshot 2025-03-10 140451](https://github.com/user-attachments/assets/f74b4209-407f-4240-86f9-714d3ec4466d)

🧪 Step 4: Test Public Access
           Go back to your file.
           Click on the file name → Copy Public URL.
           Open the URL in a private/incognito browser window.
           If the file opens without logging in, you’ve successfully configured it.
           ![Screenshot 2025-03-10 140615](https://github.com/user-attachments/assets/1057d7af-4683-4338-a8a4-2ede1365774e)
           


