# comp

> இரண்டு கோப்புகள் அல்லது கோப்புகளின் தொகுப்புகளின் உள்ளடக்கங்களை ஒப்பிடுக.
> கோப்புகளின் தொகுப்புகளை ஒப்பிட, வைல்டு கார்டுகளைப் (*) பயன்படுத்தவும்.
> மேலும் விவரத்திற்கு: <https://learn.microsoft.com/windows-server/administration/windows-commands/comp>.

- கோப்புகளை ஊடாடும் வகையில் ஒப்பிடுக:

`comp`

- இரண்டு குறிப்பிட்ட கோப்புகளை ஒப்பிடுக:

`comp {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`

- இரண்டு செட் கோப்புகளை ஒப்பிடுக:

`comp {{அடைவு_1\பாதை}}\* {{அடைவு_2\பாதை}}\*`

- தசம வடிவத்தில் வேறுபாடுகளைக் காண்பி:

`comp /d {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`

- ASCII வடிவத்தில் வேறுபாடுகளைக் காண்பி:

`comp /a {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`

- வேறுபாடுகளுக்கான வரி எண்களைக் காண்பி:

`comp /l {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`

- கோப்புகளை கேஸ்-உணர்வின்றி ஒப்பிடுக:

`comp /c {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`

- ஒவ்வொரு கோப்பின் முதல் 5 வரிகளை மட்டும் ஒப்பிடுக:

`comp /n=5 {{கோப்பு_1\பாதை}} {{கோப்பு_2\பாதை}}`
