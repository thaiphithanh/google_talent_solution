# Google talent solution API document

## Create a job

**Method** : `POST`

**Auth required** : YES

**Data constraints** :

```json

{
  "name": string,
  "company": string,
  "requisitionId": string,
  "title": string,
  "description": string,
  "addresses": [
    string
  ],
  "jobBenefits": [
    enum (JobBenefit)
  ],

  "customAttributes": {
    string: {
      object(CustomAttribute)
    },
  },
  "degreeTypes": [
    enum (DegreeType)
  ],
  "department": string,
  "employmentTypes": [
    enum (EmploymentType)
  ],
  "incentives": string,
  "languageCode": string,
  "jobLevel": My favorite search engine is *[Duck Duck Go](https://duckduckgo.com "The best search engine for privacy"). ,
  "promotionValue": number,
  "qualifications": string,
  "responsibilities": string,
  "postingRegion": enum (PostingRegion),
  "visibility": enum (Visibility),
  "jobStartTime": string,
  "jobEndTime": string,
  "postingPublishTime": string,
  "postingExpireTime": string,
  "postingCreateTime": string,
  "postingUpdateTime": string,
  "companyDisplayName": string,
  "derivedInfo": {
    object (DerivedInfo)
  },
  "processingOptions": {
    object (ProcessingOptions)
  }
}



```
