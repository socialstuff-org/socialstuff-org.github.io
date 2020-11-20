# Crypto Storage Service

The crypto storage service takes care of securely storing all kind of information to the applications local storage.  

<span style="color: #ff0000;">**// TODO extend description**</span>

## Table of Contents
- [Directory Structure](#directory-structure)
    - [Version 0.1.0](#version-010)
    - [Version 0.2.0](#version-020)

## Directory structure
In the contact directory all information related to communication with contacts are stored.
This includes the following details:
- [chat partner public key]() <span style="color: #ff0000;">**// TODO add link to public key explanation (identity service)**</span>
- [conversation key]() <span style="color: #ff0000;">**// TODO add link to conversation key explanation (messaging service & backend)**</span>
- properties file (including settings such as local name, whether read and delivery receipts are being performed, etc.)
- chat file: containing the actual conversation
- media files: directory containing all media files which have been shared in the conversation

### Version 0.1.0
```
Contacts
    Alice
        alice-public-key.txt
        conversation-key.txt
        properties.txt
        chat.txt
        media-files
            file1
            file2
            file3
    Bob
        bob-public-key.txt
        conversation-key.txt
        properties.txt
        chat.txt
        media-files
    Charly
        charly-public-key.txt
        conversation-key.txt
        properties.txt
        chat.txt
        media-files
```

### Version 0.2.0
***// NOTE: maybe add padding on usernames to further eliminate relevant metadata***

```
.trale
    45ee23 (own username hash)
        master.key
        chats
            45237 (chat partner username hash)
                chat.properties
                    conversation key
                    rsa public key
                    custom display name
                chat.log
                [profile image]
        media
            ff56a3
            67hd2e
        contacts (chat partner username listing)
        rsa private key
        rsa public key
```
