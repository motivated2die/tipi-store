# Open Archiver

Open Archiver is a modern, open-source email archiving solution designed to keep your email history safe, searchable, and accessible.

### Features

-   **Universal Compatibility:** Archive emails from Google Workspace, Microsoft 365, and any Generic IMAP server.
-   **Full-Text Search:** Powered by Meilisearch for lightning-fast search results within email bodies and attachments.
-   **Attachment Indexing:** Uses Apache Tika to extract and index text from PDF, Word, and Excel attachments.
-   **Encryption:** Supports encryption of sensitive database fields and file storage at rest.
-   **Modern UI:** A clean, fast interface built with SvelteKit.

### Initial Setup

Once installed, open the app. You will be redirected to a `/setup` page where you will create your initial Admin account.

### Security

This installation automatically generates secure, random passwords and encryption keys for Postgres, Redis, Meilisearch, and internal data encryption. These keys are stored in the Runtipi environment configuration.