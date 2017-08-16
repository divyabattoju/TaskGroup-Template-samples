# TaskGroupTemplates
A sample extension which installs TaskGroups to release management.

vss-extension.json skeleton format
```json
{
  "manifestVersion": 1,
  "id": "uniqueId", 
  "version": "0.1.0",
  "name": "Name of your task group", 
  "description": "Description for your task group", 
  "publisher": "publisher name",
  "public": true,
  "targets": [
    {
      "id": "Microsoft.VisualStudio.Services"
    }
  ],
  "screenshots": [
    {
      "path": "images/yourlogo.png"
    }
  ],
  "content": {
    "details": {
      "path": "README.md"
    }
  },
  "icons": {
    "default": "images\\yourimage.png"
  },
  "contributions": [
    {
      "id": "sample-tgtemplate",
      "type": "ms.vss-taskgroup.tg-template",
      "targets": [
        "ms.vss-taskgroup.tg-templates"
      ],
      "properties": {
        "values": [
          {
            "tasks": [
              {
                
              }
            ]
          }
        ]
      }  
    }
  ]
}
```
