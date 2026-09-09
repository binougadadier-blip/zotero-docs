---
tags:
  - kb
  - sync
---

# Why is Zotero saying it can't access the Linux keyring when I try to sync?

For increased security, Zotero 10 and later save sync credentials — the Zotero API key and, optionally, a WebDAV username/password — to the operating system keystore rather than storing them (effectively) unencrypted within the [profile directory](/support/kb/profile_directory).

On some Linux systems, you may need to install gnome-keyring, KWallet, or another Secret Service provider. On an institutional computer, you may need to ask your IT department for assistance.

If Zotero can't access the keyring, it will also give you the option of saving credentials unencrypted. This is how credentials were stored in versions prior to Zotero 10, but it makes credentials more vulnerable to being stolen by malware on your computer.
