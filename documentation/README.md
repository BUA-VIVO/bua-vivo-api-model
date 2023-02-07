     

### <a id="documentation-body"></a>

![Hackolade image](BUA%20API%20MODEL%20documentation/image1.png?raw=true)

JSON SCHEMA FOR THE BUA API MODEL
-------------------

#### Schema for:

Model name: BUA API MODEL

Author: Rolf Guescini, Florian Kotschka

Version: 1

Printed On: Tue Feb 07 2023 13:18:09 GMT+0100 (Central European Standard Time)

Created with: [Hackolade](https://hackolade.com/) - Polyglot data modeling for NoSQL databases, storage formats, REST APIs, and JSON in RDBMS

### <a id="contents"></a>

*   [Table of Contents](#contents)
*   [1\. Groups](#containers)
    *   [1.1 BUA API MODEL](#8be31291-b199-42e0-a35b-1a2f226d5f5b)
        
        [1.1.2. Documents](#8be31291-b199-42e0-a35b-1a2f226d5f5b-children)
        
        [1.1.2.1 BUA DATA API](#bb34c651-e4cd-47ff-a912-3cd0910307e8)
        
        [1.1.2.2 Event](#9ed84e35-538d-4791-b8f8-d10db7c536f4)
        
        [1.1.2.3 Person](#dde688f9-2f52-42ea-9e29-abdf87d0603b)
        
        [1.1.2.4 Project](#320fd4ce-5d95-40f3-9dc6-67845ac68eb4)
        
        [1.1.2.5 Publication](#4588d8fb-0f50-4c50-817f-fbba7f79af32)
        

### <a id="containers"></a>

##### 1\. Groups

### <a id="8be31291-b199-42e0-a35b-1a2f226d5f5b"></a>1.1 Group **BUA API MODEL**

![Hackolade image](BUA%20API%20MODEL%20documentation/image2.png?raw=true)

##### 1.1.1 **BUA API MODEL** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Group name</td><td>BUA API MODEL</td></tr><tr><td>Technical name</td><td>bua_api_model_group</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="8be31291-b199-42e0-a35b-1a2f226d5f5b-children"></a>1.1.2 **BUA API MODEL** Documents

### <a id="bb34c651-e4cd-47ff-a912-3cd0910307e8"></a>1.1.2.1 Document **BUA DATA API**

##### 1.1.2.1.1 **BUA DATA API** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image3.png?raw=true)

##### 1.1.2.1.2 **BUA DATA API** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>BUA DATA API</td></tr><tr><td>Technical name</td><td>bua_data_api</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td>bua_data_api</td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#8be31291-b199-42e0-a35b-1a2f226d5f5b><span class="name-container">BUA API MODEL</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3 **BUA DATA API** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#32c97824-f9e5-4ac4-8069-9a509d2bbe1f class="margin-0">identification</a></td><td class="no-break-word">object</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#296064b1-0783-49ef-9470-47cae151b37b class="margin-5">organizationId</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2ab52e27-6e2c-40bb-8d01-068aef6910de class="margin-5">authorizationToken</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#044bdba4-eecb-4ca8-97c6-4ad2e351fef4 class="margin-0">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b10e334c-5a23-4f2c-a6df-c2c3cf65e0a1 class="margin-0">data</a></td><td class="no-break-word">array</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#59a64152-e783-4251-9e81-82d6f6c7d56a class="margin-5">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#679854a7-cb48-44bb-9d71-8eb6f63bec1d class="margin-10">[0]&nbsp;person</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e78f812e-b209-46b8-84c7-153582e81a95 class="margin-15">[0]&nbsp;person</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5c2f523e-4359-4b1b-b421-ad61f9ac39aa class="margin-10">[1]&nbsp;publication</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#31e0c15d-9dea-4cf9-81d4-711842cdb2d9 class="margin-15">[0]&nbsp;publication</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c8b0778e-83ac-40cb-ae9b-bf017d4379f6 class="margin-10">[2]&nbsp;project</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9f2ea1f0-1a0e-4ecf-afb6-418664784969 class="margin-15">[0]&nbsp;project</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e51e9858-7267-47af-8081-e5639d2d6192 class="margin-10">[3]&nbsp;event</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f757b7f8-4bac-445b-a764-ba9af3593386 class="margin-15">[0]&nbsp;event</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="32c97824-f9e5-4ac4-8069-9a509d2bbe1f"></a>1.1.2.1.3.1 Field **identification**

##### 1.1.2.1.3.1.1 **identification** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image4.png?raw=true)

##### 1.1.2.1.3.1.2 **identification** Hierarchy

Parent field: **BUA DATA API**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#296064b1-0783-49ef-9470-47cae151b37b class="margin-NaN">organizationId</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2ab52e27-6e2c-40bb-8d01-068aef6910de class="margin-NaN">authorizationToken</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.1.3 **identification** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>identification</td></tr><tr><td>Technical name</td><td>identification</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="296064b1-0783-49ef-9470-47cae151b37b"></a>1.1.2.1.3.2 Field **organizationId**

##### 1.1.2.1.3.2.1 **organizationId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image5.png?raw=true)

##### 1.1.2.1.3.2.2 **organizationId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organizationId</td></tr><tr><td>Technical name</td><td>organizationId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="2ab52e27-6e2c-40bb-8d01-068aef6910de"></a>1.1.2.1.3.3 Field **authorizationToken**

##### 1.1.2.1.3.3.1 **authorizationToken** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image6.png?raw=true)

##### 1.1.2.1.3.3.2 **authorizationToken** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>authorizationToken</td></tr><tr><td>Technical name</td><td>authorizationToken</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="044bdba4-eecb-4ca8-97c6-4ad2e351fef4"></a>1.1.2.1.3.4 Field **type**

##### 1.1.2.1.3.4.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image7.png?raw=true)

##### 1.1.2.1.3.4.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>publication,person,event,project</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="b10e334c-5a23-4f2c-a6df-c2c3cf65e0a1"></a>1.1.2.1.3.5 Field **data**

##### 1.1.2.1.3.5.1 **data** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image8.png?raw=true)

##### 1.1.2.1.3.5.2 **data** Hierarchy

Parent field: **BUA DATA API**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#59a64152-e783-4251-9e81-82d6f6c7d56a class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.5.3 **data** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>data</td></tr><tr><td>Technical name</td><td>data</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="59a64152-e783-4251-9e81-82d6f6c7d56a"></a>1.1.2.1.3.6 Field **anyOf**

##### 1.1.2.1.3.6.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image9.png?raw=true)

##### 1.1.2.1.3.6.2 **anyOf** Hierarchy

Parent field: **data**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#679854a7-cb48-44bb-9d71-8eb6f63bec1d class="margin-NaN">[0]&nbsp;person</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5c2f523e-4359-4b1b-b421-ad61f9ac39aa class="margin-NaN">[1]&nbsp;publication</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c8b0778e-83ac-40cb-ae9b-bf017d4379f6 class="margin-NaN">[2]&nbsp;project</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e51e9858-7267-47af-8081-e5639d2d6192 class="margin-NaN">[3]&nbsp;event</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.6.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td></tr></tbody></table>

### <a id="679854a7-cb48-44bb-9d71-8eb6f63bec1d"></a>1.1.2.1.3.7 Field **\[0\] person**

##### 1.1.2.1.3.7.1 **\[0\] person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image10.png?raw=true)

##### 1.1.2.1.3.7.2 **\[0\] person** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e78f812e-b209-46b8-84c7-153582e81a95 class="margin-NaN">[0]&nbsp;person</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.7.3 **\[0\] person** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="e78f812e-b209-46b8-84c7-153582e81a95"></a>1.1.2.1.3.8 Field **\[0\] person**

##### 1.1.2.1.3.8.1 **\[0\] person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image11.png?raw=true)

##### 1.1.2.1.3.8.2 **\[0\] person** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="5c2f523e-4359-4b1b-b421-ad61f9ac39aa"></a>1.1.2.1.3.9 Field **\[1\] publication**

##### 1.1.2.1.3.9.1 **\[1\] publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image12.png?raw=true)

##### 1.1.2.1.3.9.2 **\[1\] publication** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#31e0c15d-9dea-4cf9-81d4-711842cdb2d9 class="margin-NaN">[0]&nbsp;publication</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.9.3 **\[1\] publication** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="31e0c15d-9dea-4cf9-81d4-711842cdb2d9"></a>1.1.2.1.3.10 Field **\[0\] publication**

##### 1.1.2.1.3.10.1 **\[0\] publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image13.png?raw=true)

##### 1.1.2.1.3.10.2 **\[0\] publication** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="c8b0778e-83ac-40cb-ae9b-bf017d4379f6"></a>1.1.2.1.3.11 Field **\[2\] project**

##### 1.1.2.1.3.11.1 **\[2\] project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image14.png?raw=true)

##### 1.1.2.1.3.11.2 **\[2\] project** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9f2ea1f0-1a0e-4ecf-afb6-418664784969 class="margin-NaN">[0]&nbsp;project</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.11.3 **\[2\] project** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="9f2ea1f0-1a0e-4ecf-afb6-418664784969"></a>1.1.2.1.3.12 Field **\[0\] project**

##### 1.1.2.1.3.12.1 **\[0\] project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image15.png?raw=true)

##### 1.1.2.1.3.12.2 **\[0\] project** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="e51e9858-7267-47af-8081-e5639d2d6192"></a>1.1.2.1.3.13 Field **\[3\] event**

##### 1.1.2.1.3.13.1 **\[3\] event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image16.png?raw=true)

##### 1.1.2.1.3.13.2 **\[3\] event** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f757b7f8-4bac-445b-a764-ba9af3593386 class="margin-NaN">[0]&nbsp;event</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.13.3 **\[3\] event** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f757b7f8-4bac-445b-a764-ba9af3593386"></a>1.1.2.1.3.14 Field **\[0\] event**

##### 1.1.2.1.3.14.1 **\[0\] event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image17.png?raw=true)

##### 1.1.2.1.3.14.2 **\[0\] event** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

##### 1.1.2.1.4 **BUA DATA API** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "id": "bua_data_api",
    "type": "object",
    "title": "BUA DATA API",
    "properties": {
        "identification": {
            "type": "object",
            "title": "identification",
            "properties": {
                "organizationId": {
                    "type": "string",
                    "title": "organizationId"
                },
                "authorizationToken": {
                    "type": "string",
                    "title": "authorizationToken"
                }
            },
            "additionalProperties": false,
            "required": [
                "organizationId",
                "authorizationToken"
            ]
        },
        "type": {
            "type": "string",
            "title": "type",
            "enum": [
                "publication",
                "person",
                "event",
                "project"
            ]
        },
        "data": {
            "type": "array",
            "title": "data",
            "additionalItems": true,
            "additionalProperties": true,
            "anyOf": [
                {
                    "type": "array",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": false
                    }
                },
                {
                    "type": "array",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": false
                    }
                },
                {
                    "type": "array",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": false
                    }
                },
                {
                    "type": "array",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": false
                    }
                }
            ]
        }
    },
    "additionalProperties": false,
    "required": [
        "identification",
        "type",
        "data"
    ],
    "dependencies": {
        "data": [
            null
        ]
    }
}
```

##### 1.1.2.1.5 **BUA DATA API** JSON data

```
{
    "identification": {
        "organizationId": "Lorem",
        "authorizationToken": "Lorem"
    },
    "type": "project",
    "data": [
        {}
    ]
}
```

### <a id="9ed84e35-538d-4791-b8f8-d10db7c536f4"></a>1.1.2.2 Document **Event**

##### 1.1.2.2.1 **Event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image18.png?raw=true)

##### 1.1.2.2.2 **Event** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Event</td></tr><tr><td>Technical name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#8be31291-b199-42e0-a35b-1a2f226d5f5b><span class="name-container">BUA API MODEL</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3 **Event** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cc1b2bc0-4e57-421f-a268-4577c109da02 class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#68ceb6c6-40ac-4856-ae7b-589b5c918d56 class="margin-0">description</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#34534396-1120-445b-b539-3f5b9261d22c class="margin-0">date</a></td><td class="no-break-word">date-time</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Example: 2022-01-25T14:50:00</p></div></td></tr><tr><td><a href=#7c4c3e0d-a0b7-439e-8e12-beaf69baa24b class="margin-0">type</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5c7d4f6a-c5bb-4b80-b4c6-1e8a08ce88e6 class="margin-0">contactInfo</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8f66dda3-54d7-4605-8a66-b745407523fe class="margin-5">address</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#62314964-b435-49b3-9358-2ec048279291 class="margin-5">telephone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c13a806c-f9cd-437e-af1e-9e6864d3ef96 class="margin-5">email</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4f6b06e0-39f5-49dc-8942-ff0899c42d30 class="margin-0">partOfEventseries</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e3c38c81-b2ad-43d7-b635-62350d5ee9cf class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#743709d1-9f4f-4a0a-915b-b1ea90e2c7a0 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a38a8850-da2f-4fa3-a4fd-d33ea21aab25 class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6c1656ee-4a6e-476a-b6cf-10c689417208 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0c82316f-fc83-46f6-9294-582bcc75c6a8 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#272bbc69-e3d4-4d93-8fcf-86200bc44908 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#001d78ae-69a0-4f06-aee3-4593e323a646 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2ac3776d-1665-45ae-935d-2358270ae68b class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a8705309-fcb7-4e83-9395-a173522b37fb class="margin-0">relatedDocuments</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f6aa6c28-8b35-4459-a9b5-820a1d18036b class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a886cd43-e84a-4a29-b3af-6c3fa756dccf class="margin-5">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7052301-2949-4afe-8efb-2defa6a21109 class="margin-5">uri</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#91c40858-3d01-48e5-b2ea-e58b43e7b105 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#97097832-8135-463a-b7f4-5ba30136ca38 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2d68d4f6-71eb-4319-8bac-bfa2d4058b7c class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f639324e-15fb-46b3-9ffa-ad8587e10f5d class="margin-15">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#27995422-111d-41c5-b01b-5413f3e3737b class="margin-20">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8ebe2f4f-e46f-4b20-b344-c181da936892 class="margin-15">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b84b1ec2-dde0-4b90-8cb5-df257401eae0 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="cc1b2bc0-4e57-421f-a268-4577c109da02"></a>1.1.2.2.3.1 Field **name**

##### 1.1.2.2.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image19.png?raw=true)

##### 1.1.2.2.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="68ceb6c6-40ac-4856-ae7b-589b5c918d56"></a>1.1.2.2.3.2 Field **description**

##### 1.1.2.2.3.2.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image20.png?raw=true)

##### 1.1.2.2.3.2.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="34534396-1120-445b-b539-3f5b9261d22c"></a>1.1.2.2.3.3 Field **date**

##### 1.1.2.2.3.3.1 **date** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image21.png?raw=true)

##### 1.1.2.2.3.3.2 **date** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>date</td></tr><tr><td>Technical name</td><td>date</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date-time</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Example: 2022-01-25T14:50:00</p></div></td></tr></tbody></table>

### <a id="7c4c3e0d-a0b7-439e-8e12-beaf69baa24b"></a>1.1.2.2.3.4 Field **type**

##### 1.1.2.2.3.4.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image22.png?raw=true)

##### 1.1.2.2.3.4.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Competition, Conference, Course, Exhibit, Hearing, Interview, Meeting, Performance, Presentation, VIVO Talk, Workshop,Other</td></tr></tbody></table>

### <a id="5c7d4f6a-c5bb-4b80-b4c6-1e8a08ce88e6"></a>1.1.2.2.3.5 Field **contactInfo**

##### 1.1.2.2.3.5.1 **contactInfo** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image23.png?raw=true)

##### 1.1.2.2.3.5.2 **contactInfo** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8f66dda3-54d7-4605-8a66-b745407523fe class="margin-NaN">address</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#62314964-b435-49b3-9358-2ec048279291 class="margin-NaN">telephone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c13a806c-f9cd-437e-af1e-9e6864d3ef96 class="margin-NaN">email</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.5.3 **contactInfo** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>contactInfo</td></tr><tr><td>Technical name</td><td>contactInfo</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="8f66dda3-54d7-4605-8a66-b745407523fe"></a>1.1.2.2.3.6 Field **address**

##### 1.1.2.2.3.6.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image24.png?raw=true)

##### 1.1.2.2.3.6.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="62314964-b435-49b3-9358-2ec048279291"></a>1.1.2.2.3.7 Field **telephone**

##### 1.1.2.2.3.7.1 **telephone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image25.png?raw=true)

##### 1.1.2.2.3.7.2 **telephone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>telephone</td></tr><tr><td>Technical name</td><td>telephone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="c13a806c-f9cd-437e-af1e-9e6864d3ef96"></a>1.1.2.2.3.8 Field **email**

##### 1.1.2.2.3.8.1 **email** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image26.png?raw=true)

##### 1.1.2.2.3.8.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td>email</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr></tbody></table>

### <a id="4f6b06e0-39f5-49dc-8942-ff0899c42d30"></a>1.1.2.2.3.9 Field **partOfEventseries**

##### 1.1.2.2.3.9.1 **partOfEventseries** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image27.png?raw=true)

##### 1.1.2.2.3.9.2 **partOfEventseries** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e3c38c81-b2ad-43d7-b635-62350d5ee9cf class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#743709d1-9f4f-4a0a-915b-b1ea90e2c7a0 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.9.3 **partOfEventseries** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>partOfEventseries</td></tr><tr><td>Technical name</td><td>partOfEventseries</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="e3c38c81-b2ad-43d7-b635-62350d5ee9cf"></a>1.1.2.2.3.10 Field **name**

##### 1.1.2.2.3.10.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image28.png?raw=true)

##### 1.1.2.2.3.10.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="743709d1-9f4f-4a0a-915b-b1ea90e2c7a0"></a>1.1.2.2.3.11 Field **ids**

##### 1.1.2.2.3.11.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image29.png?raw=true)

##### 1.1.2.2.3.11.2 **ids** Hierarchy

Parent field: **partOfEventseries**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a38a8850-da2f-4fa3-a4fd-d33ea21aab25 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.11.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="a38a8850-da2f-4fa3-a4fd-d33ea21aab25"></a>1.1.2.2.3.12 Field **\[0\]**

##### 1.1.2.2.3.12.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image30.png?raw=true)

##### 1.1.2.2.3.12.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6c1656ee-4a6e-476a-b6cf-10c689417208 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.12.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="6c1656ee-4a6e-476a-b6cf-10c689417208"></a>1.1.2.2.3.13 Field **anyOf**

##### 1.1.2.2.3.13.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image31.png?raw=true)

##### 1.1.2.2.3.13.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0c82316f-fc83-46f6-9294-582bcc75c6a8 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#001d78ae-69a0-4f06-aee3-4593e323a646 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.13.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="0c82316f-fc83-46f6-9294-582bcc75c6a8"></a>1.1.2.2.3.14 Field **\[0\] houseId**

##### 1.1.2.2.3.14.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image32.png?raw=true)

##### 1.1.2.2.3.14.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#272bbc69-e3d4-4d93-8fcf-86200bc44908 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.14.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="272bbc69-e3d4-4d93-8fcf-86200bc44908"></a>1.1.2.2.3.15 Field **houseId**

##### 1.1.2.2.3.15.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image33.png?raw=true)

##### 1.1.2.2.3.15.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="001d78ae-69a0-4f06-aee3-4593e323a646"></a>1.1.2.2.3.16 Field **\[1\] anyOtherID**

##### 1.1.2.2.3.16.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image34.png?raw=true)

##### 1.1.2.2.3.16.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2ac3776d-1665-45ae-935d-2358270ae68b class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.16.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="2ac3776d-1665-45ae-935d-2358270ae68b"></a>1.1.2.2.3.17 Field **anyOtherID**

##### 1.1.2.2.3.17.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image35.png?raw=true)

##### 1.1.2.2.3.17.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a8705309-fcb7-4e83-9395-a173522b37fb"></a>1.1.2.2.3.18 Field **relatedDocuments**

##### 1.1.2.2.3.18.1 **relatedDocuments** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image36.png?raw=true)

##### 1.1.2.2.3.18.2 **relatedDocuments** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f6aa6c28-8b35-4459-a9b5-820a1d18036b class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a886cd43-e84a-4a29-b3af-6c3fa756dccf class="margin-NaN">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7052301-2949-4afe-8efb-2defa6a21109 class="margin-NaN">uri</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.18.3 **relatedDocuments** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>relatedDocuments</td></tr><tr><td>Technical name</td><td>relatedDocuments</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="f6aa6c28-8b35-4459-a9b5-820a1d18036b"></a>1.1.2.2.3.19 Field **name**

##### 1.1.2.2.3.19.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image37.png?raw=true)

##### 1.1.2.2.3.19.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="a886cd43-e84a-4a29-b3af-6c3fa756dccf"></a>1.1.2.2.3.20 Field **abstract**

##### 1.1.2.2.3.20.1 **abstract** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image38.png?raw=true)

##### 1.1.2.2.3.20.2 **abstract** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>abstract</td></tr><tr><td>Technical name</td><td>abstract</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a7052301-2949-4afe-8efb-2defa6a21109"></a>1.1.2.2.3.21 Field **uri**

##### 1.1.2.2.3.21.1 **uri** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image39.png?raw=true)

##### 1.1.2.2.3.21.2 **uri** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uri</td></tr><tr><td>Technical name</td><td>uri</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="91c40858-3d01-48e5-b2ea-e58b43e7b105"></a>1.1.2.2.3.22 Field **ids**

##### 1.1.2.2.3.22.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image40.png?raw=true)

##### 1.1.2.2.3.22.2 **ids** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#97097832-8135-463a-b7f4-5ba30136ca38 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.22.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="97097832-8135-463a-b7f4-5ba30136ca38"></a>1.1.2.2.3.23 Field **\[0\]**

##### 1.1.2.2.3.23.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image41.png?raw=true)

##### 1.1.2.2.3.23.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2d68d4f6-71eb-4319-8bac-bfa2d4058b7c class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.23.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="2d68d4f6-71eb-4319-8bac-bfa2d4058b7c"></a>1.1.2.2.3.24 Field **anyOf**

##### 1.1.2.2.3.24.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image42.png?raw=true)

##### 1.1.2.2.3.24.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f639324e-15fb-46b3-9ffa-ad8587e10f5d class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8ebe2f4f-e46f-4b20-b344-c181da936892 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.24.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="f639324e-15fb-46b3-9ffa-ad8587e10f5d"></a>1.1.2.2.3.25 Field **\[0\] houseId**

##### 1.1.2.2.3.25.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image43.png?raw=true)

##### 1.1.2.2.3.25.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#27995422-111d-41c5-b01b-5413f3e3737b class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.25.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="27995422-111d-41c5-b01b-5413f3e3737b"></a>1.1.2.2.3.26 Field **houseId**

##### 1.1.2.2.3.26.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image44.png?raw=true)

##### 1.1.2.2.3.26.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="8ebe2f4f-e46f-4b20-b344-c181da936892"></a>1.1.2.2.3.27 Field **\[1\] anyOtherID**

##### 1.1.2.2.3.27.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image45.png?raw=true)

##### 1.1.2.2.3.27.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b84b1ec2-dde0-4b90-8cb5-df257401eae0 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.2.3.27.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="b84b1ec2-dde0-4b90-8cb5-df257401eae0"></a>1.1.2.2.3.28 Field **anyOtherID**

##### 1.1.2.2.3.28.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image46.png?raw=true)

##### 1.1.2.2.3.28.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 1.1.2.2.4 **Event** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "Event",
    "properties": {
        "name": {
            "type": "string",
            "title": "name"
        },
        "description": {
            "type": "string",
            "title": "description"
        },
        "date": {
            "type": "string",
            "title": "date",
            "format": "date-time"
        },
        "type": {
            "type": "string",
            "title": "type",
            "enum": [
                "Competition",
                " Conference",
                " Course",
                " Exhibit",
                " Hearing",
                " Interview",
                " Meeting",
                " Performance",
                " Presentation",
                " VIVO Talk",
                " Workshop",
                "Other"
            ]
        },
        "contactInfo": {
            "type": "object",
            "title": "contactInfo",
            "properties": {
                "address": {
                    "type": "string",
                    "title": "address"
                },
                "telephone": {
                    "type": "string",
                    "title": "telephone"
                },
                "email": {
                    "type": "string",
                    "title": "email",
                    "format": "email"
                }
            },
            "additionalProperties": false,
            "required": [
                "address"
            ]
        },
        "partOfEventseries": {
            "type": "object",
            "title": "partOfEventseries",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "ids": {
                    "type": "array",
                    "title": "ids",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": true,
                        "anyOf": [
                            {
                                "type": "object",
                                "properties": {
                                    "houseId": {
                                        "type": "string",
                                        "title": "houseId"
                                    }
                                },
                                "additionalProperties": true
                            },
                            {
                                "type": "object",
                                "properties": {
                                    "anyOtherID": {
                                        "type": "string",
                                        "title": "anyOtherID"
                                    }
                                }
                            }
                        ]
                    }
                }
            },
            "additionalProperties": false,
            "required": [
                "name"
            ]
        },
        "relatedDocuments": {
            "type": "object",
            "title": "relatedDocuments",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "abstract": {
                    "type": "string",
                    "title": "abstract"
                },
                "uri": {
                    "type": "string",
                    "title": "uri",
                    "format": "uri"
                }
            },
            "additionalProperties": false,
            "required": [
                "name",
                "uri"
            ]
        },
        "ids": {
            "type": "array",
            "title": "ids",
            "additionalItems": true,
            "items": {
                "type": "object",
                "additionalProperties": true,
                "anyOf": [
                    {
                        "type": "object",
                        "properties": {
                            "houseId": {
                                "type": "string",
                                "title": "houseId"
                            }
                        },
                        "additionalProperties": true
                    },
                    {
                        "type": "object",
                        "properties": {
                            "anyOtherID": {
                                "type": "string",
                                "title": "anyOtherID"
                            }
                        }
                    }
                ]
            }
        }
    },
    "additionalProperties": false,
    "required": [
        "name",
        "description",
        "date"
    ]
}
```

##### 1.1.2.2.5 **Event** JSON data

```
{
    "name": "Lorem",
    "description": "Lorem",
    "date": "2011-06-14T04:12:36.123Z",
    "type": "Other",
    "contactInfo": {
        "address": "Lorem",
        "telephone": "Lorem",
        "email": "sample@email.com"
    },
    "partOfEventseries": {
        "name": "Lorem",
        "ids": [
            {
                "houseId": "Lorem"
            }
        ]
    },
    "relatedDocuments": {
        "name": "Lorem",
        "abstract": "Lorem",
        "uri": "./resource.txt#frag01"
    },
    "ids": [
        {
            "houseId": "Lorem"
        }
    ]
}
```

### <a id="dde688f9-2f52-42ea-9e29-abdf87d0603b"></a>1.1.2.3 Document **Person**

##### 1.1.2.3.1 **Person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image47.png?raw=true)

##### 1.1.2.3.2 **Person** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Person</td></tr><tr><td>Technical name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td>bua_person</td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#8be31291-b199-42e0-a35b-1a2f226d5f5b><span class="name-container">BUA API MODEL</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3 **Person** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#947b161f-0357-4770-9198-88c917d104f5 class="margin-0">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b9b1baec-bd51-4a9f-b10a-c89a69d78d63 class="margin-0">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1c2e6a22-9816-4acc-8803-7c13ada73085 class="margin-0">middleName</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#30fc23f7-23c0-47e0-9c8a-512153f90d03 class="margin-0">description</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1b1cc630-cfc8-467c-84a6-fd463ef657c9 class="margin-0">birthday</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#11ec1f21-ae8a-4c1d-87e0-1e06dae30226 class="margin-0">gender</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#f3849a16-1ea2-4bbd-b5cb-90a10098839a class="margin-0">nationality</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#3c582c1c-7f6c-4090-a48f-8456a32ad989 class="margin-0">address</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#94a0d95e-47fd-4258-ab0f-72b9b7e5ed37 class="margin-0">email</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#526f247c-1c61-4d3d-bc43-0942f3b3c139 class="margin-0">phone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#df35ddd8-5363-4c32-9eeb-3af2946f58a4 class="margin-0">webpages</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#da8fe571-d11f-43e3-9cac-e952f773e730 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#482c55d5-9cd8-409f-8c15-e938410b5ae4 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1d43804b-32d3-4356-b087-12af305aba5e class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#40708ae6-1747-492d-84ff-e4fa91f66588 class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5f138fa-f575-4bdd-a8bc-2b7f6348574d class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#94c563f9-a081-4a5e-a1b9-dc96e6b6c139 class="margin-0">doctoralEligibility</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#25e9d2af-8ecd-42d9-b7ce-7c9e3d64409c class="margin-0">doctoralEligibilityFrom</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#10cb30a9-e448-448b-bb78-085c5b18ac63 class="margin-0">isPhD</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#34fb2f24-2db5-479c-a216-34ed4e751721 class="margin-0">primarySupervisor</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#ca1dfada-5e89-4faa-a4ee-eec8979fd3ad class="margin-0">doctoralCooperationPartner</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#6062af18-e810-4feb-9bf9-0d331c7234ce class="margin-0">qualificationProcess</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#ce6d70d1-daa4-4c20-859e-90bdd9dcb917 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#46c2db99-f8cc-4049-8ee7-1f9e2cefc4aa class="margin-10">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2efddf88-3224-4fcd-931a-4400691a4ff0 class="margin-10">completionDate</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#4ae4a0e3-c50b-49c5-bf06-6547943ecad1 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#dee0ef18-9aa8-4a91-9dd6-a66152f7a4f3 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f8394cbf-1efc-49e0-a608-e927602e8ff9 class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#975bdabb-c922-48c9-8fcd-801813ee248d class="margin-15">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f819bf29-282d-4549-9769-411dd6a52fdc class="margin-20">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b960e65c-4ab7-4eb6-b910-b7c1303883f7 class="margin-15">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ce6b2e5c-5117-4261-b88b-565daef43ff2 class="margin-20">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#56ff81cb-821a-4f96-990b-1472be7a0aca class="margin-15">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7d13b490-fece-411f-b500-a4458e4693e2 class="margin-20">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ea11d063-89c8-4bbc-a541-ef963d4315a6 class="margin-0">positions</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1a7ac9df-0929-45bf-a87d-e591eba1b441 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9893f10d-a4d2-4245-b12a-ab5b8ac80644 class="margin-10">positionName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b86c2e12-2165-461a-bb18-d97fee2bb40d class="margin-10">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#857f9e55-f10e-492b-a8b8-38fa4092115a class="margin-10">organisationalUnitID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a210ec21-fb2e-43a5-9027-d5636319953b class="margin-10">staffCategory</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#30b84108-670a-471f-ac6c-05acb9dc3ad1 class="margin-10">timeLimit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2a3191ed-e16b-421d-a411-e10eaadf56bd class="margin-10">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#eab93dbf-1f80-4261-b5c9-96b7da1e088b class="margin-15">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e41e2cde-aa8b-4bf1-bef7-5ceb06e908ac class="margin-10">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#fdfcc83f-160a-47e8-9ce9-be631e4f2d33 class="margin-15">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a1826fac-472a-4612-b17c-03373adb53a8 class="margin-0">roles</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e0cfec5b-54ed-48b4-ba0b-d65bfbbc019d class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#37a7c0cc-5160-4aab-ba91-e0c054ba7e31 class="margin-10">roleName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3b4edc3b-3c61-4cf3-9e68-4f3ad543621a class="margin-10">unit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f8012e93-ecf4-4d75-8f17-7337beb92777 class="margin-10">unitIds</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#04a31dfa-8c08-44c5-a673-da3f59c73b4b class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#27897214-75b2-4f98-b725-0fa1445796bc class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#180d35c3-6fd3-44a5-a0f3-d827a8bce84f class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#42080381-f324-4515-8528-62d7b37135ce class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a522f554-c1dc-40c3-a4e4-cbcc9de85c0d class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1a3808de-08dd-440d-912d-64ec2ec1970c class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f11eecd4-65f9-479c-bf1e-dea9b951f34c class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3fe79101-538f-4198-aff3-03897061763f class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="947b161f-0357-4770-9198-88c917d104f5"></a>1.1.2.3.3.1 Field **firstName**

##### 1.1.2.3.3.1.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image48.png?raw=true)

##### 1.1.2.3.3.1.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="b9b1baec-bd51-4a9f-b10a-c89a69d78d63"></a>1.1.2.3.3.2 Field **lastName**

##### 1.1.2.3.3.2.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image49.png?raw=true)

##### 1.1.2.3.3.2.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1c2e6a22-9816-4acc-8803-7c13ada73085"></a>1.1.2.3.3.3 Field **middleName**

##### 1.1.2.3.3.3.1 **middleName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image50.png?raw=true)

##### 1.1.2.3.3.3.2 **middleName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>middleName</td></tr><tr><td>Technical name</td><td>middleName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="30fc23f7-23c0-47e0-9c8a-512153f90d03"></a>1.1.2.3.3.4 Field **description**

##### 1.1.2.3.3.4.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image51.png?raw=true)

##### 1.1.2.3.3.4.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="1b1cc630-cfc8-467c-84a6-fd463ef657c9"></a>1.1.2.3.3.5 Field **birthday**

##### 1.1.2.3.3.5.1 **birthday** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image52.png?raw=true)

##### 1.1.2.3.3.5.2 **birthday** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>birthday</td></tr><tr><td>Technical name</td><td>birthday</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="11ec1f21-ae8a-4c1d-87e0-1e06dae30226"></a>1.1.2.3.3.6 Field **gender**

##### 1.1.2.3.3.6.1 **gender** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image53.png?raw=true)

##### 1.1.2.3.3.6.2 **gender** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>gender</td></tr><tr><td>Technical name</td><td>gender</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="f3849a16-1ea2-4bbd-b5cb-90a10098839a"></a>1.1.2.3.3.7 Field **nationality**

##### 1.1.2.3.3.7.1 **nationality** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image54.png?raw=true)

##### 1.1.2.3.3.7.2 **nationality** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>nationality</td></tr><tr><td>Technical name</td><td>nationality</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="3c582c1c-7f6c-4090-a48f-8456a32ad989"></a>1.1.2.3.3.8 Field **address**

##### 1.1.2.3.3.8.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image55.png?raw=true)

##### 1.1.2.3.3.8.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="94a0d95e-47fd-4258-ab0f-72b9b7e5ed37"></a>1.1.2.3.3.9 Field **email**

##### 1.1.2.3.3.9.1 **email** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image56.png?raw=true)

##### 1.1.2.3.3.9.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td>email</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr><tr><td>Pattern</td><td>/^([\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+\.)*[\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+@((((([a-z0-9]{1}[a-z0-9\-]{0,62}[a-z0-9]{1})|[a-z])\.)+[a-z]{2,6})|(\d{1,3}\.){3}\d{1,3}(\:\d{1,5})?)$/i</td></tr></tbody></table>

### <a id="526f247c-1c61-4d3d-bc43-0942f3b3c139"></a>1.1.2.3.3.10 Field **phone**

##### 1.1.2.3.3.10.1 **phone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image57.png?raw=true)

##### 1.1.2.3.3.10.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td>phone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Pattern</td><td>^\+(?:[0-9] ?){6,25}[0-9]$</td></tr></tbody></table>

### <a id="df35ddd8-5363-4c32-9eeb-3af2946f58a4"></a>1.1.2.3.3.11 Field **webpages**

##### 1.1.2.3.3.11.1 **webpages** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image58.png?raw=true)

##### 1.1.2.3.3.11.2 **webpages** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#da8fe571-d11f-43e3-9cac-e952f773e730 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.11.3 **webpages** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>webpages</td></tr><tr><td>Technical name</td><td>webpages</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="da8fe571-d11f-43e3-9cac-e952f773e730"></a>1.1.2.3.3.12 Field **\[0\]**

##### 1.1.2.3.3.12.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image59.png?raw=true)

##### 1.1.2.3.3.12.2 **\[0\]** Hierarchy

Parent field: **webpages**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#482c55d5-9cd8-409f-8c15-e938410b5ae4 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1d43804b-32d3-4356-b087-12af305aba5e class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.12.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="482c55d5-9cd8-409f-8c15-e938410b5ae4"></a>1.1.2.3.3.13 Field **name**

##### 1.1.2.3.3.13.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image60.png?raw=true)

##### 1.1.2.3.3.13.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="1d43804b-32d3-4356-b087-12af305aba5e"></a>1.1.2.3.3.14 Field **url**

##### 1.1.2.3.3.14.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image61.png?raw=true)

##### 1.1.2.3.3.14.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="40708ae6-1747-492d-84ff-e4fa91f66588"></a>1.1.2.3.3.15 Field **disciplinaryResearchAreas**

##### 1.1.2.3.3.15.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image62.png?raw=true)

##### 1.1.2.3.3.15.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c5f138fa-f575-4bdd-a8bc-2b7f6348574d class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.15.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="c5f138fa-f575-4bdd-a8bc-2b7f6348574d"></a>1.1.2.3.3.16 Field **\[0\]**

##### 1.1.2.3.3.16.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image63.png?raw=true)

##### 1.1.2.3.3.16.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="94c563f9-a081-4a5e-a1b9-dc96e6b6c139"></a>1.1.2.3.3.17 Field **doctoralEligibility**

##### 1.1.2.3.3.17.1 **doctoralEligibility** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image64.png?raw=true)

##### 1.1.2.3.3.17.2 **doctoralEligibility** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralEligibility</td></tr><tr><td>Technical name</td><td>doctoralEligibility</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="25e9d2af-8ecd-42d9-b7ce-7c9e3d64409c"></a>1.1.2.3.3.18 Field **doctoralEligibilityFrom**

##### 1.1.2.3.3.18.1 **doctoralEligibilityFrom** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image65.png?raw=true)

##### 1.1.2.3.3.18.2 **doctoralEligibilityFrom** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralEligibilityFrom</td></tr><tr><td>Technical name</td><td>doctoralEligibilityFrom</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Default</td><td>domes</td></tr><tr><td>Enum</td><td>domestic,foreign</td></tr></tbody></table>

### <a id="10cb30a9-e448-448b-bb78-085c5b18ac63"></a>1.1.2.3.3.19 Field **isPhD**

##### 1.1.2.3.3.19.1 **isPhD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image66.png?raw=true)

##### 1.1.2.3.3.19.2 **isPhD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>isPhD</td></tr><tr><td>Technical name</td><td>isPhD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="34fb2f24-2db5-479c-a216-34ed4e751721"></a>1.1.2.3.3.20 Field **primarySupervisor**

##### 1.1.2.3.3.20.1 **primarySupervisor** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image67.png?raw=true)

##### 1.1.2.3.3.20.2 **primarySupervisor** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>primarySupervisor</td></tr><tr><td>Technical name</td><td>primarySupervisor</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="ca1dfada-5e89-4faa-a4ee-eec8979fd3ad"></a>1.1.2.3.3.21 Field **doctoralCooperationPartner**

##### 1.1.2.3.3.21.1 **doctoralCooperationPartner** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image68.png?raw=true)

##### 1.1.2.3.3.21.2 **doctoralCooperationPartner** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralCooperationPartner</td></tr><tr><td>Technical name</td><td>doctoralCooperationPartner</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="6062af18-e810-4feb-9bf9-0d331c7234ce"></a>1.1.2.3.3.22 Field **qualificationProcess**

##### 1.1.2.3.3.22.1 **qualificationProcess** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image69.png?raw=true)

##### 1.1.2.3.3.22.2 **qualificationProcess** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ce6d70d1-daa4-4c20-859e-90bdd9dcb917 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.22.3 **qualificationProcess** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>qualificationProcess</td></tr><tr><td>Technical name</td><td>qualificationProcess</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="ce6d70d1-daa4-4c20-859e-90bdd9dcb917"></a>1.1.2.3.3.23 Field **\[0\]**

##### 1.1.2.3.3.23.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image70.png?raw=true)

##### 1.1.2.3.3.23.2 **\[0\]** Hierarchy

Parent field: **qualificationProcess**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#46c2db99-f8cc-4049-8ee7-1f9e2cefc4aa class="margin-NaN">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2efddf88-3224-4fcd-931a-4400691a4ff0 class="margin-NaN">completionDate</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

##### 1.1.2.3.3.23.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="46c2db99-f8cc-4049-8ee7-1f9e2cefc4aa"></a>1.1.2.3.3.24 Field **type**

##### 1.1.2.3.3.24.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image71.png?raw=true)

##### 1.1.2.3.3.24.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>habilitation,doctoral thesis</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="2efddf88-3224-4fcd-931a-4400691a4ff0"></a>1.1.2.3.3.25 Field **completionDate**

##### 1.1.2.3.3.25.1 **completionDate** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image72.png?raw=true)

##### 1.1.2.3.3.25.2 **completionDate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>completionDate</td></tr><tr><td>Technical name</td><td>completionDate</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="4ae4a0e3-c50b-49c5-bf06-6547943ecad1"></a>1.1.2.3.3.26 Field **ids**

##### 1.1.2.3.3.26.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image73.png?raw=true)

##### 1.1.2.3.3.26.2 **ids** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#dee0ef18-9aa8-4a91-9dd6-a66152f7a4f3 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.26.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="dee0ef18-9aa8-4a91-9dd6-a66152f7a4f3"></a>1.1.2.3.3.27 Field **\[0\]**

##### 1.1.2.3.3.27.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image74.png?raw=true)

##### 1.1.2.3.3.27.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f8394cbf-1efc-49e0-a608-e927602e8ff9 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.27.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="f8394cbf-1efc-49e0-a608-e927602e8ff9"></a>1.1.2.3.3.28 Field **anyOf**

##### 1.1.2.3.3.28.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image75.png?raw=true)

##### 1.1.2.3.3.28.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#975bdabb-c922-48c9-8fcd-801813ee248d class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b960e65c-4ab7-4eb6-b910-b7c1303883f7 class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#56ff81cb-821a-4f96-990b-1472be7a0aca class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.28.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="975bdabb-c922-48c9-8fcd-801813ee248d"></a>1.1.2.3.3.29 Field **\[0\] houseID**

##### 1.1.2.3.3.29.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image76.png?raw=true)

##### 1.1.2.3.3.29.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f819bf29-282d-4549-9769-411dd6a52fdc class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.29.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="f819bf29-282d-4549-9769-411dd6a52fdc"></a>1.1.2.3.3.30 Field **houseID**

##### 1.1.2.3.3.30.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image77.png?raw=true)

##### 1.1.2.3.3.30.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="b960e65c-4ab7-4eb6-b910-b7c1303883f7"></a>1.1.2.3.3.31 Field **\[1\] ORCiD**

##### 1.1.2.3.3.31.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image78.png?raw=true)

##### 1.1.2.3.3.31.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ce6b2e5c-5117-4261-b88b-565daef43ff2 class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.31.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="ce6b2e5c-5117-4261-b88b-565daef43ff2"></a>1.1.2.3.3.32 Field **ORCiD**

##### 1.1.2.3.3.32.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image79.png?raw=true)

##### 1.1.2.3.3.32.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="56ff81cb-821a-4f96-990b-1472be7a0aca"></a>1.1.2.3.3.33 Field **\[2\] anyOtherID**

##### 1.1.2.3.3.33.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image80.png?raw=true)

##### 1.1.2.3.3.33.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7d13b490-fece-411f-b500-a4458e4693e2 class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.33.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="7d13b490-fece-411f-b500-a4458e4693e2"></a>1.1.2.3.3.34 Field **id**

##### 1.1.2.3.3.34.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image81.png?raw=true)

##### 1.1.2.3.3.34.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="ea11d063-89c8-4bbc-a541-ef963d4315a6"></a>1.1.2.3.3.35 Field **positions**

##### 1.1.2.3.3.35.1 **positions** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image82.png?raw=true)

##### 1.1.2.3.3.35.2 **positions** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1a7ac9df-0929-45bf-a87d-e591eba1b441 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.35.3 **positions** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>positions</td></tr><tr><td>Technical name</td><td>positions</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1a7ac9df-0929-45bf-a87d-e591eba1b441"></a>1.1.2.3.3.36 Field **\[0\]**

##### 1.1.2.3.3.36.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image83.png?raw=true)

##### 1.1.2.3.3.36.2 **\[0\]** Hierarchy

Parent field: **positions**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9893f10d-a4d2-4245-b12a-ab5b8ac80644 class="margin-NaN">positionName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b86c2e12-2165-461a-bb18-d97fee2bb40d class="margin-NaN">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#857f9e55-f10e-492b-a8b8-38fa4092115a class="margin-NaN">organisationalUnitID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a210ec21-fb2e-43a5-9027-d5636319953b class="margin-NaN">staffCategory</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#30b84108-670a-471f-ac6c-05acb9dc3ad1 class="margin-NaN">timeLimit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2a3191ed-e16b-421d-a411-e10eaadf56bd class="margin-NaN">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#e41e2cde-aa8b-4bf1-bef7-5ceb06e908ac class="margin-NaN">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

##### 1.1.2.3.3.36.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="9893f10d-a4d2-4245-b12a-ab5b8ac80644"></a>1.1.2.3.3.37 Field **positionName**

##### 1.1.2.3.3.37.1 **positionName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image84.png?raw=true)

##### 1.1.2.3.3.37.2 **positionName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>positionName</td></tr><tr><td>Technical name</td><td>positionName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="b86c2e12-2165-461a-bb18-d97fee2bb40d"></a>1.1.2.3.3.38 Field **organisationalUnit**

##### 1.1.2.3.3.38.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image85.png?raw=true)

##### 1.1.2.3.3.38.2 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="857f9e55-f10e-492b-a8b8-38fa4092115a"></a>1.1.2.3.3.39 Field **organisationalUnitID**

##### 1.1.2.3.3.39.1 **organisationalUnitID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image86.png?raw=true)

##### 1.1.2.3.3.39.2 **organisationalUnitID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnitID</td></tr><tr><td>Technical name</td><td>organisationalUnitID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a210ec21-fb2e-43a5-9027-d5636319953b"></a>1.1.2.3.3.40 Field **staffCategory**

##### 1.1.2.3.3.40.1 **staffCategory** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image87.png?raw=true)

##### 1.1.2.3.3.40.2 **staffCategory** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>staffCategory</td></tr><tr><td>Technical name</td><td>staffCategory</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="30b84108-670a-471f-ac6c-05acb9dc3ad1"></a>1.1.2.3.3.41 Field **timeLimit**

##### 1.1.2.3.3.41.1 **timeLimit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image88.png?raw=true)

##### 1.1.2.3.3.41.2 **timeLimit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>timeLimit</td></tr><tr><td>Technical name</td><td>timeLimit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>befristet,unbefristet</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="2a3191ed-e16b-421d-a411-e10eaadf56bd"></a>1.1.2.3.3.42 Field **subjects**

##### 1.1.2.3.3.42.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image89.png?raw=true)

##### 1.1.2.3.3.42.2 **subjects** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#eab93dbf-1f80-4261-b5c9-96b7da1e088b class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.42.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="eab93dbf-1f80-4261-b5c9-96b7da1e088b"></a>1.1.2.3.3.43 Field **\[0\]**

##### 1.1.2.3.3.43.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image90.png?raw=true)

##### 1.1.2.3.3.43.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e41e2cde-aa8b-4bf1-bef7-5ceb06e908ac"></a>1.1.2.3.3.44 Field **disciplinaryResearchAreas**

##### 1.1.2.3.3.44.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image91.png?raw=true)

##### 1.1.2.3.3.44.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#fdfcc83f-160a-47e8-9ce9-be631e4f2d33 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.44.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="fdfcc83f-160a-47e8-9ce9-be631e4f2d33"></a>1.1.2.3.3.45 Field **\[0\]**

##### 1.1.2.3.3.45.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image92.png?raw=true)

##### 1.1.2.3.3.45.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a1826fac-472a-4612-b17c-03373adb53a8"></a>1.1.2.3.3.46 Field **roles**

##### 1.1.2.3.3.46.1 **roles** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image93.png?raw=true)

##### 1.1.2.3.3.46.2 **roles** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e0cfec5b-54ed-48b4-ba0b-d65bfbbc019d class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.46.3 **roles** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>roles</td></tr><tr><td>Technical name</td><td>roles</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="e0cfec5b-54ed-48b4-ba0b-d65bfbbc019d"></a>1.1.2.3.3.47 Field **\[0\]**

##### 1.1.2.3.3.47.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image94.png?raw=true)

##### 1.1.2.3.3.47.2 **\[0\]** Hierarchy

Parent field: **roles**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#37a7c0cc-5160-4aab-ba91-e0c054ba7e31 class="margin-NaN">roleName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3b4edc3b-3c61-4cf3-9e68-4f3ad543621a class="margin-NaN">unit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f8012e93-ecf4-4d75-8f17-7337beb92777 class="margin-NaN">unitIds</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.47.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="37a7c0cc-5160-4aab-ba91-e0c054ba7e31"></a>1.1.2.3.3.48 Field **roleName**

##### 1.1.2.3.3.48.1 **roleName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image95.png?raw=true)

##### 1.1.2.3.3.48.2 **roleName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>roleName</td></tr><tr><td>Technical name</td><td>roleName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="3b4edc3b-3c61-4cf3-9e68-4f3ad543621a"></a>1.1.2.3.3.49 Field **unit**

##### 1.1.2.3.3.49.1 **unit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image96.png?raw=true)

##### 1.1.2.3.3.49.2 **unit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>unit</td></tr><tr><td>Technical name</td><td>unit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>projects,clusters,etc.</td></tr></tbody></table>

### <a id="f8012e93-ecf4-4d75-8f17-7337beb92777"></a>1.1.2.3.3.50 Field **unitIds**

##### 1.1.2.3.3.50.1 **unitIds** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image97.png?raw=true)

##### 1.1.2.3.3.50.2 **unitIds** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#04a31dfa-8c08-44c5-a673-da3f59c73b4b class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.50.3 **unitIds** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>unitIds</td></tr><tr><td>Technical name</td><td>unitIds</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="04a31dfa-8c08-44c5-a673-da3f59c73b4b"></a>1.1.2.3.3.51 Field **\[0\]**

##### 1.1.2.3.3.51.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image98.png?raw=true)

##### 1.1.2.3.3.51.2 **\[0\]** Hierarchy

Parent field: **unitIds**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#27897214-75b2-4f98-b725-0fa1445796bc class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.51.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="27897214-75b2-4f98-b725-0fa1445796bc"></a>1.1.2.3.3.52 Field **anyOf**

##### 1.1.2.3.3.52.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image99.png?raw=true)

##### 1.1.2.3.3.52.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#180d35c3-6fd3-44a5-a0f3-d827a8bce84f class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a522f554-c1dc-40c3-a4e4-cbcc9de85c0d class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.52.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="180d35c3-6fd3-44a5-a0f3-d827a8bce84f"></a>1.1.2.3.3.53 Field **\[0\] houseId**

##### 1.1.2.3.3.53.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image100.png?raw=true)

##### 1.1.2.3.3.53.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#42080381-f324-4515-8528-62d7b37135ce class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.53.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="42080381-f324-4515-8528-62d7b37135ce"></a>1.1.2.3.3.54 Field **houseId**

##### 1.1.2.3.3.54.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image101.png?raw=true)

##### 1.1.2.3.3.54.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a522f554-c1dc-40c3-a4e4-cbcc9de85c0d"></a>1.1.2.3.3.55 Field **\[1\] anyOtherID**

##### 1.1.2.3.3.55.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image102.png?raw=true)

##### 1.1.2.3.3.55.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1a3808de-08dd-440d-912d-64ec2ec1970c class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.55.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="1a3808de-08dd-440d-912d-64ec2ec1970c"></a>1.1.2.3.3.56 Field **anyOtherID**

##### 1.1.2.3.3.56.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image103.png?raw=true)

##### 1.1.2.3.3.56.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="f11eecd4-65f9-479c-bf1e-dea9b951f34c"></a>1.1.2.3.3.57 Field **interDisciplinaryResearchAreas**

##### 1.1.2.3.3.57.1 **interDisciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image104.png?raw=true)

##### 1.1.2.3.3.57.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3fe79101-538f-4198-aff3-03897061763f class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.3.3.57.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="3fe79101-538f-4198-aff3-03897061763f"></a>1.1.2.3.3.58 Field **\[0\]**

##### 1.1.2.3.3.58.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image105.png?raw=true)

##### 1.1.2.3.3.58.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 1.1.2.3.4 **Person** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "id": "bua_person",
    "type": "object",
    "title": "Person",
    "properties": {
        "firstName": {
            "type": "string",
            "title": "firstName"
        },
        "lastName": {
            "type": "string",
            "title": "lastName"
        },
        "middleName": {
            "type": "string",
            "title": "middleName"
        },
        "description": {
            "type": "string",
            "title": "description"
        },
        "birthday": {
            "type": "string",
            "title": "birthday",
            "format": "date"
        },
        "gender": {
            "type": "string",
            "title": "gender"
        },
        "nationality": {
            "type": "string",
            "title": "nationality"
        },
        "address": {
            "type": "string",
            "title": "address"
        },
        "email": {
            "type": "string",
            "title": "email",
            "format": "email",
            "pattern": "/^([\\w\\!\\#$\\%\\&\\'\\*\\+\\-\\/\\=\\?\\^\\`{\\|\\}\\~]+\\.)*[\\w\\!\\#$\\%\\&\\'\\*\\+\\-\\/\\=\\?\\^\\`{\\|\\}\\~]+@((((([a-z0-9]{1}[a-z0-9\\-]{0,62}[a-z0-9]{1})|[a-z])\\.)+[a-z]{2,6})|(\\d{1,3}\\.){3}\\d{1,3}(\\:\\d{1,5})?)$/i"
        },
        "phone": {
            "type": "string",
            "title": "phone",
            "pattern": "^\\+(?:[0-9] ?){6,25}[0-9]$"
        },
        "webpages": {
            "type": "array",
            "title": "webpages",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "url": {
                        "type": "string",
                        "title": "url",
                        "format": "uri"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name",
                    "url"
                ]
            }
        },
        "disciplinaryResearchAreas": {
            "type": "array",
            "title": "disciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "doctoralEligibility": {
            "type": "boolean",
            "title": "doctoralEligibility"
        },
        "doctoralEligibilityFrom": {
            "type": "string",
            "title": "doctoralEligibilityFrom",
            "default": "domes",
            "enum": [
                "domestic",
                "foreign"
            ]
        },
        "isPhD": {
            "type": "boolean",
            "title": "isPhD"
        },
        "primarySupervisor": {
            "type": "string",
            "title": "primarySupervisor"
        },
        "doctoralCooperationPartner": {
            "type": "string",
            "title": "doctoralCooperationPartner"
        },
        "qualificationProcess": {
            "type": "array",
            "title": "qualificationProcess",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "type": {
                        "type": "string",
                        "title": "type",
                        "enum": [
                            "habilitation",
                            "doctoral thesis"
                        ]
                    },
                    "completionDate": {
                        "type": "string",
                        "title": "completionDate",
                        "format": "date"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "type"
                ]
            }
        },
        "ids": {
            "type": "array",
            "title": "ids",
            "additionalItems": true,
            "items": {
                "type": "object",
                "additionalProperties": true,
                "anyOf": [
                    {
                        "type": "object",
                        "properties": {
                            "houseID": {
                                "type": "string",
                                "title": "houseID"
                            }
                        },
                        "additionalProperties": true
                    },
                    {
                        "type": "object",
                        "properties": {
                            "orcid": {
                                "type": "string",
                                "title": "ORCiD"
                            }
                        },
                        "additionalProperties": true
                    },
                    {
                        "type": "object",
                        "properties": {
                            "id": {
                                "type": "string"
                            }
                        }
                    }
                ]
            }
        },
        "positions": {
            "type": "array",
            "title": "positions",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "positionName": {
                        "type": "string",
                        "title": "positionName"
                    },
                    "organisationalUnit": {
                        "type": "string",
                        "title": "organisationalUnit"
                    },
                    "organisationalUnitID": {
                        "type": "string",
                        "title": "organisationalUnitID"
                    },
                    "staffCategory": {
                        "type": "string",
                        "title": "staffCategory"
                    },
                    "timeLimit": {
                        "type": "string",
                        "title": "timeLimit",
                        "enum": [
                            "befristet",
                            "unbefristet"
                        ]
                    },
                    "subjects": {
                        "type": "array",
                        "title": "subjects",
                        "additionalItems": true,
                        "items": {
                            "type": "string"
                        }
                    },
                    "disciplinaryResearchAreas": {
                        "type": "array",
                        "title": "disciplinaryResearchAreas",
                        "additionalItems": true,
                        "items": {
                            "type": "string"
                        }
                    }
                },
                "additionalProperties": false,
                "required": [
                    "positionName"
                ]
            }
        },
        "roles": {
            "type": "array",
            "title": "roles",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "roleName": {
                        "type": "string",
                        "title": "roleName"
                    },
                    "unit": {
                        "type": "string",
                        "title": "unit",
                        "enum": [
                            "projects",
                            "clusters",
                            "etc."
                        ]
                    },
                    "unitIds": {
                        "type": "array",
                        "title": "unitIds",
                        "additionalItems": true,
                        "items": {
                            "type": "object",
                            "additionalProperties": true,
                            "anyOf": [
                                {
                                    "type": "object",
                                    "properties": {
                                        "houseId": {
                                            "type": "string",
                                            "title": "houseId"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "anyOtherID": {
                                            "type": "string",
                                            "title": "anyOtherID"
                                        }
                                    }
                                }
                            ]
                        }
                    }
                },
                "additionalProperties": false,
                "required": [
                    "roleName"
                ]
            }
        },
        "interDisciplinaryResearchAreas": {
            "type": "array",
            "title": "interDisciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        }
    },
    "additionalProperties": false,
    "required": [
        "firstName",
        "lastName"
    ]
}
```

##### 1.1.2.3.5 **Person** JSON data

```
{
    "firstName": "Lorem",
    "lastName": "Lorem",
    "middleName": "Lorem",
    "description": "Lorem",
    "birthday": "2011-06-14",
    "gender": "Lorem",
    "nationality": "Lorem",
    "address": "Lorem",
    "email": "/uKsWmKgVV^269sY'?v?c$.oou}C_R68Ky}~J8rXITR.!Y?^w{e52&bcVft#.ZEC'Fj9{L295IYC|haSKb*Jj|3KM9.O/`a*4PJCrkQm6k4/qi`^.xnPyR+}^.wa6W_%/Wl#Y5?ETt+Tl^*e/9sZ.IwJ.+jV6zu6J^#sbp4PI`h1JdB=S5#*?4N.Y.|AQrLYid!4#0s77vz}0T_Oj2.b~&KP+B?c/{&%H{PXz.jQ238={=bfkg|7+7!2qjsE7YPN#.|.1W_+CfGvUmjWyB#vfEZ.gz#6sbE.y`=V}@w.s.eyx7jsh1kzljiau46agau1cr0chh2k13hez8z9zv-ss6vzj04ri2f4l9vow.v.n.x2yold4dnb0pf39y37u6fn9x81at5tppqw38wagxo2jz4lq192u-baaqyp.v.3uoj7obfyq23cp1sf0zykriidu5gnd7f-ruz6v0ts3j9u751v7.uvtbcvzo9rl7yg-p9rhq.g577jout4o-309u0shzr2tmfv1ytdjhufrtjkqshn0dbrmgl.e6y-l1e78be05y.vu-fo8o-q7ryk2ogf1cttliklss3cgkn2x2ydndemxr1vrwv2.o.s.j.qjd/i",
    "phone": "+0 8 0 4 3 702 1 9 36 9 466 8 0",
    "webpages": [
        {
            "name": "Lorem",
            "url": "./resource.txt#frag01"
        }
    ],
    "disciplinaryResearchAreas": [
        "Lorem"
    ],
    "doctoralEligibility": true,
    "doctoralEligibilityFrom": "domes",
    "isPhD": true,
    "primarySupervisor": "Lorem",
    "doctoralCooperationPartner": "Lorem",
    "qualificationProcess": [
        {
            "type": "doctoral thesis",
            "completionDate": "2011-06-14"
        }
    ],
    "ids": [
        {
            "houseID": "Lorem"
        }
    ],
    "positions": [
        {
            "positionName": "Lorem",
            "organisationalUnit": "Lorem",
            "organisationalUnitID": "Lorem",
            "staffCategory": "Lorem",
            "timeLimit": "unbefristet",
            "subjects": [
                "Lorem"
            ],
            "disciplinaryResearchAreas": [
                "Lorem"
            ]
        }
    ],
    "roles": [
        {
            "roleName": "Lorem",
            "unit": "etc.",
            "unitIds": [
                {
                    "houseId": "Lorem"
                }
            ]
        }
    ],
    "interDisciplinaryResearchAreas": [
        "Lorem"
    ]
}
```

### <a id="320fd4ce-5d95-40f3-9dc6-67845ac68eb4"></a>1.1.2.4 Document **Project**

##### 1.1.2.4.1 **Project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image106.png?raw=true)

##### 1.1.2.4.2 **Project** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Project</td></tr><tr><td>Technical name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#8be31291-b199-42e0-a35b-1a2f226d5f5b><span class="name-container">BUA API MODEL</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3 **Project** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7f02d911-71a0-4294-bcd1-b524eb650802 class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#91afddf1-a5c0-4a4d-995e-ccdad664d70e class="margin-0">address</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#226667de-c663-41c8-8a39-3b3266814167 class="margin-0">phone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bda44202-c4d7-469a-a327-c37db84a04ca class="margin-0">emails</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ccd8caa8-f394-4c04-a1d8-fff84aa02599 class="margin-5">[0]</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fcdad188-8a69-4e33-962c-f00032c1e0b8 class="margin-0">organisationalUnit</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b7e99bfc-4f99-4cb3-a649-64ef21051b0c class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a384b076-2624-4652-9219-28191f176574 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#89d52e5c-20d8-40ec-8a96-2ebc1a9fc49e class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bbf1d805-4847-4399-9019-d07f39bc3947 class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1f4a5c42-5330-4917-9879-8b316906d8b9 class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#98088370-b765-49f0-ac44-841ecb43c80f class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c694783f-a895-4401-af59-4f9ebc69f50c class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#630d6da3-57ed-423c-8f18-7b56a6318d73 class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b94a1941-5f48-452a-9e8c-6da1e06684c9 class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a41f2cd7-74eb-4ce3-84ad-8d041ffa6af2 class="margin-10">coordinatorUnit</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4a990270-3599-43ee-89e8-d97b1fe3d858 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#90e88f8d-aaa1-462d-8b10-7be2c02768c0 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fd8fd72a-667d-4662-820b-5292d4a0dee9 class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5eabcc76-e952-462c-8751-c2b57d3d57ed class="margin-15">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#29bfc7f7-72d3-4380-9487-dfab44c004b7 class="margin-20">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7fc6cfb-573a-47ed-9b72-facee72a88c4 class="margin-15">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#406944fd-9e49-4132-9c61-15a1633cc5c7 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0a90ec00-3429-48c1-873a-7104367baa5f class="margin-0">parentProject</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#4e2c024f-65ff-41ae-a004-2e513f70d1b1 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6737e8c2-7132-41a0-9fa1-f0d551ec1f15 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#97b094aa-1e64-4bce-95b8-8e8c857c2b2a class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2c23277e-728a-4429-b047-4b90700ee9aa class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9045fca4-6a59-4c49-a6a3-d0340117a9f9 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8f4ca266-7c2a-471b-8c7f-ce53cbf28404 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6d9dcabb-5577-4701-8309-fe1bbbbb51ae class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#14acc0f8-c29e-49fd-bb7f-fae24d831f41 class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4a5dee85-86ab-46e7-b26e-d5a37e34c0d2 class="margin-0">projectCoordinatorOrganisation</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#6a747077-3120-4fd7-a712-149c98ec8a05 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#31a65ae1-1a2c-48b8-be8e-24f0144c4cb7 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f0a8aff8-f6b9-412d-9274-149154df24f7 class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1ed50261-534b-47e0-82bd-c3f275c34888 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9fc1c30c-7403-4eab-b395-f855f66794d6 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#47db61cf-772c-4385-88b8-af6c3b2d24e7 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f81d344c-98de-49ca-bf5e-a6e566c14ea0 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8be1f691-5c74-475b-9622-c473ec9ee816 class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b6001550-6dc4-450d-9878-a62b9162b4c7 class="margin-0">scientificProjectLead</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#f1a499c9-56be-427f-8f04-060210eb4c83 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6b6712d1-6a06-46a0-a31a-3daad83c6103 class="margin-10">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#77121077-8194-42fb-83a3-d2f07e7dd08e class="margin-10">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9035c902-2fa4-4fd4-aaed-c2f39b2c8db1 class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1a66b383-c9dc-41c0-9983-5ca1ca963433 class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#93130bbc-77fe-4050-ab27-d94aa270d7fe class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e9265d95-245d-4c87-ac8e-baffaa6ef459 class="margin-25">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#22ac8892-49d2-4be8-901d-7dba1b953ac6 class="margin-30">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#de237e85-2bd1-4cf6-b991-6f46eee4305e class="margin-25">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#98bb5686-4bf2-4f48-a6c7-1e17d9801171 class="margin-30">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#eb83883d-9db7-48b3-96ad-a94af70a92e2 class="margin-25">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#336e22f9-007b-40b9-a89b-51422ea20a0e class="margin-30">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b2b6596b-b047-44d6-b30b-2b0533c89651 class="margin-0">keywords</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c9d098a9-43fe-47ec-806c-60ac9aa33fb0 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4bad4692-6fd0-4f78-a858-0dd060851766 class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#64bfaa41-b265-462d-a094-fe027b205a47 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#386f5cc8-c270-4016-91f9-f16f46e711ab class="margin-0">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#240cb198-b233-4c48-8daa-5a0e1f9f27c4 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#984007ea-499a-4b59-ae98-ec86a5031c4f class="margin-0">description</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4f06ef06-3c15-4f50-b9ff-21fdb6fdbe61 class="margin-0">projectObjective</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1b2d1f31-c1f6-4557-8ead-9b0217d2e590 class="margin-0">funderCategories</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#7e7fd632-91a9-4ed7-a080-10313d344d05 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0b1bc9ac-20ea-4d79-8d85-91444506ec96 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ad655449-7631-4a60-8647-006e609ab76d class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e751c106-a3f8-46ec-b02c-02ee9150870c class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6878c8bf-7cb5-4a01-95d7-fb5a4b21fef4 class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d52347ec-4b87-4a7c-9784-d13be60579f7 class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8583819b-c53b-453d-977b-1bc39b39b527 class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e0a25074-91bc-4603-aa3d-5a27b306d41f class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0332d533-4b89-4c7d-9cfd-f01465b7a9d2 class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#49f769c7-f8b9-4148-8b39-431b6117ab3a class="margin-0">funders</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b6b8f9e1-1869-4921-848f-e71a553ff567 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a20d34a7-434e-4080-b76e-a6e7e74d6882 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#530272bb-e39d-4576-8560-326ca5d055cd class="margin-10">country</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e6a6a92d-dd6a-4fd9-a79b-e29ea96c87a3 class="margin-10">funderAbbrevation</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#42c27903-7f34-40ef-82ea-dbe3ee3e517a class="margin-10">fundRef</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#79ed0ffa-d326-4b41-b94c-27cbc653d967 class="margin-10">ror</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4aa62633-5d7f-41f5-a00c-618929190336 class="margin-10">isoCountryCode</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#10f8d8d1-1bf3-4fa2-875a-8a3f715db4f1 class="margin-0">projectStart</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#c7b6a4cd-5942-40c6-ad20-b6754bb05a8d class="margin-0">projectEnd</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#4f569dad-1876-48c5-b7d6-e4b6036aa598 class="margin-0">thirdPartyFunding</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#82e150e8-9e9f-4d28-9d94-38056ef5f553 class="margin-0">grantAmount</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#ab2e40c7-a605-42d6-9116-c0db1ab081e5 class="margin-0">projectStatus</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7db406b9-b342-4235-b373-137ad2074642 class="margin-0">webpages</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d0439121-7765-4510-9ba8-c82d21fee9d9 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7fee4a0d-267b-4f5d-8c88-00fdd68c10ce class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d4def0b7-f1d8-46c3-94f1-661ed5fea80c class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a22c3131-bb69-4994-9c47-3c34a1571989 class="margin-0">repositories</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#eea94d08-8bdb-46b7-86bb-c2b42959fb42 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c56742d0-77d3-444e-9b3b-8df559201888 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5d2fd6d0-abe8-46d1-9505-75b130e0cfdd class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9f9caef1-a61f-484b-bcdc-a8ef48c24a79 class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#98f5d3f4-e6b2-4680-8a28-912c5b232854 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="7f02d911-71a0-4294-bcd1-b524eb650802"></a>1.1.2.4.3.1 Field **name**

##### 1.1.2.4.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image107.png?raw=true)

##### 1.1.2.4.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="91afddf1-a5c0-4a4d-995e-ccdad664d70e"></a>1.1.2.4.3.2 Field **address**

##### 1.1.2.4.3.2.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image108.png?raw=true)

##### 1.1.2.4.3.2.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="226667de-c663-41c8-8a39-3b3266814167"></a>1.1.2.4.3.3 Field **phone**

##### 1.1.2.4.3.3.1 **phone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image109.png?raw=true)

##### 1.1.2.4.3.3.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td>phone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Pattern</td><td>^\+(?:[0-9] ?){6,25}[0-9]$</td></tr></tbody></table>

### <a id="bda44202-c4d7-469a-a327-c37db84a04ca"></a>1.1.2.4.3.4 Field **emails**

##### 1.1.2.4.3.4.1 **emails** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image110.png?raw=true)

##### 1.1.2.4.3.4.2 **emails** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ccd8caa8-f394-4c04-a1d8-fff84aa02599 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.4.3 **emails** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>emails</td></tr><tr><td>Technical name</td><td>emails</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="ccd8caa8-f394-4c04-a1d8-fff84aa02599"></a>1.1.2.4.3.5 Field **\[0\]**

##### 1.1.2.4.3.5.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image111.png?raw=true)

##### 1.1.2.4.3.5.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr><tr><td>Pattern</td><td>/^([\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+\.)*[\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+@((((([a-z0-9]{1}[a-z0-9\-]{0,62}[a-z0-9]{1})|[a-z])\.)+[a-z]{2,6})|(\d{1,3}\.){3}\d{1,3}(\:\d{1,5})?)$/i</td></tr></tbody></table>

### <a id="fcdad188-8a69-4e33-962c-f00032c1e0b8"></a>1.1.2.4.3.6 Field **organisationalUnit**

##### 1.1.2.4.3.6.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image112.png?raw=true)

##### 1.1.2.4.3.6.2 **organisationalUnit** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b7e99bfc-4f99-4cb3-a649-64ef21051b0c class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.6.3 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="b7e99bfc-4f99-4cb3-a649-64ef21051b0c"></a>1.1.2.4.3.7 Field **\[0\]**

##### 1.1.2.4.3.7.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image113.png?raw=true)

##### 1.1.2.4.3.7.2 **\[0\]** Hierarchy

Parent field: **organisationalUnit**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a384b076-2624-4652-9219-28191f176574 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#89d52e5c-20d8-40ec-8a96-2ebc1a9fc49e class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a41f2cd7-74eb-4ce3-84ad-8d041ffa6af2 class="margin-NaN">coordinatorUnit</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.7.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="a384b076-2624-4652-9219-28191f176574"></a>1.1.2.4.3.8 Field **name**

##### 1.1.2.4.3.8.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image114.png?raw=true)

##### 1.1.2.4.3.8.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="89d52e5c-20d8-40ec-8a96-2ebc1a9fc49e"></a>1.1.2.4.3.9 Field **ids**

##### 1.1.2.4.3.9.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image115.png?raw=true)

##### 1.1.2.4.3.9.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#bbf1d805-4847-4399-9019-d07f39bc3947 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.9.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="bbf1d805-4847-4399-9019-d07f39bc3947"></a>1.1.2.4.3.10 Field **\[0\]**

##### 1.1.2.4.3.10.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image116.png?raw=true)

##### 1.1.2.4.3.10.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1f4a5c42-5330-4917-9879-8b316906d8b9 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.10.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="1f4a5c42-5330-4917-9879-8b316906d8b9"></a>1.1.2.4.3.11 Field **anyOf**

##### 1.1.2.4.3.11.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image117.png?raw=true)

##### 1.1.2.4.3.11.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#98088370-b765-49f0-ac44-841ecb43c80f class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#630d6da3-57ed-423c-8f18-7b56a6318d73 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.11.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="98088370-b765-49f0-ac44-841ecb43c80f"></a>1.1.2.4.3.12 Field **\[0\] houseId**

##### 1.1.2.4.3.12.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image118.png?raw=true)

##### 1.1.2.4.3.12.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c694783f-a895-4401-af59-4f9ebc69f50c class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.12.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="c694783f-a895-4401-af59-4f9ebc69f50c"></a>1.1.2.4.3.13 Field **houseId**

##### 1.1.2.4.3.13.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image119.png?raw=true)

##### 1.1.2.4.3.13.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="630d6da3-57ed-423c-8f18-7b56a6318d73"></a>1.1.2.4.3.14 Field **\[1\] anyOtherID**

##### 1.1.2.4.3.14.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image120.png?raw=true)

##### 1.1.2.4.3.14.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b94a1941-5f48-452a-9e8c-6da1e06684c9 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.14.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="b94a1941-5f48-452a-9e8c-6da1e06684c9"></a>1.1.2.4.3.15 Field **anyOtherID**

##### 1.1.2.4.3.15.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image121.png?raw=true)

##### 1.1.2.4.3.15.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a41f2cd7-74eb-4ce3-84ad-8d041ffa6af2"></a>1.1.2.4.3.16 Field **coordinatorUnit**

##### 1.1.2.4.3.16.1 **coordinatorUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image122.png?raw=true)

##### 1.1.2.4.3.16.2 **coordinatorUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>coordinatorUnit</td></tr><tr><td>Technical name</td><td>coordinatorUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr></tbody></table>

### <a id="4a990270-3599-43ee-89e8-d97b1fe3d858"></a>1.1.2.4.3.17 Field **ids**

##### 1.1.2.4.3.17.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image123.png?raw=true)

##### 1.1.2.4.3.17.2 **ids** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#90e88f8d-aaa1-462d-8b10-7be2c02768c0 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.17.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="90e88f8d-aaa1-462d-8b10-7be2c02768c0"></a>1.1.2.4.3.18 Field **\[0\]**

##### 1.1.2.4.3.18.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image124.png?raw=true)

##### 1.1.2.4.3.18.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#fd8fd72a-667d-4662-820b-5292d4a0dee9 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.18.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="fd8fd72a-667d-4662-820b-5292d4a0dee9"></a>1.1.2.4.3.19 Field **anyOf**

##### 1.1.2.4.3.19.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image125.png?raw=true)

##### 1.1.2.4.3.19.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5eabcc76-e952-462c-8751-c2b57d3d57ed class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7fc6cfb-573a-47ed-9b72-facee72a88c4 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.19.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="5eabcc76-e952-462c-8751-c2b57d3d57ed"></a>1.1.2.4.3.20 Field **\[0\] houseId**

##### 1.1.2.4.3.20.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image126.png?raw=true)

##### 1.1.2.4.3.20.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#29bfc7f7-72d3-4380-9487-dfab44c004b7 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.20.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="29bfc7f7-72d3-4380-9487-dfab44c004b7"></a>1.1.2.4.3.21 Field **houseId**

##### 1.1.2.4.3.21.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image127.png?raw=true)

##### 1.1.2.4.3.21.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="a7fc6cfb-573a-47ed-9b72-facee72a88c4"></a>1.1.2.4.3.22 Field **\[1\] anyOtherID**

##### 1.1.2.4.3.22.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image128.png?raw=true)

##### 1.1.2.4.3.22.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#406944fd-9e49-4132-9c61-15a1633cc5c7 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.22.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="406944fd-9e49-4132-9c61-15a1633cc5c7"></a>1.1.2.4.3.23 Field **anyOtherID**

##### 1.1.2.4.3.23.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image129.png?raw=true)

##### 1.1.2.4.3.23.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="0a90ec00-3429-48c1-873a-7104367baa5f"></a>1.1.2.4.3.24 Field **parentProject**

##### 1.1.2.4.3.24.1 **parentProject** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image130.png?raw=true)

##### 1.1.2.4.3.24.2 **parentProject** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#4e2c024f-65ff-41ae-a004-2e513f70d1b1 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6737e8c2-7132-41a0-9fa1-f0d551ec1f15 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.24.3 **parentProject** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>parentProject</td></tr><tr><td>Technical name</td><td>parentProject</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="4e2c024f-65ff-41ae-a004-2e513f70d1b1"></a>1.1.2.4.3.25 Field **name**

##### 1.1.2.4.3.25.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image131.png?raw=true)

##### 1.1.2.4.3.25.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="6737e8c2-7132-41a0-9fa1-f0d551ec1f15"></a>1.1.2.4.3.26 Field **ids**

##### 1.1.2.4.3.26.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image132.png?raw=true)

##### 1.1.2.4.3.26.2 **ids** Hierarchy

Parent field: **parentProject**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#97b094aa-1e64-4bce-95b8-8e8c857c2b2a class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.26.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="97b094aa-1e64-4bce-95b8-8e8c857c2b2a"></a>1.1.2.4.3.27 Field **\[0\]**

##### 1.1.2.4.3.27.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image133.png?raw=true)

##### 1.1.2.4.3.27.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2c23277e-728a-4429-b047-4b90700ee9aa class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.27.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="2c23277e-728a-4429-b047-4b90700ee9aa"></a>1.1.2.4.3.28 Field **anyOf**

##### 1.1.2.4.3.28.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image134.png?raw=true)

##### 1.1.2.4.3.28.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9045fca4-6a59-4c49-a6a3-d0340117a9f9 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6d9dcabb-5577-4701-8309-fe1bbbbb51ae class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.28.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="9045fca4-6a59-4c49-a6a3-d0340117a9f9"></a>1.1.2.4.3.29 Field **\[0\] houseId**

##### 1.1.2.4.3.29.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image135.png?raw=true)

##### 1.1.2.4.3.29.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8f4ca266-7c2a-471b-8c7f-ce53cbf28404 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.29.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="8f4ca266-7c2a-471b-8c7f-ce53cbf28404"></a>1.1.2.4.3.30 Field **houseId**

##### 1.1.2.4.3.30.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image136.png?raw=true)

##### 1.1.2.4.3.30.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="6d9dcabb-5577-4701-8309-fe1bbbbb51ae"></a>1.1.2.4.3.31 Field **\[1\] anyOtherID**

##### 1.1.2.4.3.31.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image137.png?raw=true)

##### 1.1.2.4.3.31.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#14acc0f8-c29e-49fd-bb7f-fae24d831f41 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.31.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="14acc0f8-c29e-49fd-bb7f-fae24d831f41"></a>1.1.2.4.3.32 Field **anyOtherID**

##### 1.1.2.4.3.32.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image138.png?raw=true)

##### 1.1.2.4.3.32.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4a5dee85-86ab-46e7-b26e-d5a37e34c0d2"></a>1.1.2.4.3.33 Field **projectCoordinatorOrganisation**

##### 1.1.2.4.3.33.1 **projectCoordinatorOrganisation** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image139.png?raw=true)

##### 1.1.2.4.3.33.2 **projectCoordinatorOrganisation** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6a747077-3120-4fd7-a712-149c98ec8a05 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#31a65ae1-1a2c-48b8-be8e-24f0144c4cb7 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.33.3 **projectCoordinatorOrganisation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectCoordinatorOrganisation</td></tr><tr><td>Technical name</td><td>projectCoordinatorOrganisation</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="6a747077-3120-4fd7-a712-149c98ec8a05"></a>1.1.2.4.3.34 Field **name**

##### 1.1.2.4.3.34.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image140.png?raw=true)

##### 1.1.2.4.3.34.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="31a65ae1-1a2c-48b8-be8e-24f0144c4cb7"></a>1.1.2.4.3.35 Field **ids**

##### 1.1.2.4.3.35.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image141.png?raw=true)

##### 1.1.2.4.3.35.2 **ids** Hierarchy

Parent field: **projectCoordinatorOrganisation**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f0a8aff8-f6b9-412d-9274-149154df24f7 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.35.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f0a8aff8-f6b9-412d-9274-149154df24f7"></a>1.1.2.4.3.36 Field **\[0\]**

##### 1.1.2.4.3.36.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image142.png?raw=true)

##### 1.1.2.4.3.36.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1ed50261-534b-47e0-82bd-c3f275c34888 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.36.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="1ed50261-534b-47e0-82bd-c3f275c34888"></a>1.1.2.4.3.37 Field **anyOf**

##### 1.1.2.4.3.37.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image143.png?raw=true)

##### 1.1.2.4.3.37.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9fc1c30c-7403-4eab-b395-f855f66794d6 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f81d344c-98de-49ca-bf5e-a6e566c14ea0 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.37.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="9fc1c30c-7403-4eab-b395-f855f66794d6"></a>1.1.2.4.3.38 Field **\[0\] houseId**

##### 1.1.2.4.3.38.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image144.png?raw=true)

##### 1.1.2.4.3.38.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#47db61cf-772c-4385-88b8-af6c3b2d24e7 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.38.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="47db61cf-772c-4385-88b8-af6c3b2d24e7"></a>1.1.2.4.3.39 Field **houseId**

##### 1.1.2.4.3.39.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image145.png?raw=true)

##### 1.1.2.4.3.39.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="f81d344c-98de-49ca-bf5e-a6e566c14ea0"></a>1.1.2.4.3.40 Field **\[1\] anyOtherID**

##### 1.1.2.4.3.40.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image146.png?raw=true)

##### 1.1.2.4.3.40.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8be1f691-5c74-475b-9622-c473ec9ee816 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.40.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="8be1f691-5c74-475b-9622-c473ec9ee816"></a>1.1.2.4.3.41 Field **anyOtherID**

##### 1.1.2.4.3.41.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image147.png?raw=true)

##### 1.1.2.4.3.41.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="b6001550-6dc4-450d-9878-a62b9162b4c7"></a>1.1.2.4.3.42 Field **scientificProjectLead**

##### 1.1.2.4.3.42.1 **scientificProjectLead** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image148.png?raw=true)

##### 1.1.2.4.3.42.2 **scientificProjectLead** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f1a499c9-56be-427f-8f04-060210eb4c83 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.42.3 **scientificProjectLead** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>scientificProjectLead</td></tr><tr><td>Technical name</td><td>scientificProjectLead</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="f1a499c9-56be-427f-8f04-060210eb4c83"></a>1.1.2.4.3.43 Field **\[0\]**

##### 1.1.2.4.3.43.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image149.png?raw=true)

##### 1.1.2.4.3.43.2 **\[0\]** Hierarchy

Parent field: **scientificProjectLead**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6b6712d1-6a06-46a0-a31a-3daad83c6103 class="margin-NaN">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#77121077-8194-42fb-83a3-d2f07e7dd08e class="margin-NaN">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9035c902-2fa4-4fd4-aaed-c2f39b2c8db1 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.43.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="6b6712d1-6a06-46a0-a31a-3daad83c6103"></a>1.1.2.4.3.44 Field **firstName**

##### 1.1.2.4.3.44.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image150.png?raw=true)

##### 1.1.2.4.3.44.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="77121077-8194-42fb-83a3-d2f07e7dd08e"></a>1.1.2.4.3.45 Field **lastName**

##### 1.1.2.4.3.45.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image151.png?raw=true)

##### 1.1.2.4.3.45.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="9035c902-2fa4-4fd4-aaed-c2f39b2c8db1"></a>1.1.2.4.3.46 Field **ids**

##### 1.1.2.4.3.46.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image152.png?raw=true)

##### 1.1.2.4.3.46.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1a66b383-c9dc-41c0-9983-5ca1ca963433 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.46.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="1a66b383-c9dc-41c0-9983-5ca1ca963433"></a>1.1.2.4.3.47 Field **\[0\]**

##### 1.1.2.4.3.47.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image153.png?raw=true)

##### 1.1.2.4.3.47.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#93130bbc-77fe-4050-ab27-d94aa270d7fe class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.47.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="93130bbc-77fe-4050-ab27-d94aa270d7fe"></a>1.1.2.4.3.48 Field **anyOf**

##### 1.1.2.4.3.48.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image154.png?raw=true)

##### 1.1.2.4.3.48.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e9265d95-245d-4c87-ac8e-baffaa6ef459 class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#de237e85-2bd1-4cf6-b991-6f46eee4305e class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#eb83883d-9db7-48b3-96ad-a94af70a92e2 class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.48.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="e9265d95-245d-4c87-ac8e-baffaa6ef459"></a>1.1.2.4.3.49 Field **\[0\] houseID**

##### 1.1.2.4.3.49.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image155.png?raw=true)

##### 1.1.2.4.3.49.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#22ac8892-49d2-4be8-901d-7dba1b953ac6 class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.49.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="22ac8892-49d2-4be8-901d-7dba1b953ac6"></a>1.1.2.4.3.50 Field **houseID**

##### 1.1.2.4.3.50.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image156.png?raw=true)

##### 1.1.2.4.3.50.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="de237e85-2bd1-4cf6-b991-6f46eee4305e"></a>1.1.2.4.3.51 Field **\[1\] ORCiD**

##### 1.1.2.4.3.51.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image157.png?raw=true)

##### 1.1.2.4.3.51.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#98bb5686-4bf2-4f48-a6c7-1e17d9801171 class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.51.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="98bb5686-4bf2-4f48-a6c7-1e17d9801171"></a>1.1.2.4.3.52 Field **ORCiD**

##### 1.1.2.4.3.52.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image158.png?raw=true)

##### 1.1.2.4.3.52.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="eb83883d-9db7-48b3-96ad-a94af70a92e2"></a>1.1.2.4.3.53 Field **\[2\] anyOtherID**

##### 1.1.2.4.3.53.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image159.png?raw=true)

##### 1.1.2.4.3.53.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#336e22f9-007b-40b9-a89b-51422ea20a0e class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.53.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="336e22f9-007b-40b9-a89b-51422ea20a0e"></a>1.1.2.4.3.54 Field **id**

##### 1.1.2.4.3.54.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image160.png?raw=true)

##### 1.1.2.4.3.54.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="b2b6596b-b047-44d6-b30b-2b0533c89651"></a>1.1.2.4.3.55 Field **keywords**

##### 1.1.2.4.3.55.1 **keywords** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image161.png?raw=true)

##### 1.1.2.4.3.55.2 **keywords** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c9d098a9-43fe-47ec-806c-60ac9aa33fb0 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.55.3 **keywords** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>keywords</td></tr><tr><td>Technical name</td><td>keywords</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="c9d098a9-43fe-47ec-806c-60ac9aa33fb0"></a>1.1.2.4.3.56 Field **\[0\]**

##### 1.1.2.4.3.56.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image162.png?raw=true)

##### 1.1.2.4.3.56.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4bad4692-6fd0-4f78-a858-0dd060851766"></a>1.1.2.4.3.57 Field **disciplinaryResearchAreas**

##### 1.1.2.4.3.57.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image163.png?raw=true)

##### 1.1.2.4.3.57.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#64bfaa41-b265-462d-a094-fe027b205a47 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.57.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="64bfaa41-b265-462d-a094-fe027b205a47"></a>1.1.2.4.3.58 Field **\[0\]**

##### 1.1.2.4.3.58.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image164.png?raw=true)

##### 1.1.2.4.3.58.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="386f5cc8-c270-4016-91f9-f16f46e711ab"></a>1.1.2.4.3.59 Field **subjects**

##### 1.1.2.4.3.59.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image165.png?raw=true)

##### 1.1.2.4.3.59.2 **subjects** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#240cb198-b233-4c48-8daa-5a0e1f9f27c4 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.59.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="240cb198-b233-4c48-8daa-5a0e1f9f27c4"></a>1.1.2.4.3.60 Field **\[0\]**

##### 1.1.2.4.3.60.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image166.png?raw=true)

##### 1.1.2.4.3.60.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="984007ea-499a-4b59-ae98-ec86a5031c4f"></a>1.1.2.4.3.61 Field **description**

##### 1.1.2.4.3.61.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image167.png?raw=true)

##### 1.1.2.4.3.61.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4f06ef06-3c15-4f50-b9ff-21fdb6fdbe61"></a>1.1.2.4.3.62 Field **projectObjective**

##### 1.1.2.4.3.62.1 **projectObjective** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image168.png?raw=true)

##### 1.1.2.4.3.62.2 **projectObjective** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectObjective</td></tr><tr><td>Technical name</td><td>projectObjective</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1b2d1f31-c1f6-4557-8ead-9b0217d2e590"></a>1.1.2.4.3.63 Field **funderCategories**

##### 1.1.2.4.3.63.1 **funderCategories** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image169.png?raw=true)

##### 1.1.2.4.3.63.2 **funderCategories** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7e7fd632-91a9-4ed7-a080-10313d344d05 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.63.3 **funderCategories** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funderCategories</td></tr><tr><td>Technical name</td><td>funderCategories</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="7e7fd632-91a9-4ed7-a080-10313d344d05"></a>1.1.2.4.3.64 Field **\[0\]**

##### 1.1.2.4.3.64.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image170.png?raw=true)

##### 1.1.2.4.3.64.2 **\[0\]** Hierarchy

Parent field: **funderCategories**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0b1bc9ac-20ea-4d79-8d85-91444506ec96 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ad655449-7631-4a60-8647-006e609ab76d class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.64.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="0b1bc9ac-20ea-4d79-8d85-91444506ec96"></a>1.1.2.4.3.65 Field **name**

##### 1.1.2.4.3.65.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image171.png?raw=true)

##### 1.1.2.4.3.65.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="ad655449-7631-4a60-8647-006e609ab76d"></a>1.1.2.4.3.66 Field **ids**

##### 1.1.2.4.3.66.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image172.png?raw=true)

##### 1.1.2.4.3.66.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e751c106-a3f8-46ec-b02c-02ee9150870c class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.66.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="e751c106-a3f8-46ec-b02c-02ee9150870c"></a>1.1.2.4.3.67 Field **\[0\]**

##### 1.1.2.4.3.67.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image173.png?raw=true)

##### 1.1.2.4.3.67.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6878c8bf-7cb5-4a01-95d7-fb5a4b21fef4 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.67.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="6878c8bf-7cb5-4a01-95d7-fb5a4b21fef4"></a>1.1.2.4.3.68 Field **anyOf**

##### 1.1.2.4.3.68.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image174.png?raw=true)

##### 1.1.2.4.3.68.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d52347ec-4b87-4a7c-9784-d13be60579f7 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e0a25074-91bc-4603-aa3d-5a27b306d41f class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.68.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="d52347ec-4b87-4a7c-9784-d13be60579f7"></a>1.1.2.4.3.69 Field **\[0\] houseId**

##### 1.1.2.4.3.69.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image175.png?raw=true)

##### 1.1.2.4.3.69.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8583819b-c53b-453d-977b-1bc39b39b527 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.69.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="8583819b-c53b-453d-977b-1bc39b39b527"></a>1.1.2.4.3.70 Field **houseId**

##### 1.1.2.4.3.70.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image176.png?raw=true)

##### 1.1.2.4.3.70.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e0a25074-91bc-4603-aa3d-5a27b306d41f"></a>1.1.2.4.3.71 Field **\[1\] anyOtherID**

##### 1.1.2.4.3.71.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image177.png?raw=true)

##### 1.1.2.4.3.71.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0332d533-4b89-4c7d-9cfd-f01465b7a9d2 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.71.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="0332d533-4b89-4c7d-9cfd-f01465b7a9d2"></a>1.1.2.4.3.72 Field **anyOtherID**

##### 1.1.2.4.3.72.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image178.png?raw=true)

##### 1.1.2.4.3.72.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="49f769c7-f8b9-4148-8b39-431b6117ab3a"></a>1.1.2.4.3.73 Field **funders**

##### 1.1.2.4.3.73.1 **funders** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image179.png?raw=true)

##### 1.1.2.4.3.73.2 **funders** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b6b8f9e1-1869-4921-848f-e71a553ff567 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.73.3 **funders** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funders</td></tr><tr><td>Technical name</td><td>funders</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="b6b8f9e1-1869-4921-848f-e71a553ff567"></a>1.1.2.4.3.74 Field **\[0\]**

##### 1.1.2.4.3.74.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image180.png?raw=true)

##### 1.1.2.4.3.74.2 **\[0\]** Hierarchy

Parent field: **funders**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a20d34a7-434e-4080-b76e-a6e7e74d6882 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#530272bb-e39d-4576-8560-326ca5d055cd class="margin-NaN">country</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e6a6a92d-dd6a-4fd9-a79b-e29ea96c87a3 class="margin-NaN">funderAbbrevation</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#42c27903-7f34-40ef-82ea-dbe3ee3e517a class="margin-NaN">fundRef</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#79ed0ffa-d326-4b41-b94c-27cbc653d967 class="margin-NaN">ror</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4aa62633-5d7f-41f5-a00c-618929190336 class="margin-NaN">isoCountryCode</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.74.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="a20d34a7-434e-4080-b76e-a6e7e74d6882"></a>1.1.2.4.3.75 Field **name**

##### 1.1.2.4.3.75.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image181.png?raw=true)

##### 1.1.2.4.3.75.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="530272bb-e39d-4576-8560-326ca5d055cd"></a>1.1.2.4.3.76 Field **country**

##### 1.1.2.4.3.76.1 **country** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image182.png?raw=true)

##### 1.1.2.4.3.76.2 **country** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>country</td></tr><tr><td>Technical name</td><td>country</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e6a6a92d-dd6a-4fd9-a79b-e29ea96c87a3"></a>1.1.2.4.3.77 Field **funderAbbrevation**

##### 1.1.2.4.3.77.1 **funderAbbrevation** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image183.png?raw=true)

##### 1.1.2.4.3.77.2 **funderAbbrevation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funderAbbrevation</td></tr><tr><td>Technical name</td><td>funderAbbrevation</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="42c27903-7f34-40ef-82ea-dbe3ee3e517a"></a>1.1.2.4.3.78 Field **fundRef**

##### 1.1.2.4.3.78.1 **fundRef** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image184.png?raw=true)

##### 1.1.2.4.3.78.2 **fundRef** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>fundRef</td></tr><tr><td>Technical name</td><td>fundRef</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="79ed0ffa-d326-4b41-b94c-27cbc653d967"></a>1.1.2.4.3.79 Field **ror**

##### 1.1.2.4.3.79.1 **ror** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image185.png?raw=true)

##### 1.1.2.4.3.79.2 **ror** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ror</td></tr><tr><td>Technical name</td><td>ror</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4aa62633-5d7f-41f5-a00c-618929190336"></a>1.1.2.4.3.80 Field **isoCountryCode**

##### 1.1.2.4.3.80.1 **isoCountryCode** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image186.png?raw=true)

##### 1.1.2.4.3.80.2 **isoCountryCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>isoCountryCode</td></tr><tr><td>Technical name</td><td>isoCountryCode</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="10f8d8d1-1bf3-4fa2-875a-8a3f715db4f1"></a>1.1.2.4.3.81 Field **projectStart**

##### 1.1.2.4.3.81.1 **projectStart** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image187.png?raw=true)

##### 1.1.2.4.3.81.2 **projectStart** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectStart</td></tr><tr><td>Technical name</td><td>projectStart</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="c7b6a4cd-5942-40c6-ad20-b6754bb05a8d"></a>1.1.2.4.3.82 Field **projectEnd**

##### 1.1.2.4.3.82.1 **projectEnd** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image188.png?raw=true)

##### 1.1.2.4.3.82.2 **projectEnd** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectEnd</td></tr><tr><td>Technical name</td><td>projectEnd</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="4f569dad-1876-48c5-b7d6-e4b6036aa598"></a>1.1.2.4.3.83 Field **thirdPartyFunding**

##### 1.1.2.4.3.83.1 **thirdPartyFunding** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image189.png?raw=true)

##### 1.1.2.4.3.83.2 **thirdPartyFunding** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>thirdPartyFunding</td></tr><tr><td>Technical name</td><td>thirdPartyFunding</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Unit</td><td>euro</td></tr><tr><td>Default</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="82e150e8-9e9f-4d28-9d94-38056ef5f553"></a>1.1.2.4.3.84 Field **grantAmount**

##### 1.1.2.4.3.84.1 **grantAmount** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image190.png?raw=true)

##### 1.1.2.4.3.84.2 **grantAmount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>grantAmount</td></tr><tr><td>Technical name</td><td>grantAmount</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Unit</td><td>euro</td></tr><tr><td>Default</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="ab2e40c7-a605-42d6-9116-c0db1ab081e5"></a>1.1.2.4.3.85 Field **projectStatus**

##### 1.1.2.4.3.85.1 **projectStatus** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image191.png?raw=true)

##### 1.1.2.4.3.85.2 **projectStatus** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectStatus</td></tr><tr><td>Technical name</td><td>projectStatus</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>open,closed,proposal submitted,rejected</td></tr></tbody></table>

### <a id="7db406b9-b342-4235-b373-137ad2074642"></a>1.1.2.4.3.86 Field **webpages**

##### 1.1.2.4.3.86.1 **webpages** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image192.png?raw=true)

##### 1.1.2.4.3.86.2 **webpages** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d0439121-7765-4510-9ba8-c82d21fee9d9 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.86.3 **webpages** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>webpages</td></tr><tr><td>Technical name</td><td>webpages</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="d0439121-7765-4510-9ba8-c82d21fee9d9"></a>1.1.2.4.3.87 Field **\[0\]**

##### 1.1.2.4.3.87.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image193.png?raw=true)

##### 1.1.2.4.3.87.2 **\[0\]** Hierarchy

Parent field: **webpages**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7fee4a0d-267b-4f5d-8c88-00fdd68c10ce class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d4def0b7-f1d8-46c3-94f1-661ed5fea80c class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.87.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="7fee4a0d-267b-4f5d-8c88-00fdd68c10ce"></a>1.1.2.4.3.88 Field **name**

##### 1.1.2.4.3.88.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image194.png?raw=true)

##### 1.1.2.4.3.88.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="d4def0b7-f1d8-46c3-94f1-661ed5fea80c"></a>1.1.2.4.3.89 Field **url**

##### 1.1.2.4.3.89.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image195.png?raw=true)

##### 1.1.2.4.3.89.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="a22c3131-bb69-4994-9c47-3c34a1571989"></a>1.1.2.4.3.90 Field **repositories**

##### 1.1.2.4.3.90.1 **repositories** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image196.png?raw=true)

##### 1.1.2.4.3.90.2 **repositories** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#eea94d08-8bdb-46b7-86bb-c2b42959fb42 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.90.3 **repositories** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>repositories</td></tr><tr><td>Technical name</td><td>repositories</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="eea94d08-8bdb-46b7-86bb-c2b42959fb42"></a>1.1.2.4.3.91 Field **\[0\]**

##### 1.1.2.4.3.91.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image197.png?raw=true)

##### 1.1.2.4.3.91.2 **\[0\]** Hierarchy

Parent field: **repositories**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c56742d0-77d3-444e-9b3b-8df559201888 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5d2fd6d0-abe8-46d1-9505-75b130e0cfdd class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.91.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="c56742d0-77d3-444e-9b3b-8df559201888"></a>1.1.2.4.3.92 Field **name**

##### 1.1.2.4.3.92.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image198.png?raw=true)

##### 1.1.2.4.3.92.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="5d2fd6d0-abe8-46d1-9505-75b130e0cfdd"></a>1.1.2.4.3.93 Field **url**

##### 1.1.2.4.3.93.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image199.png?raw=true)

##### 1.1.2.4.3.93.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="9f9caef1-a61f-484b-bcdc-a8ef48c24a79"></a>1.1.2.4.3.94 Field **interDisciplinaryResearchAreas**

##### 1.1.2.4.3.94.1 **interDisciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image200.png?raw=true)

##### 1.1.2.4.3.94.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#98f5d3f4-e6b2-4680-8a28-912c5b232854 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.4.3.94.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="98f5d3f4-e6b2-4680-8a28-912c5b232854"></a>1.1.2.4.3.95 Field **\[0\]**

##### 1.1.2.4.3.95.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image201.png?raw=true)

##### 1.1.2.4.3.95.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 1.1.2.4.4 **Project** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "Project",
    "properties": {
        "name": {
            "type": "string",
            "title": "name"
        },
        "address": {
            "type": "string",
            "title": "address"
        },
        "phone": {
            "type": "string",
            "title": "phone",
            "pattern": "^\\+(?:[0-9] ?){6,25}[0-9]$"
        },
        "emails": {
            "type": "array",
            "title": "emails",
            "additionalItems": true,
            "items": {
                "type": "string",
                "format": "email",
                "pattern": "/^([\\w\\!\\#$\\%\\&\\'\\*\\+\\-\\/\\=\\?\\^\\`{\\|\\}\\~]+\\.)*[\\w\\!\\#$\\%\\&\\'\\*\\+\\-\\/\\=\\?\\^\\`{\\|\\}\\~]+@((((([a-z0-9]{1}[a-z0-9\\-]{0,62}[a-z0-9]{1})|[a-z])\\.)+[a-z]{2,6})|(\\d{1,3}\\.){3}\\d{1,3}(\\:\\d{1,5})?)$/i"
            }
        },
        "organisationalUnit": {
            "type": "array",
            "title": "organisationalUnit",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "ids": {
                        "type": "array",
                        "title": "ids",
                        "additionalItems": true,
                        "items": {
                            "type": "object",
                            "additionalProperties": true,
                            "anyOf": [
                                {
                                    "type": "object",
                                    "properties": {
                                        "houseId": {
                                            "type": "string",
                                            "title": "houseId"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "anyOtherID": {
                                            "type": "string",
                                            "title": "anyOtherID"
                                        }
                                    }
                                }
                            ]
                        }
                    },
                    "coordinatorUnit": {
                        "type": "boolean",
                        "title": "coordinatorUnit"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name"
                ]
            }
        },
        "ids": {
            "type": "array",
            "title": "ids",
            "additionalItems": true,
            "items": {
                "type": "object",
                "additionalProperties": true,
                "anyOf": [
                    {
                        "type": "object",
                        "properties": {
                            "houseId": {
                                "type": "string",
                                "title": "houseId"
                            }
                        },
                        "additionalProperties": true
                    },
                    {
                        "type": "object",
                        "properties": {
                            "anyOtherID": {
                                "type": "string",
                                "title": "anyOtherID"
                            }
                        }
                    }
                ]
            }
        },
        "parentProject": {
            "type": "object",
            "title": "parentProject",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "ids": {
                    "type": "array",
                    "title": "ids",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": true,
                        "anyOf": [
                            {
                                "type": "object",
                                "properties": {
                                    "houseId": {
                                        "type": "string",
                                        "title": "houseId"
                                    }
                                },
                                "additionalProperties": true
                            },
                            {
                                "type": "object",
                                "properties": {
                                    "anyOtherID": {
                                        "type": "string",
                                        "title": "anyOtherID"
                                    }
                                }
                            }
                        ]
                    }
                }
            },
            "additionalProperties": false,
            "required": [
                "name"
            ]
        },
        "projectCoordinatorOrganisation": {
            "type": "object",
            "title": "projectCoordinatorOrganisation",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "ids": {
                    "type": "array",
                    "title": "ids",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": true,
                        "anyOf": [
                            {
                                "type": "object",
                                "properties": {
                                    "houseId": {
                                        "type": "string",
                                        "title": "houseId"
                                    }
                                },
                                "additionalProperties": true
                            },
                            {
                                "type": "object",
                                "properties": {
                                    "anyOtherID": {
                                        "type": "string",
                                        "title": "anyOtherID"
                                    }
                                }
                            }
                        ]
                    }
                }
            },
            "additionalProperties": false,
            "required": [
                "name"
            ]
        },
        "scientificProjectLead": {
            "type": "array",
            "title": "scientificProjectLead",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "firstName": {
                        "type": "string",
                        "title": "firstName"
                    },
                    "lastName": {
                        "type": "string",
                        "title": "lastName"
                    },
                    "ids": {
                        "type": "array",
                        "title": "ids",
                        "additionalItems": true,
                        "items": {
                            "type": "object",
                            "additionalProperties": true,
                            "anyOf": [
                                {
                                    "type": "object",
                                    "properties": {
                                        "houseID": {
                                            "type": "string",
                                            "title": "houseID"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "orcid": {
                                            "type": "string",
                                            "title": "ORCiD"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "id": {
                                            "type": "string"
                                        }
                                    }
                                }
                            ]
                        }
                    }
                },
                "additionalProperties": false,
                "required": [
                    "firstName",
                    "lastName"
                ]
            }
        },
        "keywords": {
            "type": "array",
            "title": "keywords",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "disciplinaryResearchAreas": {
            "type": "array",
            "title": "disciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "subjects": {
            "type": "array",
            "title": "subjects",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "description": {
            "type": "string",
            "title": "description"
        },
        "projectObjective": {
            "type": "string",
            "title": "projectObjective"
        },
        "funderCategories": {
            "type": "array",
            "title": "funderCategories",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "ids": {
                        "type": "array",
                        "title": "ids",
                        "additionalItems": true,
                        "items": {
                            "type": "object",
                            "additionalProperties": true,
                            "anyOf": [
                                {
                                    "type": "object",
                                    "properties": {
                                        "houseId": {
                                            "type": "string",
                                            "title": "houseId"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "anyOtherID": {
                                            "type": "string",
                                            "title": "anyOtherID"
                                        }
                                    }
                                }
                            ]
                        }
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name"
                ]
            }
        },
        "funders": {
            "type": "array",
            "title": "funders",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "country": {
                        "type": "string",
                        "title": "country"
                    },
                    "funderAbbrevation": {
                        "type": "string",
                        "title": "funderAbbrevation"
                    },
                    "fundRef": {
                        "type": "string",
                        "title": "fundRef"
                    },
                    "ror": {
                        "type": "string",
                        "title": "ror"
                    },
                    "isoCountryCode": {
                        "type": "string",
                        "title": "isoCountryCode"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name"
                ]
            }
        },
        "projectStart": {
            "type": "string",
            "title": "projectStart",
            "format": "date"
        },
        "projectEnd": {
            "type": "string",
            "title": "projectEnd"
        },
        "thirdPartyFunding": {
            "type": "number",
            "title": "thirdPartyFunding",
            "default": 0
        },
        "grantAmount": {
            "type": "number",
            "title": "grantAmount",
            "default": 0
        },
        "projectStatus": {
            "type": "string",
            "title": "projectStatus",
            "enum": [
                "open",
                "closed",
                "proposal submitted",
                "rejected"
            ]
        },
        "webpages": {
            "type": "array",
            "title": "webpages",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "url": {
                        "type": "string",
                        "title": "url",
                        "format": "uri"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name",
                    "url"
                ]
            }
        },
        "repositories": {
            "type": "array",
            "title": "repositories",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "name": {
                        "type": "string",
                        "title": "name"
                    },
                    "url": {
                        "type": "string",
                        "title": "url",
                        "format": "uri"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "name",
                    "url"
                ]
            }
        },
        "interDisciplinaryResearchAreas": {
            "type": "array",
            "title": "interDisciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        }
    },
    "additionalProperties": false,
    "required": [
        "name"
    ]
}
```

##### 1.1.2.4.5 **Project** JSON data

```
{
    "name": "Lorem",
    "address": "Lorem",
    "phone": "+64 9 9 838 516 3 5 7 2 4 7 4 8 5 07593",
    "emails": [
        "/l#LRhF'YD}+}.bW9C*nlK}73cX28V1oQKg8v7Y-wP?.F9nu31JV$Zlla|C332XjK?cwVN}dfq.RbR*weMv}Rr*kw{wM&komF9ce5.lksG77ry|P}s.MfRy.2a&I=j$Qr8CslI*m@86.23.474.5:60/i"
    ],
    "organisationalUnit": [
        {
            "name": "Lorem",
            "ids": [
                {
                    "houseId": "Lorem"
                }
            ],
            "coordinatorUnit": true
        }
    ],
    "ids": [
        {
            "houseId": "Lorem"
        }
    ],
    "parentProject": {
        "name": "Lorem",
        "ids": [
            {
                "houseId": "Lorem"
            }
        ]
    },
    "projectCoordinatorOrganisation": {
        "name": "Lorem",
        "ids": [
            {
                "houseId": "Lorem"
            }
        ]
    },
    "scientificProjectLead": [
        {
            "firstName": "Lorem",
            "lastName": "Lorem",
            "ids": [
                {
                    "houseID": "Lorem"
                }
            ]
        }
    ],
    "keywords": [
        "Lorem"
    ],
    "disciplinaryResearchAreas": [
        "Lorem"
    ],
    "subjects": [
        "Lorem"
    ],
    "description": "Lorem",
    "projectObjective": "Lorem",
    "funderCategories": [
        {
            "name": "Lorem",
            "ids": [
                {
                    "houseId": "Lorem"
                }
            ]
        }
    ],
    "funders": [
        {
            "name": "Lorem",
            "country": "Lorem",
            "funderAbbrevation": "Lorem",
            "fundRef": "Lorem",
            "ror": "Lorem",
            "isoCountryCode": "Lorem"
        }
    ],
    "projectStart": "2011-06-14",
    "projectEnd": "Lorem",
    "thirdPartyFunding": 0,
    "grantAmount": 0,
    "projectStatus": "rejected",
    "webpages": [
        {
            "name": "Lorem",
            "url": "./resource.txt#frag01"
        }
    ],
    "repositories": [
        {
            "name": "Lorem",
            "url": "./resource.txt#frag01"
        }
    ],
    "interDisciplinaryResearchAreas": [
        "Lorem"
    ]
}
```

### <a id="4588d8fb-0f50-4c50-817f-fbba7f79af32"></a>1.1.2.5 Document **Publication**

##### 1.1.2.5.1 **Publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image202.png?raw=true)

##### 1.1.2.5.2 **Publication** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Publication</td></tr><tr><td>Technical name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#8be31291-b199-42e0-a35b-1a2f226d5f5b><span class="name-container">BUA API MODEL</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3 **Publication** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#34a8c944-a5dd-4276-93dc-7819fef8d67c class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d3ef9907-13f3-4286-a25e-48a284737e17 class="margin-0">documentType</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#27448d6a-260e-4651-ba0e-d515f116f5d5 class="margin-0">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d4913695-803f-4da0-a06a-3ac327512b2c class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8eb515c5-48b5-49fd-8222-3e0cbbcf0261 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#16fe27db-bdb1-47a8-a9d6-27890b8e652a class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0a2f1bc8-422f-428a-b5c4-8cc6ab56753c class="margin-15">[0]&nbsp;doi</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#88a6aa0d-1970-4fa6-a67d-129062bdcdc9 class="margin-20">doi</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a4415c9e-8a38-4c8b-bdae-e45c581433cb class="margin-15">[1]&nbsp;Scopus&nbsp;EID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#894bdba5-9de2-4088-9446-13c376c5830c class="margin-20">Scopus&nbsp;EID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#822adadb-d194-42b6-8f9a-b9ee484dee7b class="margin-15">[2]&nbsp;WOSut</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cb3d1e0c-a4f1-4dfd-9b41-cb421065b47e class="margin-20">WOSut</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#566a79f9-90a5-4bb0-8ce7-76418900bca9 class="margin-15">[3]&nbsp;PMID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#805e57e1-3a64-4706-b096-7cef272f072e class="margin-20">PMID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#741e088d-d217-47b9-a3f1-de2627ee3448 class="margin-15">[4]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e1750472-600c-42b7-a26a-fe9906c88a85 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d7838924-06bf-4526-ba8a-379fbe876e51 class="margin-0">startPage</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#a935f6a7-020e-4ec8-8d2f-c078ab2aa71c class="margin-0">endPage</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#67d32cbc-ce6d-4fe2-b43a-ef2d25b99d6d class="margin-0">volume</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#d008b1b5-bd2e-4481-b5c6-595d2155ce15 class="margin-0">year</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#608b4c00-5879-46a2-a759-785cbb329e0e class="margin-0">journal</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3fe9a64b-d52a-402f-9533-1524da2ee014 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4d151e6d-1f53-4401-bb82-f3e5c25c2fc1 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d21db85b-818c-4894-95c4-af2b99b19c7d class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2ba7feb7-a3e8-42a7-b601-3025accedb84 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1a4c10ae-b2ec-4271-8f3b-f773c68db797 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0346889d-c9d2-465c-90ff-54415706c418 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e7b2e6ee-c589-473d-b39e-63ef3189e0f9 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#255d1a0e-77a7-4c2a-8742-54a619b35efa class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8602ea8a-9178-4074-b95d-ed806f90de84 class="margin-0">publicationType</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#559b9cb0-6a20-4738-b511-76bb9b843612 class="margin-0">publisher</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#7f974922-eb7a-44af-a1b6-91e622daccb6 class="margin-0">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#de3e2af0-57d5-4917-baa5-7d4732c50a85 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#52751e94-368c-47db-8f14-ec6737c60a20 class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#76b56aeb-bb29-4d5f-bbec-e69303e629be class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1283d9d3-e129-47de-8693-841f441e1d3e class="margin-0">keywords</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#573524b4-92c9-4cd5-b78b-808ddf3b72e3 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#171e42fb-995f-4d24-896a-70af99335a25 class="margin-0">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2d180621-601a-4771-99ce-67bbe0858731 class="margin-0">presentedAtConference</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#6147e72c-87b1-4025-b65b-b8aea7debf22 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b7e7f02e-23da-4177-9212-a207e57a4c4a class="margin-5">location</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3b81d307-cb0c-467a-948a-603114cd7927 class="margin-5">date</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3d258094-424d-4d90-9974-06fa8c5572b8 class="margin-0">typeOfThesis</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#df23f974-4782-43df-9f4c-dbf50e3d1583 class="margin-0">authors</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#42aa90f3-a2bf-455e-b34d-e4f95a83032d class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#94ee9402-cc15-432b-a859-9c48c224cdde class="margin-10">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b66ef1f-2793-4b90-a1fc-dd1af6a607de class="margin-10">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fcbc7577-afcc-41e2-aff1-edb67afd2f14 class="margin-10">ids(1)</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4f337d1c-168a-41cf-93cd-e0d243aaf714 class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#43047de6-5f4f-4c25-bd01-08b465806fac class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#72ff7d45-0b09-4e65-a4be-71133694780e class="margin-25">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#88cf526a-f7a8-4561-bb29-494acb8b4391 class="margin-30">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#00bfd2ff-075c-4a86-a7ec-a93e69d0d44a class="margin-25">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7f59d388-a148-4620-a551-507465e555a9 class="margin-30">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7ccd8e24-0a2a-4b25-a3ae-0fd2ca5c99d3 class="margin-25">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f080837e-fb16-4de2-b7d3-3a8d52c91f3e class="margin-30">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7eca148f-0c9a-49e2-9ebe-036ab6e3c740 class="margin-10">listingRank</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2d8c8337-e88b-4fc9-b500-6e3c41f491ed class="margin-10">correspondingAuthor</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a4ae57ae-cb9b-4ddc-bda7-98ef5aef2020 class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d66e15a-1f87-4718-9d51-b69f2f9f07b0 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="34a8c944-a5dd-4276-93dc-7819fef8d67c"></a>1.1.2.5.3.1 Field **name**

##### 1.1.2.5.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image203.png?raw=true)

##### 1.1.2.5.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="d3ef9907-13f3-4286-a25e-48a284737e17"></a>1.1.2.5.3.2 Field **documentType**

##### 1.1.2.5.3.2.1 **documentType** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image204.png?raw=true)

##### 1.1.2.5.3.2.2 **documentType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>documentType</td></tr><tr><td>Technical name</td><td>documentType</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Bibliographie, Editorial, Letter to the Editor, Quellenedition, Review, Rezension, Wissenschaftlicher Artikel, Sonstiger Dokumenttyp</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="27448d6a-260e-4651-ba0e-d515f116f5d5"></a>1.1.2.5.3.3 Field **abstract**

##### 1.1.2.5.3.3.1 **abstract** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image205.png?raw=true)

##### 1.1.2.5.3.3.2 **abstract** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>abstract</td></tr><tr><td>Technical name</td><td>abstract</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="d4913695-803f-4da0-a06a-3ac327512b2c"></a>1.1.2.5.3.4 Field **ids**

##### 1.1.2.5.3.4.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image206.png?raw=true)

##### 1.1.2.5.3.4.2 **ids** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8eb515c5-48b5-49fd-8222-3e0cbbcf0261 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.4.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="8eb515c5-48b5-49fd-8222-3e0cbbcf0261"></a>1.1.2.5.3.5 Field **\[0\]**

##### 1.1.2.5.3.5.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image207.png?raw=true)

##### 1.1.2.5.3.5.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#16fe27db-bdb1-47a8-a9d6-27890b8e652a class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.5.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="16fe27db-bdb1-47a8-a9d6-27890b8e652a"></a>1.1.2.5.3.6 Field **anyOf**

##### 1.1.2.5.3.6.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image208.png?raw=true)

##### 1.1.2.5.3.6.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0a2f1bc8-422f-428a-b5c4-8cc6ab56753c class="margin-NaN">[0]&nbsp;doi</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a4415c9e-8a38-4c8b-bdae-e45c581433cb class="margin-NaN">[1]&nbsp;Scopus&nbsp;EID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#822adadb-d194-42b6-8f9a-b9ee484dee7b class="margin-NaN">[2]&nbsp;WOSut</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#566a79f9-90a5-4bb0-8ce7-76418900bca9 class="margin-NaN">[3]&nbsp;PMID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#741e088d-d217-47b9-a3f1-de2627ee3448 class="margin-NaN">[4]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.6.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="0a2f1bc8-422f-428a-b5c4-8cc6ab56753c"></a>1.1.2.5.3.7 Field **\[0\] doi**

##### 1.1.2.5.3.7.1 **\[0\] doi** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image209.png?raw=true)

##### 1.1.2.5.3.7.2 **\[0\] doi** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#88a6aa0d-1970-4fa6-a67d-129062bdcdc9 class="margin-NaN">doi</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.7.3 **\[0\] doi** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>doi</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="88a6aa0d-1970-4fa6-a67d-129062bdcdc9"></a>1.1.2.5.3.8 Field **doi**

##### 1.1.2.5.3.8.1 **doi** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image210.png?raw=true)

##### 1.1.2.5.3.8.2 **doi** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doi</td></tr><tr><td>Technical name</td><td>doi</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a4415c9e-8a38-4c8b-bdae-e45c581433cb"></a>1.1.2.5.3.9 Field **\[1\] Scopus EID**

##### 1.1.2.5.3.9.1 **\[1\] Scopus EID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image211.png?raw=true)

##### 1.1.2.5.3.9.2 **\[1\] Scopus EID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#894bdba5-9de2-4088-9446-13c376c5830c class="margin-NaN">Scopus&nbsp;EID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.9.3 **\[1\] Scopus EID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>Scopus EID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="894bdba5-9de2-4088-9446-13c376c5830c"></a>1.1.2.5.3.10 Field **Scopus EID**

##### 1.1.2.5.3.10.1 **Scopus EID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image212.png?raw=true)

##### 1.1.2.5.3.10.2 **Scopus EID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Scopus EID</td></tr><tr><td>Technical name</td><td>scopusEID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="822adadb-d194-42b6-8f9a-b9ee484dee7b"></a>1.1.2.5.3.11 Field **\[2\] WOSut**

##### 1.1.2.5.3.11.1 **\[2\] WOSut** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image213.png?raw=true)

##### 1.1.2.5.3.11.2 **\[2\] WOSut** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cb3d1e0c-a4f1-4dfd-9b41-cb421065b47e class="margin-NaN">WOSut</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.11.3 **\[2\] WOSut** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>WOSut</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="cb3d1e0c-a4f1-4dfd-9b41-cb421065b47e"></a>1.1.2.5.3.12 Field **WOSut**

##### 1.1.2.5.3.12.1 **WOSut** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image214.png?raw=true)

##### 1.1.2.5.3.12.2 **WOSut** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>WOSut</td></tr><tr><td>Technical name</td><td>WOSut</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="566a79f9-90a5-4bb0-8ce7-76418900bca9"></a>1.1.2.5.3.13 Field **\[3\] PMID**

##### 1.1.2.5.3.13.1 **\[3\] PMID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image215.png?raw=true)

##### 1.1.2.5.3.13.2 **\[3\] PMID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#805e57e1-3a64-4706-b096-7cef272f072e class="margin-NaN">PMID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.13.3 **\[3\] PMID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>PMID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="805e57e1-3a64-4706-b096-7cef272f072e"></a>1.1.2.5.3.14 Field **PMID**

##### 1.1.2.5.3.14.1 **PMID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image216.png?raw=true)

##### 1.1.2.5.3.14.2 **PMID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>PMID</td></tr><tr><td>Technical name</td><td>PMID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="741e088d-d217-47b9-a3f1-de2627ee3448"></a>1.1.2.5.3.15 Field **\[4\] anyOtherID**

##### 1.1.2.5.3.15.1 **\[4\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image217.png?raw=true)

##### 1.1.2.5.3.15.2 **\[4\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e1750472-600c-42b7-a26a-fe9906c88a85 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.15.3 **\[4\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="e1750472-600c-42b7-a26a-fe9906c88a85"></a>1.1.2.5.3.16 Field **anyOtherID**

##### 1.1.2.5.3.16.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image218.png?raw=true)

##### 1.1.2.5.3.16.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="d7838924-06bf-4526-ba8a-379fbe876e51"></a>1.1.2.5.3.17 Field **startPage**

##### 1.1.2.5.3.17.1 **startPage** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image219.png?raw=true)

##### 1.1.2.5.3.17.2 **startPage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>startPage</td></tr><tr><td>Technical name</td><td>startPage</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="a935f6a7-020e-4ec8-8d2f-c078ab2aa71c"></a>1.1.2.5.3.18 Field **endPage**

##### 1.1.2.5.3.18.1 **endPage** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image220.png?raw=true)

##### 1.1.2.5.3.18.2 **endPage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>endPage</td></tr><tr><td>Technical name</td><td>endPage</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="67d32cbc-ce6d-4fe2-b43a-ef2d25b99d6d"></a>1.1.2.5.3.19 Field **volume**

##### 1.1.2.5.3.19.1 **volume** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image221.png?raw=true)

##### 1.1.2.5.3.19.2 **volume** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>volume</td></tr><tr><td>Technical name</td><td>volume</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="d008b1b5-bd2e-4481-b5c6-595d2155ce15"></a>1.1.2.5.3.20 Field **year**

##### 1.1.2.5.3.20.1 **year** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image222.png?raw=true)

##### 1.1.2.5.3.20.2 **year** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>year</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr></tbody></table>

### <a id="608b4c00-5879-46a2-a759-785cbb329e0e"></a>1.1.2.5.3.21 Field **journal**

##### 1.1.2.5.3.21.1 **journal** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image223.png?raw=true)

##### 1.1.2.5.3.21.2 **journal** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3fe9a64b-d52a-402f-9533-1524da2ee014 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4d151e6d-1f53-4401-bb82-f3e5c25c2fc1 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.21.3 **journal** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>journal</td></tr><tr><td>Technical name</td><td>journal</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="3fe9a64b-d52a-402f-9533-1524da2ee014"></a>1.1.2.5.3.22 Field **name**

##### 1.1.2.5.3.22.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image224.png?raw=true)

##### 1.1.2.5.3.22.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="4d151e6d-1f53-4401-bb82-f3e5c25c2fc1"></a>1.1.2.5.3.23 Field **ids**

##### 1.1.2.5.3.23.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image225.png?raw=true)

##### 1.1.2.5.3.23.2 **ids** Hierarchy

Parent field: **journal**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d21db85b-818c-4894-95c4-af2b99b19c7d class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.23.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="d21db85b-818c-4894-95c4-af2b99b19c7d"></a>1.1.2.5.3.24 Field **\[0\]**

##### 1.1.2.5.3.24.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image226.png?raw=true)

##### 1.1.2.5.3.24.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2ba7feb7-a3e8-42a7-b601-3025accedb84 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.24.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="2ba7feb7-a3e8-42a7-b601-3025accedb84"></a>1.1.2.5.3.25 Field **anyOf**

##### 1.1.2.5.3.25.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image227.png?raw=true)

##### 1.1.2.5.3.25.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1a4c10ae-b2ec-4271-8f3b-f773c68db797 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e7b2e6ee-c589-473d-b39e-63ef3189e0f9 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.25.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="1a4c10ae-b2ec-4271-8f3b-f773c68db797"></a>1.1.2.5.3.26 Field **\[0\] houseId**

##### 1.1.2.5.3.26.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image228.png?raw=true)

##### 1.1.2.5.3.26.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0346889d-c9d2-465c-90ff-54415706c418 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.26.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="0346889d-c9d2-465c-90ff-54415706c418"></a>1.1.2.5.3.27 Field **houseId**

##### 1.1.2.5.3.27.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image229.png?raw=true)

##### 1.1.2.5.3.27.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="e7b2e6ee-c589-473d-b39e-63ef3189e0f9"></a>1.1.2.5.3.28 Field **\[1\] anyOtherID**

##### 1.1.2.5.3.28.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image230.png?raw=true)

##### 1.1.2.5.3.28.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#255d1a0e-77a7-4c2a-8742-54a619b35efa class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.28.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="255d1a0e-77a7-4c2a-8742-54a619b35efa"></a>1.1.2.5.3.29 Field **anyOtherID**

##### 1.1.2.5.3.29.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image231.png?raw=true)

##### 1.1.2.5.3.29.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="8602ea8a-9178-4074-b95d-ed806f90de84"></a>1.1.2.5.3.30 Field **publicationType**

##### 1.1.2.5.3.30.1 **publicationType** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image232.png?raw=true)

##### 1.1.2.5.3.30.2 **publicationType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publicationType</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Buch, Artikel, Konferenzbeitrag, Software, Herausgeberschaft eines Sonderhefts einer Zeitschrift, Forschungsdaten, Beitrag in nicht-wissenschaftlichen Medien, Beitrag in wissenschaftlichen Blogs, Arbeitspapier/Forschungsbericht, Integrierende Ressource, Sonstiger Publikationstyp</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="559b9cb0-6a20-4738-b511-76bb9b843612"></a>1.1.2.5.3.31 Field **publisher**

##### 1.1.2.5.3.31.1 **publisher** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image233.png?raw=true)

##### 1.1.2.5.3.31.2 **publisher** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publisher</td></tr><tr><td>Technical name</td><td>publisher</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="7f974922-eb7a-44af-a1b6-91e622daccb6"></a>1.1.2.5.3.32 Field **subjects**

##### 1.1.2.5.3.32.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image234.png?raw=true)

##### 1.1.2.5.3.32.2 **subjects** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#de3e2af0-57d5-4917-baa5-7d4732c50a85 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.32.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="de3e2af0-57d5-4917-baa5-7d4732c50a85"></a>1.1.2.5.3.33 Field **\[0\]**

##### 1.1.2.5.3.33.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image235.png?raw=true)

##### 1.1.2.5.3.33.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="52751e94-368c-47db-8f14-ec6737c60a20"></a>1.1.2.5.3.34 Field **disciplinaryResearchAreas**

##### 1.1.2.5.3.34.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image236.png?raw=true)

##### 1.1.2.5.3.34.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#76b56aeb-bb29-4d5f-bbec-e69303e629be class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.34.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="76b56aeb-bb29-4d5f-bbec-e69303e629be"></a>1.1.2.5.3.35 Field **\[0\]**

##### 1.1.2.5.3.35.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image237.png?raw=true)

##### 1.1.2.5.3.35.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="1283d9d3-e129-47de-8693-841f441e1d3e"></a>1.1.2.5.3.36 Field **keywords**

##### 1.1.2.5.3.36.1 **keywords** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image238.png?raw=true)

##### 1.1.2.5.3.36.2 **keywords** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#573524b4-92c9-4cd5-b78b-808ddf3b72e3 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.36.3 **keywords** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>keywords</td></tr><tr><td>Technical name</td><td>keywords</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="573524b4-92c9-4cd5-b78b-808ddf3b72e3"></a>1.1.2.5.3.37 Field **\[0\]**

##### 1.1.2.5.3.37.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image239.png?raw=true)

##### 1.1.2.5.3.37.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="171e42fb-995f-4d24-896a-70af99335a25"></a>1.1.2.5.3.38 Field **organisationalUnit**

##### 1.1.2.5.3.38.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image240.png?raw=true)

##### 1.1.2.5.3.38.2 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="2d180621-601a-4771-99ce-67bbe0858731"></a>1.1.2.5.3.39 Field **presentedAtConference**

##### 1.1.2.5.3.39.1 **presentedAtConference** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image241.png?raw=true)

##### 1.1.2.5.3.39.2 **presentedAtConference** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6147e72c-87b1-4025-b65b-b8aea7debf22 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b7e7f02e-23da-4177-9212-a207e57a4c4a class="margin-NaN">location</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3b81d307-cb0c-467a-948a-603114cd7927 class="margin-NaN">date</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.39.3 **presentedAtConference** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>presentedAtConference</td></tr><tr><td>Technical name</td><td>presentedAtConference</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="6147e72c-87b1-4025-b65b-b8aea7debf22"></a>1.1.2.5.3.40 Field **name**

##### 1.1.2.5.3.40.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image242.png?raw=true)

##### 1.1.2.5.3.40.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="b7e7f02e-23da-4177-9212-a207e57a4c4a"></a>1.1.2.5.3.41 Field **location**

##### 1.1.2.5.3.41.1 **location** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image243.png?raw=true)

##### 1.1.2.5.3.41.2 **location** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>location</td></tr><tr><td>Technical name</td><td>location</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="3b81d307-cb0c-467a-948a-603114cd7927"></a>1.1.2.5.3.42 Field **date**

##### 1.1.2.5.3.42.1 **date** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image244.png?raw=true)

##### 1.1.2.5.3.42.2 **date** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>date</td></tr><tr><td>Technical name</td><td>date</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr></tbody></table>

### <a id="3d258094-424d-4d90-9974-06fa8c5572b8"></a>1.1.2.5.3.43 Field **typeOfThesis**

##### 1.1.2.5.3.43.1 **typeOfThesis** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image245.png?raw=true)

##### 1.1.2.5.3.43.2 **typeOfThesis** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>typeOfThesis</td></tr><tr><td>Technical name</td><td>typeOfThesis</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>dissertation,habilitation</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="df23f974-4782-43df-9f4c-dbf50e3d1583"></a>1.1.2.5.3.44 Field **authors**

##### 1.1.2.5.3.44.1 **authors** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image246.png?raw=true)

##### 1.1.2.5.3.44.2 **authors** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#42aa90f3-a2bf-455e-b34d-e4f95a83032d class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.44.3 **authors** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>authors</td></tr><tr><td>Technical name</td><td>authors</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="42aa90f3-a2bf-455e-b34d-e4f95a83032d"></a>1.1.2.5.3.45 Field **\[0\]**

##### 1.1.2.5.3.45.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image247.png?raw=true)

##### 1.1.2.5.3.45.2 **\[0\]** Hierarchy

Parent field: **authors**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#94ee9402-cc15-432b-a859-9c48c224cdde class="margin-NaN">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b66ef1f-2793-4b90-a1fc-dd1af6a607de class="margin-NaN">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fcbc7577-afcc-41e2-aff1-edb67afd2f14 class="margin-NaN">ids(1)</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7eca148f-0c9a-49e2-9ebe-036ab6e3c740 class="margin-NaN">listingRank</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2d8c8337-e88b-4fc9-b500-6e3c41f491ed class="margin-NaN">correspondingAuthor</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.45.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="94ee9402-cc15-432b-a859-9c48c224cdde"></a>1.1.2.5.3.46 Field **firstName**

##### 1.1.2.5.3.46.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image248.png?raw=true)

##### 1.1.2.5.3.46.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="9b66ef1f-2793-4b90-a1fc-dd1af6a607de"></a>1.1.2.5.3.47 Field **lastName**

##### 1.1.2.5.3.47.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image249.png?raw=true)

##### 1.1.2.5.3.47.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="fcbc7577-afcc-41e2-aff1-edb67afd2f14"></a>1.1.2.5.3.48 Field **ids(1)**

##### 1.1.2.5.3.48.1 **ids(1)** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image250.png?raw=true)

##### 1.1.2.5.3.48.2 **ids(1)** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#4f337d1c-168a-41cf-93cd-e0d243aaf714 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.48.3 **ids(1)** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids(1)</td></tr><tr><td>Technical name</td><td>ids(1)</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="4f337d1c-168a-41cf-93cd-e0d243aaf714"></a>1.1.2.5.3.49 Field **\[0\]**

##### 1.1.2.5.3.49.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image251.png?raw=true)

##### 1.1.2.5.3.49.2 **\[0\]** Hierarchy

Parent field: **ids(1)**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#43047de6-5f4f-4c25-bd01-08b465806fac class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.49.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="43047de6-5f4f-4c25-bd01-08b465806fac"></a>1.1.2.5.3.50 Field **anyOf**

##### 1.1.2.5.3.50.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image252.png?raw=true)

##### 1.1.2.5.3.50.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#72ff7d45-0b09-4e65-a4be-71133694780e class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#00bfd2ff-075c-4a86-a7ec-a93e69d0d44a class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7ccd8e24-0a2a-4b25-a3ae-0fd2ca5c99d3 class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.50.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="72ff7d45-0b09-4e65-a4be-71133694780e"></a>1.1.2.5.3.51 Field **\[0\] houseID**

##### 1.1.2.5.3.51.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image253.png?raw=true)

##### 1.1.2.5.3.51.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#88cf526a-f7a8-4561-bb29-494acb8b4391 class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.51.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="88cf526a-f7a8-4561-bb29-494acb8b4391"></a>1.1.2.5.3.52 Field **houseID**

##### 1.1.2.5.3.52.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image254.png?raw=true)

##### 1.1.2.5.3.52.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="00bfd2ff-075c-4a86-a7ec-a93e69d0d44a"></a>1.1.2.5.3.53 Field **\[1\] ORCiD**

##### 1.1.2.5.3.53.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image255.png?raw=true)

##### 1.1.2.5.3.53.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7f59d388-a148-4620-a551-507465e555a9 class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.53.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="7f59d388-a148-4620-a551-507465e555a9"></a>1.1.2.5.3.54 Field **ORCiD**

##### 1.1.2.5.3.54.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image256.png?raw=true)

##### 1.1.2.5.3.54.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="7ccd8e24-0a2a-4b25-a3ae-0fd2ca5c99d3"></a>1.1.2.5.3.55 Field **\[2\] anyOtherID**

##### 1.1.2.5.3.55.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image257.png?raw=true)

##### 1.1.2.5.3.55.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f080837e-fb16-4de2-b7d3-3a8d52c91f3e class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.55.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="f080837e-fb16-4de2-b7d3-3a8d52c91f3e"></a>1.1.2.5.3.56 Field **id**

##### 1.1.2.5.3.56.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image258.png?raw=true)

##### 1.1.2.5.3.56.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="7eca148f-0c9a-49e2-9ebe-036ab6e3c740"></a>1.1.2.5.3.57 Field **listingRank**

##### 1.1.2.5.3.57.1 **listingRank** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image259.png?raw=true)

##### 1.1.2.5.3.57.2 **listingRank** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>listingRank</td></tr><tr><td>Technical name</td><td>listingRank</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Min value</td><td>1</td></tr><tr><td>Default</td><td>1</td></tr></tbody></table>

### <a id="2d8c8337-e88b-4fc9-b500-6e3c41f491ed"></a>1.1.2.5.3.58 Field **correspondingAuthor**

##### 1.1.2.5.3.58.1 **correspondingAuthor** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image260.png?raw=true)

##### 1.1.2.5.3.58.2 **correspondingAuthor** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>correspondingAuthor</td></tr><tr><td>Technical name</td><td>correspondingAuthor</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr></tbody></table>

### <a id="a4ae57ae-cb9b-4ddc-bda7-98ef5aef2020"></a>1.1.2.5.3.59 Field **interDisciplinaryResearchAreas**

##### 1.1.2.5.3.59.1 **interDisciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image261.png?raw=true)

##### 1.1.2.5.3.59.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9d66e15a-1f87-4718-9d51-b69f2f9f07b0 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.5.3.59.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="9d66e15a-1f87-4718-9d51-b69f2f9f07b0"></a>1.1.2.5.3.60 Field **\[0\]**

##### 1.1.2.5.3.60.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image262.png?raw=true)

##### 1.1.2.5.3.60.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 1.1.2.5.4 **Publication** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "Publication",
    "properties": {
        "name": {
            "type": "string",
            "title": "name"
        },
        "documentType": {
            "type": "string",
            "title": "documentType",
            "enum": [
                "Bibliographie",
                "    Editorial",
                "    Letter to the Editor",
                "    Quellenedition",
                "    Review",
                "    Rezension",
                "    Wissenschaftlicher Artikel",
                "    Sonstiger Dokumenttyp"
            ]
        },
        "abstract": {
            "type": "string",
            "title": "abstract"
        },
        "ids": {
            "type": "array",
            "title": "ids",
            "additionalItems": true,
            "items": {
                "type": "object",
                "additionalProperties": true,
                "anyOf": [
                    {
                        "type": "object",
                        "properties": {
                            "doi": {
                                "type": "string",
                                "title": "doi"
                            }
                        },
                        "additionalProperties": true
                    },
                    {
                        "type": "object",
                        "properties": {
                            "scopusEID": {
                                "type": "string",
                                "title": "Scopus EID"
                            }
                        }
                    },
                    {
                        "type": "object",
                        "properties": {
                            "WOSut": {
                                "type": "string",
                                "title": "WOSut"
                            }
                        }
                    },
                    {
                        "type": "object",
                        "properties": {
                            "PMID": {
                                "type": "string",
                                "title": "PMID"
                            }
                        }
                    },
                    {
                        "type": "object",
                        "properties": {
                            "anyOtherID": {
                                "type": "string",
                                "title": "anyOtherID"
                            }
                        }
                    }
                ]
            }
        },
        "startPage": {
            "type": "string",
            "title": "startPage"
        },
        "endPage": {
            "type": "string",
            "title": "endPage"
        },
        "volume": {
            "type": "string",
            "title": "volume"
        },
        "year": {
            "type": "string",
            "format": "date"
        },
        "journal": {
            "type": "object",
            "title": "journal",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "ids": {
                    "type": "array",
                    "title": "ids",
                    "additionalItems": true,
                    "items": {
                        "type": "object",
                        "additionalProperties": true,
                        "anyOf": [
                            {
                                "type": "object",
                                "properties": {
                                    "houseId": {
                                        "type": "string",
                                        "title": "houseId"
                                    }
                                },
                                "additionalProperties": true
                            },
                            {
                                "type": "object",
                                "properties": {
                                    "anyOtherID": {
                                        "type": "string",
                                        "title": "anyOtherID"
                                    }
                                }
                            }
                        ]
                    }
                }
            },
            "additionalProperties": false,
            "required": [
                "name"
            ]
        },
        "publicationType": {
            "type": "string",
            "enum": [
                "Buch",
                "    Artikel",
                "    Konferenzbeitrag",
                "    Software",
                "    Herausgeberschaft eines Sonderhefts einer Zeitschrift",
                "    Forschungsdaten",
                "    Beitrag in nicht-wissenschaftlichen Medien",
                "    Beitrag in wissenschaftlichen Blogs",
                "    Arbeitspapier/Forschungsbericht",
                "    Integrierende Ressource",
                "    Sonstiger Publikationstyp"
            ]
        },
        "publisher": {
            "type": "string",
            "title": "publisher"
        },
        "subjects": {
            "type": "array",
            "title": "subjects",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "disciplinaryResearchAreas": {
            "type": "array",
            "title": "disciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "keywords": {
            "type": "array",
            "title": "keywords",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "organisationalUnit": {
            "type": "string",
            "title": "organisationalUnit"
        },
        "presentedAtConference": {
            "type": "object",
            "title": "presentedAtConference",
            "properties": {
                "name": {
                    "type": "string",
                    "title": "name"
                },
                "location": {
                    "type": "string",
                    "title": "location"
                },
                "date": {
                    "type": "string",
                    "title": "date",
                    "format": "date"
                }
            },
            "additionalProperties": false,
            "required": [
                "name"
            ]
        },
        "typeOfThesis": {
            "type": "string",
            "title": "typeOfThesis",
            "enum": [
                "dissertation",
                "habilitation"
            ]
        },
        "authors": {
            "type": "array",
            "title": "authors",
            "additionalItems": true,
            "items": {
                "type": "object",
                "properties": {
                    "firstName": {
                        "type": "string",
                        "title": "firstName"
                    },
                    "lastName": {
                        "type": "string",
                        "title": "lastName"
                    },
                    "ids(1)": {
                        "type": "array",
                        "title": "ids(1)",
                        "additionalItems": true,
                        "items": {
                            "type": "object",
                            "additionalProperties": true,
                            "anyOf": [
                                {
                                    "type": "object",
                                    "properties": {
                                        "houseID": {
                                            "type": "string",
                                            "title": "houseID"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "orcid": {
                                            "type": "string",
                                            "title": "ORCiD"
                                        }
                                    },
                                    "additionalProperties": true
                                },
                                {
                                    "type": "object",
                                    "properties": {
                                        "id": {
                                            "type": "string"
                                        }
                                    }
                                }
                            ]
                        }
                    },
                    "listingRank": {
                        "type": "number",
                        "title": "listingRank",
                        "minimum": 1,
                        "default": 1
                    },
                    "correspondingAuthor": {
                        "type": "boolean",
                        "title": "correspondingAuthor"
                    }
                },
                "additionalProperties": false,
                "required": [
                    "firstName",
                    "lastName"
                ]
            }
        },
        "interDisciplinaryResearchAreas": {
            "type": "array",
            "title": "interDisciplinaryResearchAreas",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        }
    },
    "additionalProperties": false,
    "required": [
        "name",
        "documentType"
    ]
}
```

##### 1.1.2.5.5 **Publication** JSON data

```
{
    "name": "Lorem",
    "documentType": "    Sonstiger Dokumenttyp",
    "abstract": "Lorem",
    "ids": [
        {
            "doi": "Lorem"
        }
    ],
    "startPage": "Lorem",
    "endPage": "Lorem",
    "volume": "Lorem",
    "year": "2011-06-14",
    "journal": {
        "name": "Lorem",
        "ids": [
            {
                "houseId": "Lorem"
            }
        ]
    },
    "publicationType": "    Sonstiger Publikationstyp",
    "publisher": "Lorem",
    "subjects": [
        "Lorem"
    ],
    "disciplinaryResearchAreas": [
        "Lorem"
    ],
    "keywords": [
        "Lorem"
    ],
    "organisationalUnit": "Lorem",
    "presentedAtConference": {
        "name": "Lorem",
        "location": "Lorem",
        "date": "2011-06-14"
    },
    "typeOfThesis": "habilitation",
    "authors": [
        {
            "firstName": "Lorem",
            "lastName": "Lorem",
            "ids(1)": [
                {
                    "houseID": "Lorem"
                }
            ],
            "listingRank": 1,
            "correspondingAuthor": true
        }
    ],
    "interDisciplinaryResearchAreas": [
        "Lorem"
    ]
}
```

### <a id="edges"></a>