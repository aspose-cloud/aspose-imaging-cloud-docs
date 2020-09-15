---
title: "Add Tag and Reference Image to Search Context"
type: docs
url: /add-tag-and-reference-image-to-search-context/
weight: 90
---

# **Introduction**
This article explains how to add Tag and Reference Image to Search Context.

The API URL is: [POST /imaging/ai/imageSearch/{searchContextId}/addTag](https://apireference.aspose.cloud/imaging/#/SearchContext/CreateImageTag)
## **Resource URI**
[Swagger UI](https://apireference.aspose.cloud/imaging/#/SearchContext/CreateImageTag) lets you call Aspose.Imaging REST APIs directly from the browser. The description of the APIs and their parameters are also given there.
## **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

// First get Access Token

// Get App Key and App SID from https://dashboard.aspose.cloud/

curl -v "https://api.aspose.cloud/oauth2/token" \

-X POST \

-d 'grant\_type=client\_credentials&client\_id=xxxx&client\_secret=xxxx' \

-H "Content-Type: application/x-www-form-urlencoded" \

-H "Accept: application/json"



// cURL example to find similar images

curl -v "https://api.aspose.cloud/v2/imaging/ai/imageSearch/cc435948-2dc3-4269-9299-052baa314d72/addTag?tagName=MyTag" \

-X POST \

-T aspose\_logo.png \

-H "Content-Type: application/json" \

-H "Accept: multipart/form-data" \

-H "Authorization: Bearer <access\_token>"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

No Response

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
Using an SDK (API client) is the quickest way for a developer to speed up the development. An SDK takes care of a lot of low-level details of making requests and handling responses and lets you focus on writing code specific to your particular project. Check out our [GitHub repository](https://github.com/aspose-imaging-cloud) for a complete list of Aspose.Imaging SDKs along with working examples, to get you started in no time.
## **SDK Examples**
{{< tabs tabTotal="1" tabID="4" tabName1="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "d66d31a62aa65f7dee66a6a655153f47" "AddTagAndReferenceImageToSearchContext.java" >}}

{{< /tab >}}

{{< /tabs >}}
