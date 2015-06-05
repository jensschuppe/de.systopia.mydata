# SYSTOPIA MyData extension
CiviCRM extension to allow API access to your own data

**This extension offers API wrappers for these five entities:**
 * Contact => MyContact
 * Address => MyAddress
 * Phone => MyPhone
 * Email => MyEmail
 * Contribution => MyContribution (read only)

They only allow viewing and editing *your own* contact and its associated address/email/phone.

The API calls require the ``view my contact`` and ``edit my contact`` respectively.
