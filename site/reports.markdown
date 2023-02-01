---
layout: page
title: Monthly Operating Reports
permalink: /reports/
---

<p>This page will be updated monthly to recap key events of the month, and the hosting costs incurred to keep Mastodon.Africa running.</p>

<h1>February 2023</h1>

<p>Having completed a full calendar month of service hosting, I'm pretty comfortable with the setup - the instance has been stable and responsive, and the costs are within expectations. No major goals this month, other than some optimization on storage utilization.</p>

<ul>
  <li>1 Feb: Added the provisional January 2023 report</li>
  <li>1 Feb: Updated server retention policy: Media will cache for 14 days, content for 21 days</li>
</ul>

<h1>January 2023</h1>

<p>The main goal for this month was to get Mastodon.Africa listed and visible as a destination for African users, and complete a full month on the current AWS hosting stack (to ensure it's properly resourced, and to get a sense of how many users can be supported on the current setup.</p>

<ul>
  <li>2 Jan: Updated the December 2022 Hosting Costs with the final figures</li>
  <li>3 Jan: Submitted the server to joinmastodon.org for listing (as of 2 Feb 2023, it's not listed)</li>
  <li>29 Jan: Listed mastodon.africa on <a href="https://fedi.garden/mastodon-africa/" target="_blank">fedi.garden</a></li>
</ul>

<h3>Instance Statistics</h3>

<p>As of 1 Feb 2023:</p>

<ul>
  <li>No user reports</li>
  <li>No service downtime</li>
  <li>20 active users</li>
  <li>2.73gb in database utilization</li>
  <li>383.4gb (1,235,860 items) in media storage utilization</li>
</ul>

<h3>Hosting Costs</h3>

<p>Utilization from 1 January 2023 to 31 January 2023, last updated 1 February 2023:</p>

<ul>
  <li>t3.medium instance (EC2): $40.27</li>
  <li>Media and backup storage (S3): $12.27</li>
  <li>DNS Hosting (Route53): $0.73</li>
  <li>Data Transfer: $0.06</li>
  <li>Tax: $8.00</li>
  <li><strong>Total (Jan 2023): $61.33</strong></li>
  <li><strong>Total (USDZAR 17.4081): R1,067.64</strong></li>
</ul>

<p><strong>NB:</strong> The ZAR figure is provisional, until AWS actually sends the invoice</p>

<h1>December 2022</h1>

<p>Main project this month was to finalize the service setup: Get everything migrated to South Africa, set up the terms/conduct rules, and prepare to open the doors "properly"</p>

<ul>
<li>16 Dec: Started registration for a dedicated AWS account under Protocol </li>
<li>19 Dec: AWS account registered and af-south-1 region activated</li>
<li>19 Dec: Instance and data migration to af-south-1 completed</li>
<li>19 Dec: about.mastodon.africa created, Vision and Mission populated, first draft of Code of Conduct</li>
<li>19 Dec: AWS CloudFront CDN enabled and configured</li>
<li>22 Dec: Code of Conduct, Terms and Conditions finalized</li>
<li>22 Dec: Instance registration opened - accounts can now be created without prior approval</li>
</ul>

<h3>Hosting Costs</h3>

<p>Utilization from 19 December to 31 December 2023, last updated 2 January 2023:</p>

<ul>
  <li>t3.medium instance (EC2): $16.50</li>
  <li>Media and backup storage (S3): $4.20</li>
  <li>DNS Hosting (Route53): $0.59</li>
  <li>Tax: $3.19</li>
  <li><strong>Total (Dec 2022): $24.48</strong></li>
</ul>

<hr>

<h1>November 2022</h1>

Given the events at Twitter during the week, the case for a reliable South African-based Mastodon server basically made itself. I got an initial setup going at Hetzner EU first, under an existing hosting agreement to get up and running quickly. The plan was to eventually migrate everything to AWS Cape Town (af-south-1) and operate the service under a Pty (Ltd).

<ul>
  <li>7 Nov: mastodon.africa domain name registered</li>
  <li>7 Nov: Hosting procured at Hetzner EU, with a CPX31 VM in Germany</li>
  <li>7 Nov: Initial instance deployed at v3.5.3</li>
</ul>

<h3>Hosting Costs</h3>

<p>No hosting costs reported for November 2022, since the instance was running on existing hosting under another account.</p>

<hr>

<small>Last Updated: 22 December 2022</small>
