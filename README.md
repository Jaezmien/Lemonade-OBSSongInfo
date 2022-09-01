<div align="center">
  
# 🍋 Lemonade - OBS Song Info

</div>

1. Install [Lemonade](https://github.com/Jaezmien/Lemonade) on your NotITG theme.
2. Insert `OBSSongInfo.xml` to `Screens/Overlay/LemonScripts/`.
3. Run the command:

```bash
# Requries Python 3

$ pip install -r requirements.txt
$ python main.py
```

4. Read `info.txt` on OBS to show the current song info.

### Format

To edit the format of `info.txt`, change the contents of `format.txt`

What is avaialble:

- ``{{ SONG_TITLE }}``
- ``{{ SONG_SUBTITLE }}``
- ``{{ ARTIST }}``

Example:

```
{{ ARTIST }} - {{ SONG_TITLE }} ({{ SONG_SUBTITLE }})
```