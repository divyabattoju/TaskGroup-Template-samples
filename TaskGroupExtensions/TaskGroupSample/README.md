# TaskGroupTemplates
A sample extension which installs TaskGroups to release management.

vss-extension.json skeleton 
```json
{
  "manifestVersion": 1,
  "id": "rm-tg-extensions2", 
  "version": "0.1.0",
  "name": "Sample Taskgroup1", 
  "description": "Adds more tg templates to RM", 
  "publisher": "ms-devlabs",
  "public": true,
  "targets": [
    {
      "id": "Microsoft.VisualStudio.Services"
    }
  ],
  "screenshots": [
    {
      "path": "images/logo.png"
    }
  ],
  "content": {
    "details": {
      "path": "README.md"
    }
  },
  "icons": {
    "default": "images\\azureicon.png"
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
