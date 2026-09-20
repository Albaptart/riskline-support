[index.html](https://github.com/user-attachments/files/32433568/index.html)
Support and privacy policy pages for the Riskline iOS app.<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Riskline — Support</title>
<style>
  :root { color-scheme: dark; }
  body {
    margin: 0 auto; padding: 2rem 1.25rem 5rem; max-width: 46rem;
    background: #0d1117; color: #d8dee9;
    font: 16px/1.65 -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }
  h1 { font-size: 2.1rem; margin-bottom: .2rem; color: #fff; }
  .tag { color: #ffb454; margin-top: 0; font-size: 1rem; }
  h2 { font-size: 1.15rem; margin-top: 2.25rem; color: #ffb454; }
  a { color: #58a6ff; }
  .card {
    background: #161b22; border: 1px solid #30363d; border-radius: 10px;[Uploading privacy.html…]()

    padding: 1rem 1.25rem; margin: 1.25rem 0;
  }
  dt { font-weight: 600; color: #fff; margin-top: 1.1rem; }
  dd { margin: .35rem 0 0; }
  footer { margin-top: 3.5rem; padding-top: 1.25rem; border-top: 1px solid #30363d; color: #7d8590; font-size: .88rem; }
</style>
</head>
<body>

<h1>Riskline</h1>
<p class="tag">Support &amp; contact</p>

<div class="card">
  <strong>Need help?</strong> Email
  <a href="mailto:risklinedev@gmail.com">risklinedev@gmail.com</a>.
  We usually reply within two or three days. Including your device model and iOS version
  makes it much faster to sort out.
</div>

<h2>Frequently asked</h2>

<dl>
  <dt>I lost my career progress.</dt>
  <dd>Riskline saves locally on your device and keeps a backup copy, which it restores
  automatically at launch if the main save is missing. There is no cloud save, so
  deleting the app or resetting the device removes your progress permanently and we
  cannot recover it. If progress disappeared without you deleting anything, email us with
  your device model and roughly when it happened.</dd>

  <dt>An ad did not play, or I did not get my reward.</dt>
  <dd>Rewarded ads need a working internet connection, and there is not always one
  available to show. The game is designed so that a failed ad never costs you anything —
  if the reward did not arrive after watching a full video, email us and describe which
  bonus it was.</dd>

  <dt>Can I play without ads?</dt>
  <dd>Yes. Every ad in Riskline is optional and started by you in exchange for a bonus.
  Nothing in the game is locked behind watching one.</dd>

  <dt>How do I change my tracking or advertising choice?</dt>
  <dd>Go to <em>Settings → Privacy &amp; Security → Tracking</em> on your iPhone to allow or
  refuse tracking for Riskline. In the EEA, UK and Switzerland a Google consent form also
  appears on first launch. Refusing either simply means you see non-personalised ads.</dd>

  <dt>The game does not fit my screen, or the sound keeps playing.</dt>
  <dd>Force-quit the app and reopen it. If it persists, email us with your device model —
  these reports genuinely help.</dd>
</dl>

<h2>Privacy</h2>
<p>Riskline has no accounts and no servers. See the
<a href="privacy.html">Privacy Policy</a> for exactly what the advertising SDK collects and
how to control it.</p>

<footer>
  Riskline — William Pitot · <a href="privacy.html">Privacy Policy</a>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Riskline — Privacy Policy</title>
<style>
  :root { color-scheme: dark; }
  body {
    margin: 0 auto; padding: 2rem 1.25rem 5rem; max-width: 46rem;
    background: #0d1117; color: #d8dee9;
    font: 16px/1.65 -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }
  h1 { font-size: 1.9rem; margin-bottom: .25rem; color: #fff; }
  h2 { font-size: 1.15rem; margin-top: 2.25rem; color: #ffb454; }
  .updated { color: #7d8590; font-size: .9rem; margin-top: 0; }
  a { color: #58a6ff; }
  table { border-collapse: collapse; width: 100%; margin: 1rem 0; font-size: .93rem; }
  th, td { border: 1px solid #30363d; padding: .55rem .7rem; text-align: left; vertical-align: top; }
  th { background: #161b22; color: #fff; }
  code { background: #161b22; padding: .1rem .35rem; border-radius: 3px; font-size: .88em; }
  footer { margin-top: 3.5rem; padding-top: 1.25rem; border-top: 1px solid #30363d; color: #7d8590; font-size: .88rem; }
</style>
</head>
<body>

<h1>Privacy Policy</h1>
<p class="updated">Riskline — last updated 20 September 2026</p>

<p>Riskline is a single-player game published by William Pitot. This policy explains
what data the app handles, what leaves your device, and how to control it.</p>

<h2>The short version</h2>
<p>Riskline has no accounts, no logins and no servers of its own. The game itself runs
entirely offline on your device. The only data that ever leaves your phone is what the
Google AdMob advertising SDK sends when it loads an ad.</p>

<h2>Data stored on your device</h2>
<p>Your career progress — money, fleet, upgrades, streaks, statistics — is saved locally
on your device and is also mirrored into iOS <code>UserDefaults</code> as a backup, so that
progress survives if iOS clears the app's web storage. This data is never transmitted to us
or to anyone else. Deleting the app deletes it permanently; there is no cloud copy and no
way for us to restore it.</p>

<h2>Data collected by advertising</h2>
<p>Riskline shows optional rewarded video ads through <strong>Google AdMob</strong>. You are
never forced to watch one; every ad is something you choose to start in exchange for an
in-game bonus. When an ad loads, Google may collect:</p>

<table>
  <tr><th>Data</th><th>Purpose</th></tr>
  <tr><td>Device identifier (IDFA), when you allow it</td><td>Ad personalisation and measurement</td></tr>
  <tr><td>Advertising data (ads shown, viewed, clicked)</td><td>Ad delivery, fraud prevention, measurement</td></tr>
  <tr><td>Approximate location derived from IP address</td><td>Regional ad relevance and legal compliance</td></tr>
  <tr><td>Device and app information (model, OS version, app version)</td><td>Ad compatibility and reporting</td></tr>
</table>

<p>This data is collected and used by Google as an independent controller, under
<a href="https://policies.google.com/privacy">Google's Privacy Policy</a>. We never receive it
in a form that identifies you; we only see aggregate revenue and performance figures.</p>

<h2>Your choices</h2>
<p><strong>App Tracking Transparency.</strong> On first launch iOS asks whether Riskline may
track you across apps and websites. If you decline, no IDFA is shared and you receive
non-personalised ads. The game is fully playable either way — nothing is locked behind
consent. You can change this at any time in <em>Settings → Privacy &amp; Security → Tracking</em>.</p>

<p><strong>Consent in the EEA, UK and Switzerland.</strong> If you are in these regions, a Google
consent form appears before any ad is requested, letting you accept or refuse personalised
advertising and review each advertising partner.</p>

<p><strong>Resetting your advertising ID.</strong> <em>Settings → Privacy &amp; Security → Apple
Advertising</em> lets you reset the identifier at any time.</p>

<h2>Notifications</h2>
<p>If you allow notifications, Riskline schedules reminders locally on your device — for
example when your offline earnings are ready. These are generated on the device itself.
There is no push server and we hold no device token.</p>

<h2>Analytics</h2>
<p>Riskline contains no third-party analytics SDK. We do not track how you play.</p>

<h2>Children</h2>
<p>Riskline is not directed at children under 13 and we do not knowingly collect data from
them. The game deals with commodity trading and geopolitical risk, and is rated accordingly
on the App Store.</p>

<h2>Your rights</h2>
<p>Because we hold no personal data about you on our side, there is nothing for us to export
or erase — deleting the app removes everything held locally. For data collected by Google
through AdMob, exercise your access, rectification, erasure, restriction and objection rights
directly with Google using the link above. If you are in the EEA or UK, you may also lodge a
complaint with your national data protection authority.</p>

<h2>Changes</h2>
<p>If this policy changes materially, the date at the top will be updated and the revised
version published on this page.</p>

<h2>Contact</h2>
<p>Questions about this policy: <a href="mailto:risklinedev@gmail.com">risklinedev@gmail.com</a></p>

<footer>
  Riskline — William Pitot · <a href="./">Support</a>
</footer>

</body>
</html>
