# Privacy Policy — Meet Recording Helper

_Last updated: 2026-06-19_

Meet Recording Helper ("the extension") is a browser extension that detects when you
join or leave a Google Meet call and notifies a companion desktop application installed
on the same computer.

## Data we collect
**None.** The extension does not collect, store, or transmit any personal information,
browsing history, account information, or the content of your meetings.

## How the extension works
- The extension runs only on `https://meet.google.com`. It reads the page locally to
  determine whether you are currently in a call (joined or left).
- When the call state changes, the extension sends a single local message
  ("call started" / "call ended") to a companion desktop application on the same
  computer, using the browser's native messaging mechanism.
- This message is delivered **locally on your device only**. It is never sent to the
  developer, to any server, or to any third party.

## Data sharing
We do not sell, share, or transfer any data to third parties. The extension performs no
network communication of its own.

## Permissions
- **nativeMessaging**: to deliver the local call-state message to the companion desktop
  application.
- **Host access to meet.google.com**: to detect the call start/end on the Google Meet
  page. The extension does not access any other website.

## Changes
If this policy changes, the updated version will be posted at this URL with a new
"Last updated" date.

## Contact
Questions about this policy: <連絡先メールアドレスをここに記載>
