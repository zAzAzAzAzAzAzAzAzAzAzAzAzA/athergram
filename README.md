<p align="center">
    <a href="https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram">
        <img src="https://raw.githubusercontent.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram/dev/docs/source/static/img/pyrogram.png" alt="Pyrogram" width="128">
    </a>
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://zAzAzAzAzAzAzAzAzAzAzAzAzA.github.io/athergram/">
        Documentation
    </a>
    •
    <a href="https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram/releases">
        Releases
    </a>
</p>

## Pyrogram Fork

> Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots

**Note:** This is a fork of [Pyrogram](https://github.com/pyrogram/pyrogram) maintained by [Aes](https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA). Original copyright and credits belong to Dan and Pyrogram contributors.

``` python
from pyrogram import Client, filters

app = Client("my_account")


@app.on_message(filters.private)
async def hello(client, message):
    await message.reply("Hello from Pyrogram!")


app.run()
```

**Pyrogram** is a modern, elegant and asynchronous [MTProto API](https://zAzAzAzAzAzAzAzAzAzAzAzAzA.github.io/athergram/topics/mtproto-vs-botapi)
framework. It enables you to easily interact with the main Telegram API through a user account (custom client) or a bot
identity (bot API alternative) using Python.

### Key Features

- **Ready**: Install Pyrogram with pip and start building your applications right away.
- **Easy**: Makes the Telegram API simple and intuitive, while still allowing advanced usages.
- **Elegant**: Low-level details are abstracted and re-presented in a more convenient way.
- **Fast**: Boosted up by [TgCrypto](https://github.com/ohmyarthur/tgcrypto), a high-performance cryptography library written in C.  
- **Type-hinted**: Types and methods are all type-hinted, enabling excellent editor support.
- **Async**: Fully asynchronous (also usable synchronously if wanted, for convenience).
- **Powerful**: Full access to Telegram's API to execute any official client action and more.

### Installing

**From GitHub Releases (Recommended):**

``` bash
pip3 install git+https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram.git@latest
```

**With TgCrypto for better performance:**

``` bash
pip3 install git+https://github.com/ohmyarthur/tgcrypto.git
pip3 install git+https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram.git@latest
```

### Resources

- Check out [the documentation](https://zAzAzAzAzAzAzAzAzAzAzAzAzA.github.io/athergram) to learn more about Pyrogram, get started right away and discover more in-depth material for building your client applications.

- Join our [Telegram community](https://t.me/honlyonee) for discussions and support.
- Reach out to [@durovpalsu](https://t.me/durovpalsu) for questions.