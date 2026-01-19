# Request Attacker - Custom Repeater Action (Bambda Script)

**Request Attacker** is a Burp Suite Bambda script for Custom Repeater Action that lets you instantly fuzz and perform various attacks on request.

## Features
- Performs attacks one by one - You can add/remove your attacks as well.
- Fast, scriptable, and useful for quick checks during manual testing.
- Modify as Per Need - Add/remove payloads and checks as per requirements
- You can modify the delay between requests as well.

1. Clone this repo.
2. Open Burp Suite.
3. Navigate to **Extender → Bambda Scripts**.
4. Click **"Load"**, select `request-attacker.bambda`.
5. Set Location as `Custom Action` and `Repeater`, see the video
6. Select a request in **Repeater** context.
7. Run the script to send all payloads and view responses.

> You can customize or extend the payload list directly in the script.
> 
> You can add/remove attacks types as well, i.e commenting out the payloads for invalid date will not perform that check.
> 
> Note: This is not replacement of intruder/scanner, it is just a custom action for repeater to solve very specific issue of automation of manual test cases. Read the script before running and check if it matches your use case.
>
> It is not new ground breaking tool or anything like that.

