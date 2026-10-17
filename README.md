<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>[BOT NAME] | Terms of Service &amp; Privacy Policy</title>
<style>
  :root {
    --bg: #f6f7fb; --card: #ffffff; --text: #1f2430; --muted: #5b6475;
    --accent: #5865f2; --border: #e2e5ee; --ph-bg: #fff3c4; --ph-text: #6b5300;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #14161c; --card: #1c1f27; --text: #e6e8ee; --muted: #a0a8b8;
      --accent: #8c96ff; --border: #2a2e39; --ph-bg: #4a3d0a; --ph-text: #ffe28a;
    }
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; scroll-padding-top: 72px; }
  body {
    margin: 0; background: var(--bg); color: var(--text);
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif; line-height: 1.65;
  }
  header {
    position: sticky; top: 0; z-index: 10; background: var(--card);
    border-bottom: 1px solid var(--border); padding: 14px 20px;
    display: flex; gap: 20px; align-items: center; flex-wrap: wrap;
  }
  header .brand { font-weight: 700; margin-right: auto; }
  header a { color: var(--muted); text-decoration: none; font-weight: 600; }
  header a:hover { color: var(--accent); }
  main { max-width: 820px; margin: 0 auto; padding: 32px 20px 64px; }
  section.doc {
    background: var(--card); border: 1px solid var(--border); border-radius: 12px;
    padding: 28px 32px; margin-bottom: 32px;
  }
  h1 { margin-top: 0; font-size: 1.9rem; }
  h2 { font-size: 1.15rem; margin-top: 1.8em; }
  .meta { color: var(--muted); font-size: 0.95rem; }
  ul { padding-left: 1.3em; }
  li { margin: 0.35em 0; }
  a { color: var(--accent); }
  .ph { background: var(--ph-bg); color: var(--ph-text); padding: 0 4px; border-radius: 4px; font-weight: 600; }
  footer { text-align: center; color: var(--muted); font-size: 0.9rem; padding-bottom: 32px; }
  @media (max-width: 600px) { section.doc { padding: 20px; } }
</style>
</head>
<body>

<header>
  <span class="brand"><span class="ph">[BOT NAME]</span></span>
  <a href="#terms">Terms of Service</a>
  <a href="#privacy">Privacy Policy</a>
  <a href="https://discord.com" target="_blank" rel="noopener">Discord</a>
</header>

<main>

<!-- ============================ TERMS OF SERVICE ============================ -->
<section class="doc" id="terms">
  <h1>Terms of Service</h1>
  <p class="meta">Effective Date: October 17, 2026</p>

  <h2>1. Acceptance of Terms</h2>
  <p>By inviting, accessing, or using <span class="ph">[BOT NAME]</span> (“the Service”) in any Discord server, or by opening a ticket through it, you agree to be bound by these Terms of Service. Server owners and administrators who add the Service to a server accept these terms on behalf of that server. If you do not agree with any part of these terms, you must not use or interact with the Service.</p>

  <h2>2. Compliance with Discord</h2>
  <p>You must comply at all times with the <a href="https://discord.com/terms" target="_blank" rel="noopener">Discord Terms of Service</a>, the <a href="https://discord.com/guidelines" target="_blank" rel="noopener">Discord Community Guidelines</a>, and the Discord Developer Policy, including Discord’s minimum age requirement. Any attempt to use the Service to break Discord’s platform rules is strictly prohibited.</p>

  <h2>3. What the Service Does</h2>
  <p>The Service is a support ticket system for Discord servers. It provides:</p>
  <ul>
    <li><strong>Ticket Panel:</strong> an embed with a button for each support category. Pressing a button opens a private ticket channel, placed in a Discord category that matches the option chosen.</li>
    <li><strong>Ticket Dashboard:</strong> a configuration embed for server owners and administrators, used to set the ticket staff roles, the assistance role, the review category and review channel, the close log channel, the default auto-close time, and the panel’s appearance and categories.</li>
    <li><strong>Staff commands:</strong> <code>/closerequest</code> (asks the opener to confirm closing, with an automatic close after a set number of hours), <code>/close</code>, <code>/claim</code> and <code>/unclaim</code> (a staff member takes ownership of a ticket and other staff can no longer send messages in it), <code>/assistance</code> (pings the configured assistance role), and <code>/review</code>.</li>
    <li><strong>Review system:</strong> <code>/review</code> moves a ticket to a private review category, posts a log embed in the review channel, and opens a discussion thread or forum post where staff are pinged and asked to discuss the matter and reach a joint decision.</li>
    <li><strong>Logging:</strong> when a ticket is closed, a log entry is posted in the configured close log channel.</li>
  </ul>

  <h2>4. Acceptable Use &amp; Conduct</h2>
  <p>When interacting with the Service, you agree that you will not:</p>
  <ul>
    <li>Attempt to exploit, reverse engineer, decompile, or bypass the Service’s permission checks and command limitations.</li>
    <li>Spam buttons or commands, flood the bot or Discord’s API, or attempt denial-of-service attacks against the Service or its hosting.</li>
    <li>Open tickets to harass, spam, or mislead staff, or submit false or abusive reports.</li>
    <li>Use the Service to transmit harmful software, evade bans or disciplinary action, or share other people’s private information without permission.</li>
    <li>Misuse staff features, for example claiming tickets to obstruct users, or using review to target a person unfairly.</li>
    <li>Attempt to access tickets, settings, or logs you have not been given access to.</li>
  </ul>

  <h2>5. Server Owner &amp; Staff Responsibilities</h2>
  <p>Server owners and administrators are responsible for how the Service is configured in their server. In particular:</p>
  <ul>
    <li>You decide which roles count as ticket staff and who may use the dashboard. The dashboard can be posted as a message in a channel; <strong>anyone who can see that channel can use and edit it</strong>, so post it only in a channel limited to people you trust.</li>
    <li>You are responsible for keeping the review category and log channels private and for setting their permissions correctly.</li>
    <li>Staff must treat the contents of tickets as confidential and use them only to provide support and run moderation.</li>
    <li>Server operators are responsible for complying with the laws and Discord policies that apply to their community.</li>
  </ul>

  <h2>6. Tickets, Closing &amp; Review</h2>
  <ul>
    <li>Ticket channels are visible to the person who opened them, the configured ticket staff roles, the bot, and anyone in the server with permissions that override channel settings, such as administrators.</li>
    <li>When a ticket is closed, its channel is permanently deleted. The Service does not create or keep transcripts of ticket conversations.</li>
    <li>A close request closes the ticket automatically if it is not answered within the stated number of hours.</li>
    <li>When a ticket is sent to review, it moves to the review category and takes on that category’s permissions, so the ticket opener may lose access to it. A description of the issue is posted for staff to discuss.</li>
    <li>Close logs and review logs are posted as messages in your server’s channels. Who can see them and how long they stay there is controlled by the server, not by the Service.</li>
  </ul>

  <h2>7. Administration &amp; Moderation Authority</h2>
  <p>The Service’s operator and the management of a server using it reserve the right to restrict, suspend, or end any user’s access to the Service’s features, or to remove the Service from a server, at any time, with or without notice, for conduct that breaks these terms or a server’s rules.</p>

  <h2>8. Disclaimer of Warranties</h2>
  <p>The Service is provided on an “AS IS” and “AS AVAILABLE” basis, without warranties of any kind, express or implied. We do not guarantee that the Service will always be uninterrupted, timely, secure, or free from bugs, or that it will be unaffected by outages of Discord or of the hosting it runs on. Ticket records and settings may be lost in the event of a technical failure.</p>

  <h2>9. Limitation of Liability</h2>
  <p>To the maximum extent permitted by applicable law, the developers and operators of the Service are not liable for any indirect, incidental, or consequential damages resulting from your use of, or inability to use, the Service, including lost tickets, missed support requests, or decisions made by staff using the Service.</p>

  <h2>10. Modifications to Terms</h2>
  <p>We may modify these Terms of Service at any time. Changes take effect when they are posted on this page. Continued use of the Service after any change means you accept the updated terms.</p>

  <h2>11. Contact &amp; Inquiries</h2>
  <p>If you have questions about these terms, please contact us through the support server or the bot owner: <span class="ph">[SUPPORT SERVER INVITE LINK]</span> or <span class="ph">[OWNER DISCORD USERNAME]</span>.</p>
</section>

<!-- ============================ PRIVACY POLICY ============================ -->
<section class="doc" id="privacy">
  <h1>Privacy Policy</h1>
  <p class="meta">Effective Date: October 17, 2026</p>

  <h2>1. Overview</h2>
  <p>This Privacy Policy explains what information <span class="ph">[BOT NAME]</span> (“we”, “us”, or “the Service”) collects, how it is used, and how it is protected when you interact with the bot in Discord. We follow the Discord Developer Policy and collect only what is needed to run a ticket system.</p>

  <h2>2. Information We Collect</h2>
  <p>The Service stores the following operational data:</p>
  <ul>
    <li><strong>Server settings:</strong> your server’s ID; the IDs of the ticket staff roles, assistance role, review category, review channel, and close log channel; the default auto-close time; and the panel’s text, colour, image link, and category options.</li>
    <li><strong>Open ticket records:</strong> the ticket channel’s ID and your server’s ID, the Discord User ID of the person who opened it, the category chosen, the time it was opened, the ID of the staff member who claimed it, any pending close request (reason, time, and the staff member’s ID), and any review request and its description.</li>
    <li><strong>Message references:</strong> the IDs of the posted panel and dashboard messages, so they can be updated.</li>
  </ul>

  <h2>3. Information Processed Automatically</h2>
  <ul>
    <li>When you press a button or run a command, the Service receives that interaction from Discord, including your User ID and roles, in order to check permissions and carry out the action.</li>
    <li>The Service does not read, store, or log the content of messages sent in tickets or elsewhere, and it does not keep transcripts.</li>
    <li>When a ticket is closed or sent to review, the Service posts a log entry in your server containing the opener’s and staff member’s Discord IDs, the reason given, the category, and the time. These entries are stored by Discord in your server, not in our database.</li>
    <li>Staff usernames may appear in a ticket’s channel name when a ticket is claimed.</li>
  </ul>

  <h2>4. How We Use Your Information</h2>
  <ul>
    <li>To open, manage, claim, review, and close support tickets.</li>
    <li>To check who is allowed to use staff commands and the dashboard.</li>
    <li>To send logs to the channels your server has chosen, and to restore close-request timers after the bot restarts.</li>
  </ul>
  <p>We do not sell, rent, or trade your data. No message content or user activity is used to train machine learning or artificial intelligence models.</p>

  <h2>5. Data Security &amp; Storage</h2>
  <p>The Service’s data is kept in a file on the server infrastructure that hosts the bot. Access is limited to the bot’s operator. The bot runs on third-party hosting, and while we take reasonable steps to protect it, no system can be guaranteed completely secure.</p>

  <h2>6. Data Retention</h2>
  <ul>
    <li><strong>Open ticket records:</strong> deleted as soon as the ticket is closed or its channel is deleted.</li>
    <li><strong>Server settings:</strong> kept for as long as the Service is in use in your server, and removed on request.</li>
    <li><strong>Logs posted in Discord:</strong> remain in the server’s channels until the server deletes them.</li>
  </ul>

  <h2>7. Your Rights &amp; Data Deletion</h2>
  <p>You may ask to see, correct, or permanently delete any information the Service holds about you or your server. To make a request, contact us using the details below. Verified requests are carried out within 30 days.</p>

  <h2>8. Contact Us</h2>
  <p>For questions about this policy or your data, contact us through the support server or the bot owner: <span class="ph">[SUPPORT SERVER INVITE LINK]</span> or <span class="ph">[OWNER DISCORD USERNAME]</span>.</p>
</section>

</main>

<footer>© 2026 <span class="ph">[BOT NAME]</span>. Not affiliated with or endorsed by Discord Inc.</footer>

</body>
</html>
