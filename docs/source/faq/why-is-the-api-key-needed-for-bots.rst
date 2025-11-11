Why is the API key needed for bots?
===================================

Requests against the official bot API endpoints are made via JSON/HTTP and are handled by an intermediate server
application that implements the MTProto protocol and uses its own API key to communicate with the MTProto servers.

Using MTProto is the only way to communicate with the actual Telegram servers, and the main API requires developers to
identify applications by means of a unique key; the bot token identifies a bot as a user and replaces the user's phone
number only.

.. tip::

    The Bot API server uses its own API key when communicating with Telegram via MTProto. Your bot needs both the bot token (for user identity) and an API key (for application identity).