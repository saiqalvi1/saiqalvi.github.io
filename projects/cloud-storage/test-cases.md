# Cloud Storage – Sample Test Cases

| ID   | Title                           | Precondition                        | Steps                                                                 | Expected Result                                | Status |
|------|---------------------------------|------------------------------------|----------------------------------------------------------------------|------------------------------------------------|--------|
| TC01 | Upload file to cloud            | User logged in, stable internet     | 1. Open app <br> 2. Tap "Upload" <br> 3. Select file <br> 4. Confirm | File appears in user’s cloud storage           | Pass   |
| TC02 | Restore file from backup        | File exists in backup               | 1. Open app <br> 2. Navigate to "Backups" <br> 3. Select file <br> 4. Restore | File restored to device successfully          | Pass   |
| TC03 | Network interruption on upload  | User uploading large file           | 1. Start file upload <br> 2. Turn off Wi-Fi mid-upload                | Upload paused, clear error message shown       | Fail   |
| TC04 | Login with invalid credentials  | App installed                       | 1. Launch app <br> 2. Enter wrong email/pass <br> 3. Tap Login        | Error: “Invalid username or password” shown    | Pass   |
