---
layout: page
title: SMS Opt-In
permalink: /sms-opt-in/
---

# {{ page.title }}

Sign up to receive personal alerts and reminders by text message.

<form id="sms-opt-in-form" style="max-width: 720px; margin-top: 1.5rem;">
  <div style="margin-bottom: 1rem;">
    <label for="name"><strong>Name</strong></label><br>
    <input id="name" name="name" type="text" placeholder="Your name" style="width: 100%; padding: 0.75rem; margin-top: 0.4rem;" />
  </div>

  <div style="margin-bottom: 1rem;">
    <label for="phone"><strong>Mobile phone number</strong></label><br>
    <input id="phone" name="phone" type="tel" placeholder="(555) 555-5555" style="width: 100%; padding: 0.75rem; margin-top: 0.4rem;" />
  </div>

  <div style="margin-bottom: 1rem; padding: 1rem; border: 1px solid #ddd; border-radius: 8px;">
    <label for="consent" style="display: flex; gap: 0.75rem; align-items: flex-start;">
      <input id="consent" name="consent" type="checkbox" style="margin-top: 0.25rem;" />
      <span>
        By checking this box and submitting this form, you agree to receive recurring SMS messages from <strong>Sam's Stock Recommendation Project</strong> for personal alerts and reminders. Message frequency varies. Message and data rates may apply. Reply <strong>STOP</strong> to opt out and <strong>HELP</strong> for help. Consent is not a condition of purchase. View our <a href="/privacy">Privacy Policy</a> and <a href="/terms">Terms &amp; Conditions</a>.
      </span>
    </label>
  </div>

  <p>After you submit this form, we will send a confirmation text. You must reply <strong>YES</strong> to complete your opt-in.</p>

<button type="submit" style="padding: 0.85rem 1.25rem; font-weight: 600;">Sign Up for SMS Alerts</button>

