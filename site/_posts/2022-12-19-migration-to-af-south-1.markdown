---
layout: post
title:  "Migration to af-south-1"
date:   2022-12-19 16:09:05 +0000
categories: news
---
As of today, mastodon.africa operates entirely within the borders of South Africa - via the AWS Cape Town (<code>af-south-1</code>) region.

When the instance was initially launched, it was provisioned on a Hetzner server (in Germany) to get up and running quickly. The intention was to eventually transfer it into South African hosting, which has now been accomplished:

<ul>
<li>The primary EC2 server now runs out of <code>af-south-1</code></li>
<li>Media is saved directly to an S3 bucket domiciled in <code>af-south-1</code></li>
<li>AWS CloudFlare provides a CDN distribution for better performance</li>
<li>AWS Route53 provides DNS hosting for the mastodon.africa domain</li>
<li>The internal PostgreSQL database is backed up daily to a secure S3 bucket</li>
</ul>

On the technical side, most of the work has been completed. All that remains:

<ul>
<li>Upgrading the instance to the latest version of Mastodon</li>
<li>Publishing the mission, vision, code of conduct and Terms pages</li>
<li>Opening up registration to the wider public</li>
</ul>

Applications for new accounts are already open, though - if you're interested in signing up, you can do so at <a href="https://mastodon.africa/">https://mastodon.africa/</a>.

