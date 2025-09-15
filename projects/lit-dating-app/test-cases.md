# LIT Dating App – Sample Test Cases

| ID   | Title                          | Precondition           | Steps                                                                    | Expected Result                                      | Status |
|------|--------------------------------|------------------------|-------------------------------------------------------------------------|------------------------------------------------------|--------|
| TC01 | User signup with valid data    | App installed          | 1. Launch app <br> 2. Tap "Sign Up" <br> 3. Enter valid info <br> 4. Submit | User account created, redirected to profile setup    | Pass   |
| TC02 | Swipe right on profile         | User logged in         | 1. Open app <br> 2. Swipe right on profile                                | Profile marked as “Liked”                           | Pass   |
| TC03 | Chat message delivery          | Two users matched      | 1. User A sends message to User B <br> 2. User B receives notification   | Message delivered instantly, notification triggered | Pass   |
| TC04 | App crash on profile picture   | User uploading image   | 1. Go to Profile <br> 2. Upload high-resolution picture                   | App should resize/upload image without crash         | Fail   |
