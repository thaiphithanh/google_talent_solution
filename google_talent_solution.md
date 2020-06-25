# Google talent solution API document

Create a company
**Method**: `POST`
**Auth required** : YES

```json
[
    {
        "name": string,
        "displayName": string,
        "externalId": string,
        "websiteUri": string,
        "careerSiteUri": string,
        "imageUri": string,
        "keywordSearchableJobCustomAttributes": [
            string
        ],
        "derivedInfo": {
            object (DerivedInfo)
        },
        "suspended": boolean
    }
]

```




