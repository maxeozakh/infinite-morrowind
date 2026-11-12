# infinite morrowind

a tiny char-rnn (plain numpy, no autograd) trained from scratch on all 440 in-game books from morrowind, tribunal and bloodmoon. the web demo runs the checkpoint right in the browser

demo: https://maxeozakh.github.io/infinite-morrowind/

- `rnn.py` — training. extracts the books straight from the game's `.esm` files (needs a steam install of morrowind)
- `export_web_model.py` — turns a checkpoint into `web/model.js`
- `web/` — the demo page

same code as [infinite shakespeare](https://github.com/maxeozakh/misc/blob/main/tinyshakespeare/rnn.py), only the data changed
