# Course Unregistration Notification Email Template

## How to Use This Template

This email template uses placeholder variables that need to be replaced with actual data before sending.

### Placeholders

The template uses the following placeholders that need to be replaced:

- `{{student_name}}` - Student's full name
- `{{course_name}}` - Name of the course
- `{{course_code}}` - Course code/identifier
- `{{credits}}` - Number of credits
- `{{unregistered_by}}` - Person/system who unregistered the student
- `{{date_time}}` - Date and time of unregistration
- `{{support_email}}` - Support/contact email address
- `{{support_phone}}` - Support phone number

### Important Notes for Email Usage

1. **CSS must be inline**: Email clients don't support external CSS files. Use the `Mail.html` file with inline styles (see example script).

2. **Images need absolute URLs**: Replace relative image paths with full URLs:
   - Logo: `../Media/inpulse-logo.png` → `https://yourdomain.com/media/inpulse-logo.png`
   - GIF: `../Media/61de58c18b8a3f99119a2be6983bb12dfdd85edf.gif` → `https://yourdomain.com/media/61de58c18b8a3f99119a2be6983bb12dfdd85edf.gif`

3. **Test before sending**: Always test the email in multiple email clients (Gmail, Outlook, Apple Mail, etc.)


