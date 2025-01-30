# line3
{
  "type": "bubble",
  "size": "hecto",
  "direction": "ltr",
  "hero": {
    "type": "image",
    "url": "https://i.imgur.com/a5GGROv.png",
    "size": "full",
    "aspectRatio": "20:13",
    "aspectMode": "cover",
    "action": {
      "type": "uri",
      "uri": "https://line.me/"
    }
  },
  "body": {
    "type": "box",
    "layout": "vertical",
    "contents": [
      {
        "type": "text",
        "text": "LINE PAY",
        "weight": "bold",
        "size": "xl"
      },
      {
        "type": "text",
        "text": "您已收到NT$250。(來自:啊橙)",
        "offsetTop": "none",
        "offsetBottom": "none",
        "offsetStart": "none",
        "offsetEnd": "none",
        "size": "sm"
      }
    ]
  },
  "footer": {
    "type": "box",
    "layout": "vertical",
    "spacing": "sm",
    "contents": [
      {
        "type": "button",
        "style": "secondary",
        "height": "sm",
        "action": {
          "type": "uri",
          "label": "了解更多",
          "uri": "https://line.me/"
        }
      },
      {
        "type": "separator",
        "margin": "sm"
      },
      {
        "type": "box",
        "layout": "baseline",
        "contents": [
          {
            "type": "icon",
            "url": "https://i.imgur.com/UKWjcIM.png",
            "offsetTop": "sm",
            "size": "xs",
            "margin": "none"
          },
          {
            "type": "text",
            "text": "LINE PAY",
            "size": "xs",
            "offsetTop": "xs",
            "offsetStart": "sm"
          },
          {
            "type": "icon",
            "url": "https://i.imgur.com/aKbXQ9D.png",
            "size": "xxs",
            "margin": "xs",
            "offsetTop": "sm"
          }
        ]
      }
    ],
    "flex": 0
  },
  "styles": {
    "hero": {
      "separator": true
    }
  }
}
