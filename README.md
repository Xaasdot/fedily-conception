# Fedily Conception

## **Fedily**

![Fedily Logo](media/fedily_logo.svg)

*Fediverse and more, universally*

### 1) Own your data and explicitly choose what is shared threw each registered third-party account

*Your online identity, your contact repository, your tree view page, your password manager and all your social media and third-party services inside **one** advanced and secured FOSS solution*

   * Federated secured server (encrypted data : passphrase)
   * Custom secured smartphone app and webbrowser add-on client (encrypted data : passphrase)
   * Open and secure standard to make it easily adopted by everyone : users as institutions
       * *Log in with Fedily* on every social instance of the fediverse (Mastodon, Pixelfed, ...) 
       * *Connect to Fedily* account on devices (linux, android...)
       * Export your vCard (adapted new version) profile | *qrCard*
       * Easily migrate your Fedily account from a server to another (export/import or direct link)
       * Generate and/or store all your passwords for each accounts
       * Export all your credentials in a KeepassX database format (.kdbx)
       * Import all your passwords from your password manager and use **Fedily** as your secured advanced password manager
       * Customize all the predefined settings (defined out-of-the-box initially for an easy access)
       * Create templates of configurations and settings of your **Fedily** account
       * 2FA authentication for profile edition
       * Credentials : one random (generated on registration) unique _ID number_ and one chosen secured _passphrase_ to connect to your account (must be kept securely out of the app because it can't be retrieved)
       * You can create an _alias_ of the _ID number_ to connect to the **Fedily** instance (whatever you desire from another random suite of character to a mail or a pseudo) but this _alias_ must be unique on your **Fedily** instance.
       * The _ID number_ or _alias_ will by default be saved in the app client (can be opt-out) and the _passphrase_ can be too by enabling an opt-in option.
   * Handle all your web accounts in the same app
   * Keep your online identity clean and clear
   * Manage all the aspects of your online identity
   * Allow some volountary and democratic state or NGO institutions to apply a check on user chosen profiles to allow the access on certain specific services (for example : adding a profile for [the European Digital Identity](https://ec.europa.eu/info/strategy/priorities-2019-2024/europe-fit-digital-age/european-digital-identity_en))


**An account means** :

   * Multiple contained and secured profiles which can be renamed (for example Fediverse, Personnal, Gaming, Professionnal, ...)
   * Each profile can be customed and shared separately with :
       * inherit primary information: firstname, lastname, nationality...
       * chosen or given, editable, private information : pgpkey, institutionnal eID, health care number, bank account, cryptowallet, phone number, address...
       * public social \& services accounts, profile photos, cover photos...
   * Each kind of custom information has a *public info* part **and** a *private info* part.
   * Add a public _Tree View_ of your account for each profile
   * Use some **officialy checked** profile to address professionnal or governmental services
   * Use of 2FA restricted connection to edit a profile
   * Sharing your profile to your contacts threw a Qrcode or NFC (or also opt-in bluetooth tracker to suggest contacts profile based on if you met them and they add the same setting enabled)
   * Disable screenshots on profile settings
   * Option to read the contacts vCard book of your device and check for shared corresponding info inside the federated network to suggest more contacts profile on **Fedily**
   * Option to share selected profile unique info to the federated network to help your contacts discover you and appear in their suggestion 
   * Create groups of contacts and make it appearing on all your social media third-party accounts (_only if the third party service allows it, see [the list here](thrid_party_services_list.md)_)
      * Option to share groups for each linked account
      * Option to lock the view of a chosen profile with a password
      * Based on a profile, suggest automatically accounts

*Own your data and share securely and precisely what you want with your contacts*

### 2) Link several accounts and follow your contact accounts



   * Choose who sees what in your contacts
   * Watch the federated feed your contacts want you to see
   * Synchronise all your social media in one thanks to linked accounts (_only works with supported third party services, see [the list here](thrid_party_services_list.md)_)

*No tracking, no private info leaking, only led by the community, for you* 

## Steps

* Create KeepassX plugin for Profile handling. You can create as many profiles/identities as you want. One profile has a name/pseudo, a unique key and allows to link selected inputs of your _kdbx_ one one unique page defining your identity. Each input can be set as private or public on your profile and can be tagged with custom tags. Each input of a profile page can be renamed from the _kdbx_ database while keeping the link between inputs. Edits on the database directly influence the profile pages in which inputs are linked.

## License

GPLv3
