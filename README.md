# My Website
The following code is the source code for my website, zgriffin.com

The purpose of this site is to redirect you, the user, to my main LinkedIn profile. I keep my LinkedIn up-to-date so that it acts as an more interactive version of a resume. The redirection is purposely slow, to allow the user time to understand where they are being redirected to, and not blindly take them to a different page.

Because I run this through CloudFlare, you will notice some lines between <sse> comments. These are for use with the CloudFlare bot protection mechanism and prevent known crawlers and bots from constantly forcing redirects. CloudFlare simply skips over lines between these comments when a bot user is suspected.

There are also directories that redirect to my other applications that are not hosted in cloudflare. You will see that they redirect immediatley but still present a loading animation. This is to act as a backup in the event the redirection fails.
