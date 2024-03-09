# Phishing-Analysis-Lab

## Objective

The Phishing Analysis Lab project aimed to establish a controlled environment for simulating and analyzing phishing emails. The primary focus was to investigate a phishing email and attachment to collect useful artifacts.

### Skills Learned

- Identifying phishing emails, discerning fraudulent websites, and recognizing social engineering tactics.
- Scrutinizing email headers, inspecting URL structures, and detect malicious attachments or links.

### Tools Used

- Text Editor(Sublime Text).
- Mozilla Thunderbird.
- URL2PNG.
- WHOis.

## Steps 1
<img width="858" alt="Screenshot 2024-03-09 at 11 18 49" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/b637e2f6-0ceb-4637-b52f-d535dc75a215">
*Ref 1: Finding the primary recipient of this email*
By opening the email attachment in Sublime Text, one can employ the shortcut key (CTRL+F) to locate the recipient's email address which is kinnar1975@yahoo.co.uk.

## Steps 2
<img width="915" alt="Screenshot 2024-03-09 at 11 30 41" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/048f4549-c862-4813-b290-31bda2014f79">
*Ref 2: Identifying the subject of this email*
By using same process as before, one can utilize one can employ the shortcut key (CTRL+F) to locate the subject of this email which is, Undeliverable: Website contact form submission.

## Steps 3
<img width="819" alt="Screenshot 2024-03-09 at 11 53 13" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/a6044e98-eff5-4e32-8ad8-b906dac9884f">
*Ref 3: Finding the date and time the email was sent*
Within Sublime Text, we will search for the "Date" field, as illustrated.

## Steps 4
<img width="1263" alt="Screenshot 2024-03-09 at 12 24 52" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/ef47ac12-903d-4a88-8817-aa58e2f1cfbb">
*Ref 4: Finding the Originating IP*
To locate the IP Address, we conducted a search for "IP" within Sublime Text. Upon thorough examination, we identified the desired IP Address as 103.9.171.10.

## Steps 5
<img width="858" alt="Screenshot 2024-03-09 at 12 32 58" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/0d3df43f-a682-4112-80d2-929d389d29fb">
*Ref 5: Performing a reverse DNS on the IP address to find the resolved host*
To conduct a WHOIS lookup for obtaining the hostname, we searched for the sender's IP address, 103.9.171.10, on https://whois.domaintools.com. This yielded the hostname, as depicted in the reference.

## Steps 6
<img width="1298" alt="Screenshot 2024-03-09 at 14 52 20" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/939209d0-89db-4df7-bb5e-c3ff866730c1">
*Ref 6: Finding the name of the attached file*
When examining the Thunderbird client, the attachment name is visible at the bottom of the interface.

## Steps 7
<img width="839" alt="Screenshot 2024-03-09 at 14 57 56" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/abadd8cb-5ee9-438b-bcd7-5df33a4ec62e">
*Ref 7: URL found in attachment*
The attachment's URL can be located in Sublime Text by conducting a search for "http".

## Steps 8
<img width="1388" alt="Screenshot 2024-03-09 at 15 02 59" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/7034f8ec-fbfd-4ca0-bba1-be17a36af34e">
*Ref 8: Identifying the kind of service this webpage hosted on*
The solution to this question can be discovered by examining the URL artifact associated with this email.

## Steps 9
<img width="1217" alt="Screenshot 2024-03-09 at 15 18 00" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/e9f2f777-b8ac-4fbe-993d-47eb0c6a8d04">
*Ref 9: Identifying the the heading text on this page using URL2PNG*
URL2PNG is a tool for visualizing URLs, allowing you to preview website snapshots without actually visiting them. To address this question, you'll need to copy the provided URL and paste it into https://www.url2png.com/.


##PHISHING ANALYSIS 2

The second phishing analysis is to put skils to the test by triaging and collecting information about a recent phishing campaign.
<img width="423" alt="Screenshot 2024-03-09 at 21 38 31" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/211c9942-7609-4789-b098-5b89dc9ca60a">

Analysis Tools
- Text Editor(Sublime Text)
- Mozilla Thunderbird
- CyberChef

## Steps 1
<img width="1312" alt="Screenshot 2024-03-09 at 21 54 22" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/1c9c3fd2-c698-408d-a8e7-b8b790585c10">
*Ref 1: Finding the sending email address*
Upon opening the email in Sublime Text and utilizing the keys (CTRL+F) and search "from", we can find the senders email.

## Steps 2
<img width="1316" alt="Screenshot 2024-03-09 at 22 00 51" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/da0418ee-5c18-4e7f-9cac-fb4f5da745ad">
*Ref 2: Finding the receivers email address*
The receivers email is located under the senders email as marked in the attached.

## Steps 3
<img width="1328" alt="Screenshot 2024-03-09 at 22 04 31" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/b5a48c50-c219-4cee-b7f2-9776c695ae99">
*Ref 3: Finding the subject of the email*
The email's subject can be found by entering "subject" into the search box.

## Steps 4
<img width="1286" alt="Screenshot 2024-03-09 at 22 10 09" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/2c7d5252-c256-4d47-8f9b-ddfcb4bb1c9b">
*Ref 4: Identifying the company the attacker trying to imitate*
From the "from" address, it's evident that the attacker is imitating Amazon.

## Steps 5
<img width="1318" alt="Screenshot 2024-03-09 at 22 26 02" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/a303ad9d-7c40-4491-89aa-7c4854a29a16">
*Ref 5: Finding the date the email was sent*
Once more, we utilize Sublime Text to search for "date" to ascertain when the email was sent.

## Steps 6
<img width="1432" alt="Screenshot 2024-03-09 at 23 27 39" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/17ad0238-f3f5-4f2e-8c5f-dba0f247b31d">
*Ref 6: Finding the URL of the main call-to-action button*
To extract the malicious URL embedded within the phishing email, right-click the hyperlink and choose “Copy Link Location” with caution. Be aware that this approach carries the risk of inadvertently activating the malicious link. As a safer alternative, consider employing a text editor.

## Steps 7
<img width="1203" alt="Screenshot 2024-03-09 at 23 33 58" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/3a1915fc-c5e7-4d28-970d-a4ffcbad8b75">
*Ref 7: The first sentence (heading) displayed on the site using URL using URL2PNG*
Upon entering the URL into https://www.url2png.com/, it was discovered that the page failed to load.

## Steps 8
<img width="958" alt="Screenshot 2024-03-09 at 23 42 45" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/1223246b-a263-4ad3-a00e-c92dad21d9ad">
*Ref 8: Finding the main body content in text editor, to find encoding scheme is used*
By searching "Encoded" in Sublime Text, we find that the encoded scheme used is Base64.

## Steps 9
<img width="1440" alt="Screenshot 2024-03-09 at 23 54 57" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/2b9138b7-4182-46d0-85fc-76fce4b71600">
*Ref 9: URL used to retrieve the company’s logo in the email*
By transferring the base64 content into CyberChef and conducting a search for "http," we can uncover the URL that was used to download the company's logo.

## Steps 10
<img width="1440" alt="Screenshot 2024-03-10 at 00 12 28" src="https://github.com/AlCybx/Phishing-Analysis-Lab/assets/161755166/3ae265e3-695f-4e42-a6ab-80c2fbf2d713">
*Ref 10: For some unknown reason one of the URLs contains a Facebook profile URL. What is the username (not necessarily the display name) of this account, based on the URL*
For this query, we'll look for the "facebook" field within the Output section on CyberChef.


