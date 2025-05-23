Add Ebernati token metadata”

---
---

---

PRs are reviewed in bulk and and can take up to **two weeks** to be merged.

_This repository is managed using an auto merge action. Please ensure your PR has no deleted lines, and it will be merged._



Please include change to the `src/tokens/solana.tokenlist.json` file in the PR.
DON'T modify any other token on the list.

At minimum each entry should have

- Token Address: AJgMw4WRQoJscFkyqp6nXQgmUXHgf9oL9seHBFuAmWq4
- Token Name:Ebernati
- Token Symbol:EBI
- Logo: 
![](https://github.com/ebernati/token-list/blob/8ffb1aae09cbcf89b33bbe9ee20210c5982ca970/assets/mainnet/BE183A50-6F42-421C-AC45-1266DEDCDC24.png)

- Link to the official homepage of token: https://ebernati.github.io/ebernati-token/
- Coingecko ID if available (https://www.coingecko.com/api/documentations/v3#/coins/get_coins__id_):

## Auto merge requirements

Your pull request will be automatically merged if the following conditions are met:

- Your pull request **only adds new tokens** to the list. Any modification to existing
  tokens will require manual review to prevent unwanted modifications.

- Your pull request does **not touch unrelated code**. In particular, reformatting changes to unrelated
  code will cause the auto merge to reject your PR.

- Any **asset files added correspond to the token address** you are adding. Asset files
  must be PNG, JPG or SVG files.

- Your change is **valid JSON** and **conforms to the schema**. If your change failed validation,
  read the error message carefully and update your PR accordingly.

- No other tokens shares the **same name, symbol or address**.

For example, this change would be rejected due to unrelated changes:

<img src=https://i.imgur.com/qB9RNO4.png width=600px>

The bot runs **every 60 minutes** and bulk-merges all open pull requests to prevent conflicts.
This means that you need to wait up to 60 minutes for your pull request to be merged or reprocessed.
