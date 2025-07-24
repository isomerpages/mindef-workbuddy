---
title: DOs and DON'Ts of Using Postman for SMS Communications
permalink: /general-faqs/postman-faqs/dos-and-don-ts-of-using-postman-for-sms-communications/
variant: tiptap
description: ""
third_nav_title: Postman FAQs
---
<h2>This page is for testing purposes only.</h2>
<h1><strong>DOs and DON'Ts of Using Postman for SMS Communications</strong></h1>
<h3><strong>Message Types and Requirements</strong></h3>
<h4>Q1: Can I use my own SMS aggregators to send SMS messages to citizens and mixed groups?</h4>
<p>All one-way SMS communications to citizens or mixed groups must be sent
using Postman V2 by Open Government Products (OGP). Agencies are not allowed
to engage external SMS aggregators.</p>
<h4>Q2: What types of messages can I send?</h4>
<p>You should only send essential/critical SMS messages to citizens or mixed
groups. The sending of non-critical or generic messages<sup>3</sup> to citizens
or mixed groups using the "gov.sg" sender ID is not allowed. Refer to the
table below for examples of non-critical and critical messages. More details
can be found in SD Directive 03-2022 - Management of MINDEF/SAF’s Direct
Channels of Communication.</p>
<p>Aside from the critical messages listed, you may also send SMS messages
to citizens and mixed groups containing pre-event related details (e.g.,
RSVP confirmations, digital Admin Instructions).</p>
<p><strong><u>Examples of non-critical and critical messages</u></strong>
</p>
<table style="minWidth: 50px">
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr>
<th rowspan="1" colspan="1">
<p>Non-Critical</p>
</th>
<th rowspan="1" colspan="1">
<p>Critical</p>
</th>
</tr>
<tr>
<td rowspan="1" colspan="1">
<ul data-tight="true" class="tight">
<li>
<p>General feedback or post-event polls or surveys<sup>4</sup>
</p>
</li>
<li>
<p>Holiday greetings</p>
</li>
<li>
<p>Promotions (e.g. promotions of courses, promotions of new app features)</p>
</li>
<li>
<p>Messages of appreciation</p>
</li>
<li>
<p>Requests for donation</p>
</li>
</ul>
</td>
<td rowspan="1" colspan="1">
<ul data-tight="true" class="tight">
<li>
<p>One-Time Password (OTP)</p>
</li>
<li>
<p>Appointment bookings or reminders</p>
</li>
<li>
<p>Updates on transactions with MINDEF/SAF (e.g. applications on OneNS)</p>
</li>
<li>
<p>Follow-up on requests</p>
</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p><sup>3 </sup><em>“Generic messages” are messages with no call-to-action or are not related to the citizen’s transactions with MINDEF/SAF.</em>
</p>
<p><sup>4 </sup><em>Polls or surveys commissioned at the national or organisation level in support of strategic defence objectives (e.g. defence opinion polls, policy research) may be assessed for deviation.</em>
</p>
<h4>Q3: Does prior notification to the target recipient to expect an SMS message change the nature of the message from 'non-critical' to 'critical'?</h4>
<p>No.</p>
<h4>Q4: Can I send an SMS and get their response via SMS?</h4>
<p>No.</p>
<p></p>
<h3><strong>Use of Links</strong></h3>
<h4>Q5: Can I send links in the SMS?</h4>
<p>By default, you should not send links in SMSes. However, there are exceptions
where non-login links may be sent (see Q7). Some scenarios include:</p>
<p>a. The link was requested by the customer, who is expecting the link from
MINDEF/SAF; <strong>OR</strong>
</p>
<p>b. The customer is less digitally-savvy and found it difficult to locate
the webpage despite personalised instructions.</p>
<h4>Q6: What are the requirements if a link is approved to be used in the SMS?</h4>
<p>If approved, the link must meet these requirements:</p>
<p>a. The link must use a GoGovSG URL shortener (<a href="https://go.gov.sg/" rel="noopener noreferrer nofollow" target="_blank">https://go.gov.sg/</a>). This is because only
public officers with a gov.sg email domain can generate GoGovSG links,
ensuring that the public can trust that the links are official and not
from scammers.</p>
<p>b. Agencies must use a GoGovSG URL shortener to shorten links, subdomains
and subdirectories where possible. This reduces the total character count
of the message and the corresponding SMS cost.</p>
<h4>Q7: Can I send non-login links in an SMS?</h4>
<p>There are exceptions allowing non-login links to be sent in an SMS message.
The SMS must be a solicited message and part of MINDEF/SAF’s day-to-day
operations:</p>
<p>a. Where there is an established relationship between MINDEF/SAF and Members
of Public (MOP)</p>
<p>b. Where the MOP is expecting to receive the link (e.g., links that are
sent in response to a MOP’s action)</p>
<h3><strong>Length and Format</strong></h3>
<h4>Q8: What is the maximum number of characters and segments permissible for each SMS?</h4>
<p>Postman allows a maximum of 1000 characters for the message body, excluding
the header (agency's name) and footer. However, users are strongly encouraged
to limit their message body to 320 characters (excluding the header and
footer) and keep messages under 7 segments to ensure reliable and timely
message delivery.</p>
<h4>Q9: What will happen if my SMS message contains unsupported characters?</h4>
<p>On the Admin Portal: Campaign templates that contain unsupported characters
cannot be created on the Postman admin portal. This blocking has been implemented
since June 2024.</p>
<p>On the API layer: Message content containing unsupported characters will
be blocked from sending. Postman Team will implement blocking on the Postman
production environment from 5 May 2025.</p>
<h4>Q10: How do I count total characters, number of segments and identify unsupported characters?</h4>
<p>Visit <a href="https://message-segment-calculator.postman.gov.sg" rel="noopener noreferrer nofollow" target="_blank">https://message-segment-calculator.postman.gov.sg</a> to
use the Postman Message Segment Calculator tool to count your total characters,
number of segments and identify any unsupported characters.</p>
<h4>Q11: Can I paste message content into Postman from another editor/MS Word/Outlook etc?</h4>
<p>A: It is recommended that you do not paste message content into Postman
from another editor/MS Word/Outlook etc. as this may convert characters
into unsupported (non-GSM-7) characters. Please type the message content
directly into Postman.</p>
<p></p>