# WorkPulse Privacy

WorkPulse is local-first.

## Local Data

Tasks, projects, reviews, language settings, and reminder settings are stored locally on the user's Mac.

## API Keys

OpenAI-compatible API keys are stored in macOS Keychain. They are not stored in plain text inside the app bundle.

WorkPulse checks whether a key exists for status display. It reads the key value only when saving a new key, testing the connection, clearing the key, or generating an AI review.

## AI Review

AI review is optional. If the user configures an API key and clicks Generate in Reviews, WorkPulse sends only the selected review period's aggregated summary data to the configured provider.

WorkPulse does not upload the full local database.

If no API key is configured, reviews are generated from local statistics only.

## Notifications

Daily progress reminders and due-date reminders are scheduled through macOS notifications.

## Analytics

WorkPulse does not include analytics, tracking, accounts, or cloud sync.
