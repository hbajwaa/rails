*   Deprecate `Rails.application.credentials.action_mailbox.api_key` and `MAILGUN_INGRESS_API_KEY` in favor of `Rails.application.credentials.action_mailbox.signing_key` and `MAILGUN_INGRESS_SIGNING_KEY`.

    *Matthijs Vos*

*   Allow easier creation of multi-part emails from the `create_inbound_email_from_mail` and `receive_inbound_email_from_mail` test helpers.

    *Michael Herold*

*   Fix Bcc header not being included with emails from `create_inbound_email_from` test helpers.

    *jduff*

*   Add `ApplicationMailbox.mailbox_for` to expose mailbox routing.

    *James Dabbs*


Please check [6-0-stable](https://github.com/rails/rails/blob/6-0-stable/actionmailbox/CHANGELOG.md) for previous changes.
