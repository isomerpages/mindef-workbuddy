---
title: Vendor Access to Postman SMS System
permalink: /vendor-access-to-postman-sms-system/
variant: tiptap
description: ""
third_nav_title: Postman FAQs
---
<h2>This page is for testing purposes only.</h2>
<h1><strong>Vendor Access to Postman SMS System</strong></h1>
<h4>Q1: Are vendors allowed to be Campaign Creators?</h4>
<p>Vendors are not allowed to be Campaign Creators; they can only be assigned
as Campaign Collaborators (members). Please refer to MDDI’s policy and
clause stated in the AUP on FormSG.</p>
<table style="minWidth: 50px">
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr>
<th rowspan="1" colspan="1">
<p>MDDI's Policy</p>
</th>
<th rowspan="1" colspan="1">
<p>FormSG</p>
</th>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Who can I add as a campaign creator?</strong>
</p>
<p>You will only be able to add officers from your own agency as campaign
creators. This is defined as officers who have the same email domain as
you.</p>
<p></p>
<p>Vendors <strong>will not</strong> be allowed to have campaign creator access,
as they are not allowed to create campaigns on behalf of agencies. They
can be added to existing campaigns, under campaign settings. Please refer
to <a href="https://postman-v2.guides.gov.sg/postman-v2-admin-portal-for-api-users-mop/campaign-settings#settings-members" rel="noopener" target="_blank"><u>this page</u></a> for
more information.</p>
<p></p>
</td>
<td rowspan="1" colspan="1">
<p>I am aware of and agree to comply with MDDI's policy regarding vendor
access, which stipulates that vendors can only be assigned the Campaign
Collaborator role for sending messages, the Campaign Creator role is exclusively
for MINDEF/SAF Employees, and Campaign Creators are solely responsible
for managing and overseeing Campaign Collaborators.</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><em><a href="https://docs.developer.tech.gov.sg/docs/postman-sgdp-guide/campaign-create-access" rel="noopener nofollow" target="_blank">Postman SGDP Guide</a></em>
</p>
</td>
<td rowspan="1" colspan="1">
<p></p>
</td>
</tr>
</tbody>
</table>
<h4>Q2: How do vendors access and use Postman V2 for sending SMS messages?</h4>
<p>Postman does not grant vendors access to the portal. This means vendors
with non-whitelisted email domains cannot log into Postman V2. Agency officers
should log into Postman V2, create the campaign, craft the message, whitelist
the vendor’s domain, generate the API keys and pass the API keys to the
vendors for the necessary integration.</p>
<h4>Q3: How do I whitelist the vendor’s domain<sup>#</sup>?</h4>
<p>Agency PIC (Person-in-Charge) - SDD must <u>submit a request</u> for the
Postman team to whitelist the vendor's domain. This will allow vendors
to log into Postman V2 and view campaigns that they have been added to
by the agency admins. Vendors will then be able to log in and send messages,
but not create campaigns (i.e., member access).</p>
<p><sup>#</sup><em>The vendor's domain refers to their email domain (the part of their email address that comes after the @ symbol). For example, if a vendor's email address is john@vendorcompany.com, then "vendorcompany.com" is their domain that needs to be whitelisted. This whitelisting allows anyone with an email address from that vendor's domain to access the specified campaigns in Postman.</em>
</p>
<p></p>
<p></p>