### [Initial Release]

- Basic functionality:
    - Created initial HTML and CSS structure for the application.
    - Implemented basic note-taking functionality (title, content, theme switcher).
    - Added autosave functionality for user data. (Base64 encoding)

### [0.1.1]

- Enhanced autosave functionality:
    - Upgraded data compression using `gzip` for efficient storage.

### [0.1.2]

- Improved user experience:
    - Customized the appearance of the vertical scrollbar.

### [0.1.3]

- Added note metadata:
    - Implemented footer section displaying note's last update date and unique ID (for browser history search).

### [0.1.4]

- Optimized autosave behavior:
    - Introduced event-based triggers for save actions:
        - Mouse movement triggers immediate save.
        - Keystrokes initiate a delayed (debounced) save to avoid excessive writes.

### [0.1.5]

- Bug fix:
    - Resolved issue with dark theme toggle inadvertently updating note modification datetime.

### [0.1.6]

- Bug fix (related to the Gecko rendering engine):
    - Resolved issue with visual display mismatch in Firefox browser.
    - Resolved issue with saving data in Firefox browser.
