# AI Resume Maker – Sample Test Cases

| ID   | Title                          | Precondition            | Steps                                                                 | Expected Result                                     | Status |
|------|--------------------------------|-------------------------|----------------------------------------------------------------------|-----------------------------------------------------|--------|
| TC01 | Create resume with template    | User logged in          | 1. Launch app <br> 2. Select template <br> 3. Enter details <br> 4. Save | Resume generated with selected template             | Pass   |
| TC02 | Export resume as PDF           | Resume created          | 1. Open resume <br> 2. Tap "Export" <br> 3. Choose PDF                | PDF downloaded successfully                         | Pass   |
| TC03 | Export without entering data   | User skips input        | 1. Select template <br> 2. Skip entering data <br> 3. Tap "Export"     | Error shown: “Please complete required fields”      | Pass   |
| TC04 | Special characters in name     | User enters invalid data| 1. Enter name: “@@@” <br> 2. Save resume                             | Error message shown, no crash                       | Fail   |
