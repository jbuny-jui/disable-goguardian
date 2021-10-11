# Disable GoGuardian

## If you have any questions, contact my discord at: hendy#6982

### Essentially, this bypass makes GoGuardian seem like an untrusted/dangerous extension, so Google will automatically block the extension from working.

1) Go to chrome://settings/certificates

2) Click on the "Authoritites" tab.

3) Scroll down to `org-amazon`

5) Once you click on `org-amazon`, a drop-down list will appear with things like: `Amazon Root CA 1` and `Amazon Root CA 2 `.

5) Click the three dots next to each item

6) Click "Edit"

7) A pop-up should appear, titled "Certificate Authority." 

### Note: I'm not 100% sure, but if you want to turn GoGuardian back on (for tests and stuff), just go to `Amazon Root CA 1`and `Amazon Root CA 2` and check the first two boxes of each category. Then, restart the chromebook. Still testing this, it may not work due to client-side lag. (also try visiting http://blocked.com-default.ws/) to retag the extensions.

8) Important: UNCHECK ALL 3 BOXES, then press "OK"

9) Repeat for all categories under Amazon

### Note: Reload the page and go back to `org-amazon`. The four certificates you just unchecked should look like this: ![image](https://user-images.githubusercontent.com/88973452/135337012-dc6263c8-02ce-4ad0-a05f-b646dd1485c1.png)

### If the categories don't have "UNTRUSTED," it's ok. Just keep going with the steps. This is merely a client-side display issue

10) Scroll down to `org-Starfield Technologies`.

11) Repeat what you did for the amazon certificates, open the drop-down, click "edit" from the three dots, and uncheck all boxes. ![image](https://user-images.githubusercontent.com/88973452/135337231-ee91930e-8c57-42b9-bfd5-70ceda77d2d7.png)

12) Close out of all applications and restart your chromebook by holding down the power button.

13) Once restarted, check if it has worked by going to a blocked site such as [https://discord.com/app] If not, contact my discord (mentioned in title).

#### Remember: GoGuardian active = icon glowing blue.
