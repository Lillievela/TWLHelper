# TWLHelper, DS⁽ⁱ⁾ Mode Hacking Discord server bot

## How to use

1. Make a copy of `settings.json.example` and name it `settings.json`.
1. Set your bot's token ID.
    - You will need to create a bot over at [Discord Developer Portal](https://discord.com/developers/applications).
1. You can also set other arguments in `settings.json`, such as command prefix, account status, and moderator roles.
    - It is recommended to use IDs rather than names for Moderator Roles to make sure jishaku can't be hijacked.
1. Install the following for your host:
    - Python 3.9.x (and its respective pip)
        - This must be 3.9.x as exception parser is broken as of 3.10.x.
    - gifsicle 1.92 or later
    - ffmpeg
1. Run `pip install -r requirements.txt`
1. Run the following command:
    - UNIX-based: `python3 twlhelper.py`
    - Windows: `py twlhelper.py`

## License
```
ISC License

Copyright (C) 2021-present DS-Homebrew

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

## Credits
- Discord.py: This wouldn't exist without it
- [Nintendo Homebrew's Kurisu](https://github.com/nh-server/kurisu): `utils.py` error embeds, `load.py`, `assistance.py`, netinfo, simple_embed
    - Licensed under Apache 2.0. See source, or see http://www.apache.org/licenses/LICENSE-2.0.
- [YourKalamity](https://github.com/YourKalamity): `convert.py` code used with permission
