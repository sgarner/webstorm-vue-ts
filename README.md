# webstorm-vue-ts

Minimal reproduction to demonstrate a bug in WebStorm 2023.2 with TypeScript in Vue templates.

When a &lt;script&gt; tag appears inside the &lt;template&gt; section of a Vue single file component,
the actual component script is treated as vanilla JS by WebStorm.

### ❌ With script in template:

![Screenshot](https://uccf6601d08713c5ee5eff4637d5.previews.dropboxusercontent.com/p/thumb/AB-o6Vclbf0p4wpwEGpY4LHEIZCx8IpfhNPTRH6rQQSMaxYzO4nKMy9fgqd9GZAynv4NJMtcrfvn5TbIU-Mjd3iv-Rtkf7d2rGEx6WvbqW0ahRGGVMDp1g7CDEGShvEATEW4n2eK2ibHXvngblWCGUXCsh9mZJVUZ_I4ff1Egc51uW1aq3HceGh5trGOevnw8WwRwSTxQjLrMbLvkuRbpPCKObdwA7A7W94852ZrSX3MwCTULEeXtSUfhd3Cfr1TwRoPmatlFpnHo7YGCy6tFjf_DM0o8-NJFzBSghAvFYGBAuDoCTEvLT6w7fJBarCxopGkSnQA2X0lqW6_bLGxyBYWcFq-IlZyjuCkWA-9AbH7sw/p.png)

### ✅ Without script in template:

![Screenshot](https://uc7f1910ae12158f988995815fdb.previews.dropboxusercontent.com/p/thumb/AB80uoBqB6IqHAVY7glhxOL1cs-kEGDW_WDIUps4UoM0ZmTbKBSaOh8Wpqu4drCaFc-3vQMeAkIvmiTUQ2y2J1YIwe4uWgYg6YAyQBjJ25hN0jJ8zw6vqPINbb-y69iX7QeHdbGtu9uo_NTqFy167KbIYd4cKWgNFXM_ivr79qnl2wTw7uze6auQnUbj_vLsuJrAJ57CcPncQWRSKmKVpi_2r-MDB5JsK_5sfUK_Glvl_P_ofds-QPnJuYGbWrGy8cv1_hgkksuoO06H-MrRt_XziVHBlXSevICEY3cgnVUZMALSJTaiH9h8mNkwg7iy6voEDFVa38P067tG6GElwj9f7SEWNenrIJFTIKqBrLmGXQ/p.png)
