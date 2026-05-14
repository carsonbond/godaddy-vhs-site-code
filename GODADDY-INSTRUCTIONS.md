# GoDaddy Website Builder – A2P Fix Instructions

Follow these steps in order. Each section takes about 5–10 minutes.

---

## STEP 1 — Add the Privacy Policy Page

1. Log in to your GoDaddy account and open **Website Builder**.
2. In the top menu, click **Pages** → **Add Page**.
3. Name the page: `Privacy Policy`
4. Set the URL/slug to: `privacy-policy`
5. On the new page, **delete any default blocks** so you have a blank canvas.
6. Click **Add Section** → choose **HTML** (or "Embed Code" / "Custom HTML" depending on your builder version).
7. Open the file `privacy-policy.html` from this repository, **select all the code** (Ctrl+A / Cmd+A), and **paste it** into the HTML block.
8. Click **Done** / **Save**.
9. Make sure the page is **published** and accessible at:
   `https://veteranhealthsolutions.net/privacy-policy`

---

## STEP 2 — Add the Terms of Service Page

Repeat the same steps as above but use the file `terms-of-service.html`:

1. Click **Pages** → **Add Page**.
2. Name: `Terms of Service`
3. Slug/URL: `terms-of-service`
4. Add an HTML block, paste in the contents of `terms-of-service.html`.
5. Save and publish.
6. Confirm it's live at:
   `https://veteranhealthsolutions.net/terms-of-service`

---

## STEP 3 — Add Footer Links (Terms & Privacy)

A2P registration requires Terms of Service and Privacy Policy links in the **footer of every page**.

1. In GoDaddy Website Builder, click on your **footer** section to edit it.
2. Add a **Text** element (or edit an existing one).
3. Type: `Terms of Service  |  Privacy Policy`
4. Highlight **"Terms of Service"**, click the **link** icon, and enter:
   `https://veteranhealthsolutions.net/terms-of-service`
5. Highlight **"Privacy Policy"**, click the **link** icon, and enter:
   `https://veteranhealthsolutions.net/privacy-policy`
6. Save and publish.
7. Check every page of your site to confirm the footer links appear.

---

## STEP 4 — Add SMS Consent to the Contact Form

This is the **most important fix** for A2P approval. Your contact form needs a checkbox with the exact consent language below.

### In GoDaddy Website Builder:

1. Navigate to your **Contact Us** page.
2. Click on your **contact form** to edit it.
3. Click **Add Field** → choose **Checkbox**.
4. For the checkbox label, paste this exact text:

---

**Checkbox label text (copy this exactly):**

```
By checking this box, I consent to receive SMS text messages from Veteran Health Solutions LLC 
at the phone number provided. Message frequency may vary. Message & data rates may apply. 
Reply STOP to opt out at any time. Reply HELP for help. 
View our Privacy Policy: https://veteranhealthsolutions.net/privacy-policy
```

---

5. Make the checkbox **required** (so it must be checked before the form submits).
6. Save and publish.

### If GoDaddy's form doesn't support a Checkbox field:

Add a **Text block** directly above the form's submit button with this language:

> *By submitting this form, you consent to receive SMS text messages from Veteran Health Solutions LLC at the number provided. Msg & data rates may apply. Reply STOP to opt out. View our [Privacy Policy](https://veteranhealthsolutions.net/privacy-policy) and [Terms of Service](https://veteranhealthsolutions.net/terms-of-service).*

---

## STEP 5 — Confirm Your Chat Widget Is Live

Before submitting for A2P registration, open your website in a **regular browser window** (not incognito, and not the editor preview) and confirm:

- [ ] The GoHighLevel chat bubble appears in the bottom corner of the page
- [ ] The chat widget's opt-in language mentions SMS messaging
- [ ] Your Terms & Privacy links are clickable in the footer
- [ ] The contact form has the SMS consent checkbox

---

## Summary Checklist

| Item | Status |
|------|--------|
| Privacy Policy page live at `/privacy-policy` | ⬜ |
| Terms of Service page live at `/terms-of-service` | ⬜ |
| Footer has links to both on all pages | ⬜ |
| Contact form has SMS consent checkbox | ⬜ |
| Chat widget is visible in regular browser | ⬜ |

Once all boxes are checked, you're ready to re-submit your A2P registration.
