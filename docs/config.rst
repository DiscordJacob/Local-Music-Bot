Config
======

.. _config-json:

config.json
-----------

prefix
    The prefix the bot uses.
owner
    The owner's Discord ID.
token
    Your bot's token. Defaults to email and password if not provided.
email
    Your bot's email. Optional if token provided.
password
    Your bot's password. Optional if token provided.
allowedChannels
    Array of **text** channel IDs which the bot will listen to. Used to avoid clogging up channel logs.
    
Example
-------

.. code-block:: json

    {
        "prefix": ">",
        "owner": "345678909876543",
        "token": "ABC123def987-zxyNOP546",
        "email": "",
        "password": "",
        "allowedChannels": ["23456789098765432", "23456789098765432", "23456789098765432"]
    }