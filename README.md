{
  "$schema": "https://developer.microsoft.com/json-schemas/sp/v2/column-formatting.schema.json",
  "elmType": "button",
  "txtContent": "Submit",
  "customRowAction": {
    "action": "executeFlow",
    "actionParams": "{\"id\": \"5b668945-4e53-4d45-bbae-6174f7f8af11\"}"
  }
}



{
“$schema”: “https: //developer.microsoft.com/en-us/json-schemas/sp/column-formatting.schema.json”,
“elmType”: “span”,
“style”: {
“color”: “#0078d7”
},
“children”: [
{
“elmType”: “span”,
“attributes”: {
“iconName”: “Flow”
}
},
{
“elmType”: “button”,
“style”: {
“border”: “none”,
“background-color”: “transparent”,
“color”: “#0078d7”,
“cursor”: “pointer”
},
“txtContent”: {
“operator”: “+”,
“operands”: [
“[$Policy_x0020_Owner.title]”,
“ Approval”
]
},
“customRowAction”: {
“action”: “executeFlow”,
“actionParams”: “{\”id\”: \”86dfdf10-8d99-4914-8e98-fe4b21ed7e34\”}”
}
}
]
}
