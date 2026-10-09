# Verdandi Privacy Policy

Applies to the Verdandi desktop application ("the app"), published by
Akshay M Singh ("we"). Last updated: 2026-10-09.

## The short version

Your documents stay yours. Page images go only to the AI model provider you
configure with your own key. The only things that reach us are (a) a periodic
anonymous access check, and (b) the contact details and feedback you choose
to send. We do not sell your data.

## What the app sends, and why

### 1. Access check (automatic)

On start and roughly every 12 hours the app asks our server whether this
installation may continue using paid extraction. It sends:

- a **random install ID** (a UUID generated on your machine; not derived from
  your identity),
- the **app version** and your **operating system** name.

It never sends documents, filenames, extracted values, or personal details.
Purpose: license/access control. Legal basis: legitimate interest in
protecting the software.

### 2. Contact details and feedback (only when you submit them)

The onboarding "Stay in touch" step and About → "Send feedback" are opt-in
and skippable. When you submit, we receive:

- your **name**, **email**, and **what you plan to use Verdandi for**
  (whatever you type; only the email is required for the form),
- any **feedback message** you write,
- the **install ID**, **app version** and **OS** (so we can follow up and,
  if needed, revoke a specific installation).

Purpose: replying to your feedback and improving the product. We never sell
this information. It is stored in a private spreadsheet accessible only to
us and a mail provider we use to correspond with you.

### 3. Your model provider

To read documents, the app sends **page images** of your PDFs to the AI
model provider you configured, using **your own gateway key**. That
processing is governed by that provider's privacy policy, not this one. We
never see your documents or your provider credentials (your key is stored in
your operating system's credential store).

### 4. Everything else

Runs, extracted data, review decisions, exports and logs stay in your local
workspace folder (`~/.verdandi`). The app contains no analytics, no ads, and
no third-party trackers.

## Retention and your rights

- Access-check records are kept only as a counter/verdict; the install ID is
  retained while we operate the access service.
- Contact details and feedback are kept until you ask us to delete them.
- To access, correct, or delete your information (or to ask what we hold),
  email **akshaymsingh.work@gmail.com** from the address you used, and we
  will act within 30 days. You may also stop all collection by not
  submitting the details form and by removing the app.

## Security

Data in transit uses HTTPS. Feedback rows are stored in an access-controlled
spreadsheet; the relay server holds no documents and no keys.

## Changes

We will update this policy in this file and note material changes in the
release notes. Continued use after a change means you accept it.
