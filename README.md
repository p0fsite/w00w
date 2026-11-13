<p align="center">
  <img src="public/w00w.svg" alt="w00w" width="148">
</p>

<p align="center">
  For anyone who wants a website and does not know how to make one.<br>
  Paste a page you like, or write one sentence. Get a site you can send.
</p>

<p align="center">
  <a href="https://x.com/w00wapp">X</a>
  ·
  <a href="https://t.me/w00w_portal">Telegram</a>
</p>

## How it works

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>1. Say it</strong><br><br>
      Paste any public page as the example, or write the name, the price, the hours, and the door.
    </td>
    <td width="33%" valign="top">
      <strong>2. Read it</strong><br><br>
      w00w writes one site. A pasted page comes back as a new site in that spirit, not a copy of theirs.
    </td>
    <td width="33%" valign="top">
      <strong>3. Send it</strong><br><br>
      Connect a Solana wallet and publish. The link looks like <code>/s/lane-coffee</code>.
    </td>
  </tr>
</table>

```text
Lane Coffee. Open until 2. Milk is 4. Second door on the left.
```

The name, the price, the hours, and the door stay as written. If a line is wrong, say what to change. A site that is already live keeps the same link.

There is no contract yet, so posting does not burn tokens.

## Run it

```bash
npm install
cp .env.example .env
npm run dev
```

Open `http://127.0.0.1:5173`.

| Key | Where it is used |
| --- | --- |
| `XAI_API_KEY` | The model that writes the site. Server only. |
| `HF_CREDENTIALS` | Optional. Server only. `key-id:key-secret` |

Leave a key blank until you have it. Do not commit `.env`.
