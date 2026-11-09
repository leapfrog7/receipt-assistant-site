# Receipt Assistant - manual installation

[Download v0.21.0](https://github.com/leapfrog7/receipt-assistant-site/releases/download/v0.21.0/email-diarisation-assistant-0.21.0.zip) | [Installation guide](https://leapfrog7.github.io/receipt-assistant-site/download.html) | [Privacy](https://leapfrog7.github.io/receipt-assistant-site/privacy.html)

This public repository hosts the product website and built extension releases. Download the named **email-diarisation-assistant-0.21.0.zip** release asset; GitHub's automatic Source code ZIP contains the website, not the loadable extension.

## Install

1. Download the extension ZIP and extract it into a permanent folder.
2. In your Mail Chrome profile, visit `chrome://extensions`.
3. Enable **Developer mode**, choose **Load unpacked**, and select the folder containing `manifest.json`.
4. Pin the extension, open Mail, and allow access to configured hosts. Use Settings for compatible ministry URLs.
5. Sign in to the eOffice portal, launch **eFile**, wait for its inbox, then use **Check again** in the assistant.

Keep the folder in place. Updates are manual: after current work finishes, replace files in the same folder, reload the extension and refresh Mail/eOffice. An organisation-managed browser may prohibit Developer mode or required permissions.

## Workflow

Open an email, choose a message if needed, edit the receipt subject and choose PDFs. **Email only**, **Email with attachments**, and **Attachments only** all hand off automatically to eOffice, upload the prepared PDF, fill the required defaults and click **Generate once**. A generated receipt is a real record; check eOffice before retrying an uncertain result.

The Chrome mail app uses one reusable companion with Arrange beside mail, Restore layout, Return to mail and Hide assistant. Normal Chrome tabs use the native side panel. Only PDF attachments are supported; Word/Excel/PowerPoint conversion is not included.

This manual-install testing release is separate from the Chrome Web Store submission and does not claim Store approval. Extension preparation is local; the requested receipt is sent to your configured eOffice service. Activation/retry eFile checks may contact that service before preparation. No automatic sign-in or keep-alive is provided.

Publisher: **Undersigned**. Support: **yatinnsit319@gmail.com**. Independent software; not an official Government, NIC, eOffice or Google product.
