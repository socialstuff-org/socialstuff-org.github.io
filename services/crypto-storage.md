# Crypto Storage Service

The crypto storage service takes care of securely storing all kind of information to the applications local storage.  

<span style="color: #ff0000;">**// TODO extend description**</span>


## Directory structure
In the contact directory all information related to communication with contacts are stored.
This includes the following details:
- [chat partner public key]() <span style="color: #ff0000;">**// TODO add link to public key explanation (identity service)**</span>
- [conversation key]() <span style="color: #ff0000;">**// TODO add link to conversation key explanation (messaging service & backend)**</span>
- properties file (including settings such as local name, whether read and delivery receipts are being performed, etc.)
- chat file: containing the actual conversation
- media files: directory containing all media files which have been shared in the conversation

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
