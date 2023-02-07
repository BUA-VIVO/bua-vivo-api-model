     

### <a id="documentation-body"></a>

![Bua VIVO image](buavivologo.png?raw=true)

JSON Physical Model
-------------------

#### Schema for:

Model name: BUA API MODEL

Author: Rolf Guescini, Florian Kotschka

Version: 1

File name: JSON\_model\_BUA.hck.json


Printed On: Mon Feb 06 2023 16:04:13 GMT+0100 (Central European Standard Time)

Created with: [Hackolade](https://hackolade.com/) - Polyglot data modeling for NoSQL databases, storage formats, REST APIs, and JSON in RDBMS

### <a id="contents"></a>

*   [Table of Contents](#contents)
*   [1\. Model](#model)
*   [2\. Groups](#containers)
    *   [2.1 Undefined Group](#no-bucket)
        
        [2.1.2. Documents](#no-bucket-children)
        
        [2.1.2.1 BUA DATA API](#cdb639e2-f7af-4727-bb8c-bb53d7297535)
        
        [2.1.2.2 Event](#8f9b034b-6269-4a15-bd00-437bdc962d73)
        
        [2.1.2.3 Person](#56b58da0-bebc-41b1-9ce3-6472881e4247)
        
        [2.1.2.4 Project](#4f72014b-c421-4a4c-8aa8-a56403100ac5)
        
        [2.1.2.5 Publication](#482b0df2-d80e-4871-89e5-ea8b028eabb4)
        
*   [3\. Relationships](#relationships)
    *   [3.1 project\_role](#87f1244c-f6c8-4812-b1af-02f716d398f8)
    *   [3.2 publication\_author](#9776efff-92fd-4f84-b454-c60737bdb4df)

### <a id="model"></a>

##### 1\. Model

##### 1.1 Model **BUA API MODEL**

##### 1.1.1 **BUA API MODEL** Entity Relationship Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image2.png?raw=true)

##### 1.1.2 **BUA API MODEL** Properties

##### 1.1.2.1 **Details** tab

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td><span>Model name</span></td><td>BUA API MODEL</td></tr><tr><td><span>Technical name</span></td><td>bua_api_model</td></tr><tr><td><span>Author</span></td><td>Rolf Guescini, Florian Kotschka</td></tr><tr><td><span>Target</span></td><td>JSON</td></tr><tr><td><span>Draft version</span></td><td>2020-12</td></tr><tr><td><span>Version</span></td><td>1</td></tr><tr><td><span>Lineage capture</span></td><td></td></tr></tbody></table>

##### 1.1.3 **BUA API MODEL** DB Definitions

### <a id="containers"></a>

##### 2\. Groups

### <a id="no-bucket"></a>2.1 Group **Undefined Group**

![Hackolade image](BUA%20API%20MODEL%20documentation/image3.png?raw=true)

##### 2.1.1 **Undefined Group** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Group name</td><td>Undefined Group</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="no-bucket-children"></a>2.1.2 **Undefined Group** Documents

### <a id="cdb639e2-f7af-4727-bb8c-bb53d7297535"></a>2.1.2.1 Document **BUA DATA API**

##### 2.1.2.1.1 **BUA DATA API** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image4.png?raw=true)

##### 2.1.2.1.2 **BUA DATA API** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>BUA DATA API</td></tr><tr><td>Technical name</td><td>bua_data_api</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td>bua_data_api</td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3 **BUA DATA API** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#00b13b26-f99e-440c-ace3-560643002b68 class="margin-0">identification</a></td><td class="no-break-word">object</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e5a80aaf-a215-4cf2-8758-2a935ade410a class="margin-5">organizationId</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a143ef14-6fa4-4ed8-8f2c-b28e2ba40e8e class="margin-5">authorizationToken</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#01d15cd9-379c-4188-b397-7e2b30cdba31 class="margin-0">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6338bc98-b918-454c-b6e3-8b56c8342fdb class="margin-0">data</a></td><td class="no-break-word">array</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#720710c2-805f-4d07-986f-b129c33d76fa class="margin-5">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#114d1a3b-0df0-4e6f-a43a-9d88828d34da class="margin-10">[0]&nbsp;person</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b592121f-5ab5-4b71-8991-3495339bf424 class="margin-15">[0]&nbsp;person</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#54934db6-db54-4abe-bd65-f8a657a2dcc8 class="margin-10">[1]&nbsp;publication</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3a903297-22fc-4990-9b9c-8985705d29bc class="margin-15">[0]&nbsp;publication</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcfffd6e-6a02-49cf-9279-64489740b550 class="margin-10">[2]&nbsp;project</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f785eb55-c6ca-4f78-be5f-e6445743ed5a class="margin-15">[0]&nbsp;project</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#82927f30-272b-4e73-b69d-2fbad4c6c295 class="margin-10">[3]&nbsp;event</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d6b0423b-d51b-4909-b0bf-a410b1bf0b56 class="margin-15">[0]&nbsp;event</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="00b13b26-f99e-440c-ace3-560643002b68"></a>2.1.2.1.3.1 Field **identification**

##### 2.1.2.1.3.1.1 **identification** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image5.png?raw=true)

##### 2.1.2.1.3.1.2 **identification** Hierarchy

Parent field: **BUA DATA API**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e5a80aaf-a215-4cf2-8758-2a935ade410a class="margin-NaN">organizationId</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a143ef14-6fa4-4ed8-8f2c-b28e2ba40e8e class="margin-NaN">authorizationToken</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.1.3 **identification** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>identification</td></tr><tr><td>Technical name</td><td>identification</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="e5a80aaf-a215-4cf2-8758-2a935ade410a"></a>2.1.2.1.3.2 Field **organizationId**

##### 2.1.2.1.3.2.1 **organizationId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image6.png?raw=true)

##### 2.1.2.1.3.2.2 **organizationId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organizationId</td></tr><tr><td>Technical name</td><td>organizationId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="a143ef14-6fa4-4ed8-8f2c-b28e2ba40e8e"></a>2.1.2.1.3.3 Field **authorizationToken**

##### 2.1.2.1.3.3.1 **authorizationToken** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image7.png?raw=true)

##### 2.1.2.1.3.3.2 **authorizationToken** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>authorizationToken</td></tr><tr><td>Technical name</td><td>authorizationToken</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="01d15cd9-379c-4188-b397-7e2b30cdba31"></a>2.1.2.1.3.4 Field **type**

##### 2.1.2.1.3.4.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image8.png?raw=true)

##### 2.1.2.1.3.4.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>publication,person,event,project</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="6338bc98-b918-454c-b6e3-8b56c8342fdb"></a>2.1.2.1.3.5 Field **data**

##### 2.1.2.1.3.5.1 **data** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image9.png?raw=true)

##### 2.1.2.1.3.5.2 **data** Hierarchy

Parent field: **BUA DATA API**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#720710c2-805f-4d07-986f-b129c33d76fa class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.5.3 **data** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>data</td></tr><tr><td>Technical name</td><td>data</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Dependent required</td><td>type</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="720710c2-805f-4d07-986f-b129c33d76fa"></a>2.1.2.1.3.6 Field **anyOf**

##### 2.1.2.1.3.6.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image10.png?raw=true)

##### 2.1.2.1.3.6.2 **anyOf** Hierarchy

Parent field: **data**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#114d1a3b-0df0-4e6f-a43a-9d88828d34da class="margin-NaN">[0]&nbsp;person</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#54934db6-db54-4abe-bd65-f8a657a2dcc8 class="margin-NaN">[1]&nbsp;publication</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcfffd6e-6a02-49cf-9279-64489740b550 class="margin-NaN">[2]&nbsp;project</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#82927f30-272b-4e73-b69d-2fbad4c6c295 class="margin-NaN">[3]&nbsp;event</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.6.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"><p>Must contain the object specified in the type attribute</p></div></td></tr></tbody></table>

### <a id="114d1a3b-0df0-4e6f-a43a-9d88828d34da"></a>2.1.2.1.3.7 Field **\[0\] person**

##### 2.1.2.1.3.7.1 **\[0\] person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image11.png?raw=true)

##### 2.1.2.1.3.7.2 **\[0\] person** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b592121f-5ab5-4b71-8991-3495339bf424 class="margin-NaN">[0]&nbsp;person</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.7.3 **\[0\] person** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="b592121f-5ab5-4b71-8991-3495339bf424"></a>2.1.2.1.3.8 Field **\[0\] person**

##### 2.1.2.1.3.8.1 **\[0\] person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image12.png?raw=true)

##### 2.1.2.1.3.8.2 **\[0\] person** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Foreign collection</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr></tbody></table>

### <a id="54934db6-db54-4abe-bd65-f8a657a2dcc8"></a>2.1.2.1.3.9 Field **\[1\] publication**

##### 2.1.2.1.3.9.1 **\[1\] publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image13.png?raw=true)

##### 2.1.2.1.3.9.2 **\[1\] publication** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3a903297-22fc-4990-9b9c-8985705d29bc class="margin-NaN">[0]&nbsp;publication</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.9.3 **\[1\] publication** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="3a903297-22fc-4990-9b9c-8985705d29bc"></a>2.1.2.1.3.10 Field **\[0\] publication**

##### 2.1.2.1.3.10.1 **\[0\] publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image14.png?raw=true)

##### 2.1.2.1.3.10.2 **\[0\] publication** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Foreign collection</td><td><a href=#482b0df2-d80e-4871-89e5-ea8b028eabb4>Publication</a></td></tr></tbody></table>

### <a id="bcfffd6e-6a02-49cf-9279-64489740b550"></a>2.1.2.1.3.11 Field **\[2\] project**

##### 2.1.2.1.3.11.1 **\[2\] project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image15.png?raw=true)

##### 2.1.2.1.3.11.2 **\[2\] project** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f785eb55-c6ca-4f78-be5f-e6445743ed5a class="margin-NaN">[0]&nbsp;project</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.11.3 **\[2\] project** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f785eb55-c6ca-4f78-be5f-e6445743ed5a"></a>2.1.2.1.3.12 Field **\[0\] project**

##### 2.1.2.1.3.12.1 **\[0\] project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image16.png?raw=true)

##### 2.1.2.1.3.12.2 **\[0\] project** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Foreign collection</td><td><a href=#4f72014b-c421-4a4c-8aa8-a56403100ac5>Project</a></td></tr></tbody></table>

### <a id="82927f30-272b-4e73-b69d-2fbad4c6c295"></a>2.1.2.1.3.13 Field **\[3\] event**

##### 2.1.2.1.3.13.1 **\[3\] event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image17.png?raw=true)

##### 2.1.2.1.3.13.2 **\[3\] event** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d6b0423b-d51b-4909-b0bf-a410b1bf0b56 class="margin-NaN">[0]&nbsp;event</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.13.3 **\[3\] event** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="d6b0423b-d51b-4909-b0bf-a410b1bf0b56"></a>2.1.2.1.3.14 Field **\[0\] event**

##### 2.1.2.1.3.14.1 **\[0\] event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image18.png?raw=true)

##### 2.1.2.1.3.14.2 **\[0\] event** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Foreign collection</td><td><a href=#8f9b034b-6269-4a15-bd00-437bdc962d73>Event</a></td></tr></tbody></table>

##### 2.1.2.1.4 **BUA DATA API** JSON Schema

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
            "type"
        ]
    }
}
```

##### 2.1.2.1.5 **BUA DATA API** JSON data

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

### <a id="8f9b034b-6269-4a15-bd00-437bdc962d73"></a>2.1.2.2 Document **Event**

##### 2.1.2.2.1 **Event** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image19.png?raw=true)

##### 2.1.2.2.2 **Event** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Event</td></tr><tr><td>Technical name</td><td>event</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3 **Event** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5541aa5e-765d-4a64-b5a7-061e3306f6bb class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1f6a3891-a19d-4082-b637-4bb12cec19b1 class="margin-0">description</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#eac941cb-354f-42e9-afc0-be65fa7f9027 class="margin-0">date</a></td><td class="no-break-word">date-time</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Example: 2022-01-25T14:50:00</p></div></td></tr><tr><td><a href=#e0989e92-ca75-4161-a0bf-0221eaafe2fe class="margin-0">type</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#baf9bdc2-2ac2-4385-85ca-954974505641 class="margin-0">contactInfo</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#29fa8430-c835-4853-8793-4233ba0332f9 class="margin-5">address</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6ca4a3a6-66b7-4d0c-8042-c20cfd37db53 class="margin-5">telephone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#59e9af26-f8f5-4b6b-822e-d74a14f27567 class="margin-5">email</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e4632a5a-16ec-4ece-ad81-9a06fba528a0 class="margin-0">partOfEventseries</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7d1541ff-8830-4a83-a374-217aab11616a class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4b3f4f05-163d-4176-aaa9-d423359e11dc class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5bfc6f9-bf92-4a43-83f7-89ac6eb10990 class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c35c1ed3-9cfa-460d-8ba0-0dc228db1fc4 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1457a3a3-3b1a-4ec2-8499-70b169530583 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d3a8e76a-f475-48e5-94f3-91afaa8e405f class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fde19b37-3eca-4283-b4a3-28cdd48abf0d class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#797f3e55-6fd9-4fc9-a8a3-dac04d2f3c81 class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#601dd86e-54bc-4df0-9fea-735f82a3b9a6 class="margin-0">relatedDocuments</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a9e7ece6-67cc-4741-8271-cf7170c5e168 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1c49b2c0-e554-4a44-8160-12cd1bcb938c class="margin-5">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc459737-8fe6-489b-9982-8bae2019c9b0 class="margin-5">uri</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#82927f30-272b-4e73-b69d-2fbad4c6c295 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d6b0423b-d51b-4909-b0bf-a410b1bf0b56 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b9661cd0-49df-4455-811c-19ec49d35441 class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e6b90ca4-4a91-4a08-acb7-4aa76204d85b class="margin-15">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5a0c60d2-d4a0-460a-89b2-f762b047fad0 class="margin-20">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#53e21acd-dcd7-4f96-8933-87cd832e0a92 class="margin-15">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3ba4dd26-a539-41d6-8066-ca832f7f88d9 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5541aa5e-765d-4a64-b5a7-061e3306f6bb"></a>2.1.2.2.3.1 Field **name**

##### 2.1.2.2.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image20.png?raw=true)

##### 2.1.2.2.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="1f6a3891-a19d-4082-b637-4bb12cec19b1"></a>2.1.2.2.3.2 Field **description**

##### 2.1.2.2.3.2.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image21.png?raw=true)

##### 2.1.2.2.3.2.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="eac941cb-354f-42e9-afc0-be65fa7f9027"></a>2.1.2.2.3.3 Field **date**

##### 2.1.2.2.3.3.1 **date** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image22.png?raw=true)

##### 2.1.2.2.3.3.2 **date** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>date</td></tr><tr><td>Technical name</td><td>date</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date-time</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Example: 2022-01-25T14:50:00</p></div></td></tr></tbody></table>

### <a id="e0989e92-ca75-4161-a0bf-0221eaafe2fe"></a>2.1.2.2.3.4 Field **type**

##### 2.1.2.2.3.4.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image23.png?raw=true)

##### 2.1.2.2.3.4.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Competition, Conference, Course, Exhibit, Hearing, Interview, Meeting, Performance, Presentation, VIVO Talk, Workshop,Other</td></tr></tbody></table>

### <a id="baf9bdc2-2ac2-4385-85ca-954974505641"></a>2.1.2.2.3.5 Field **contactInfo**

##### 2.1.2.2.3.5.1 **contactInfo** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image24.png?raw=true)

##### 2.1.2.2.3.5.2 **contactInfo** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#29fa8430-c835-4853-8793-4233ba0332f9 class="margin-NaN">address</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6ca4a3a6-66b7-4d0c-8042-c20cfd37db53 class="margin-NaN">telephone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#59e9af26-f8f5-4b6b-822e-d74a14f27567 class="margin-NaN">email</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.5.3 **contactInfo** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>contactInfo</td></tr><tr><td>Technical name</td><td>contactInfo</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="29fa8430-c835-4853-8793-4233ba0332f9"></a>2.1.2.2.3.6 Field **address**

##### 2.1.2.2.3.6.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image25.png?raw=true)

##### 2.1.2.2.3.6.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="6ca4a3a6-66b7-4d0c-8042-c20cfd37db53"></a>2.1.2.2.3.7 Field **telephone**

##### 2.1.2.2.3.7.1 **telephone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image26.png?raw=true)

##### 2.1.2.2.3.7.2 **telephone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>telephone</td></tr><tr><td>Technical name</td><td>telephone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="59e9af26-f8f5-4b6b-822e-d74a14f27567"></a>2.1.2.2.3.8 Field **email**

##### 2.1.2.2.3.8.1 **email** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image27.png?raw=true)

##### 2.1.2.2.3.8.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td>email</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr></tbody></table>

### <a id="e4632a5a-16ec-4ece-ad81-9a06fba528a0"></a>2.1.2.2.3.9 Field **partOfEventseries**

##### 2.1.2.2.3.9.1 **partOfEventseries** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image28.png?raw=true)

##### 2.1.2.2.3.9.2 **partOfEventseries** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7d1541ff-8830-4a83-a374-217aab11616a class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4b3f4f05-163d-4176-aaa9-d423359e11dc class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.9.3 **partOfEventseries** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>partOfEventseries</td></tr><tr><td>Technical name</td><td>partOfEventseries</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="7d1541ff-8830-4a83-a374-217aab11616a"></a>2.1.2.2.3.10 Field **name**

##### 2.1.2.2.3.10.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image29.png?raw=true)

##### 2.1.2.2.3.10.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="4b3f4f05-163d-4176-aaa9-d423359e11dc"></a>2.1.2.2.3.11 Field **ids**

##### 2.1.2.2.3.11.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image30.png?raw=true)

##### 2.1.2.2.3.11.2 **ids** Hierarchy

Parent field: **partOfEventseries**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c5bfc6f9-bf92-4a43-83f7-89ac6eb10990 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.11.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="c5bfc6f9-bf92-4a43-83f7-89ac6eb10990"></a>2.1.2.2.3.12 Field **\[0\]**

##### 2.1.2.2.3.12.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image31.png?raw=true)

##### 2.1.2.2.3.12.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c35c1ed3-9cfa-460d-8ba0-0dc228db1fc4 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.12.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="c35c1ed3-9cfa-460d-8ba0-0dc228db1fc4"></a>2.1.2.2.3.13 Field **anyOf**

##### 2.1.2.2.3.13.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image32.png?raw=true)

##### 2.1.2.2.3.13.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1457a3a3-3b1a-4ec2-8499-70b169530583 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fde19b37-3eca-4283-b4a3-28cdd48abf0d class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.13.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="1457a3a3-3b1a-4ec2-8499-70b169530583"></a>2.1.2.2.3.14 Field **\[0\] houseId**

##### 2.1.2.2.3.14.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image33.png?raw=true)

##### 2.1.2.2.3.14.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d3a8e76a-f475-48e5-94f3-91afaa8e405f class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.14.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="d3a8e76a-f475-48e5-94f3-91afaa8e405f"></a>2.1.2.2.3.15 Field **houseId**

##### 2.1.2.2.3.15.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image34.png?raw=true)

##### 2.1.2.2.3.15.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Foreign collection</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Foreign field</td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>houseId</a></td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="fde19b37-3eca-4283-b4a3-28cdd48abf0d"></a>2.1.2.2.3.16 Field **\[1\] anyOtherID**

##### 2.1.2.2.3.16.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image35.png?raw=true)

##### 2.1.2.2.3.16.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#797f3e55-6fd9-4fc9-a8a3-dac04d2f3c81 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.16.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="797f3e55-6fd9-4fc9-a8a3-dac04d2f3c81"></a>2.1.2.2.3.17 Field **anyOtherID**

##### 2.1.2.2.3.17.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image36.png?raw=true)

##### 2.1.2.2.3.17.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="601dd86e-54bc-4df0-9fea-735f82a3b9a6"></a>2.1.2.2.3.18 Field **relatedDocuments**

##### 2.1.2.2.3.18.1 **relatedDocuments** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image37.png?raw=true)

##### 2.1.2.2.3.18.2 **relatedDocuments** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a9e7ece6-67cc-4741-8271-cf7170c5e168 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1c49b2c0-e554-4a44-8160-12cd1bcb938c class="margin-NaN">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc459737-8fe6-489b-9982-8bae2019c9b0 class="margin-NaN">uri</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.18.3 **relatedDocuments** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>relatedDocuments</td></tr><tr><td>Technical name</td><td>relatedDocuments</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="a9e7ece6-67cc-4741-8271-cf7170c5e168"></a>2.1.2.2.3.19 Field **name**

##### 2.1.2.2.3.19.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image38.png?raw=true)

##### 2.1.2.2.3.19.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="1c49b2c0-e554-4a44-8160-12cd1bcb938c"></a>2.1.2.2.3.20 Field **abstract**

##### 2.1.2.2.3.20.1 **abstract** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image39.png?raw=true)

##### 2.1.2.2.3.20.2 **abstract** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>abstract</td></tr><tr><td>Technical name</td><td>abstract</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="cc459737-8fe6-489b-9982-8bae2019c9b0"></a>2.1.2.2.3.21 Field **uri**

##### 2.1.2.2.3.21.1 **uri** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image40.png?raw=true)

##### 2.1.2.2.3.21.2 **uri** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uri</td></tr><tr><td>Technical name</td><td>uri</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="82927f30-272b-4e73-b69d-2fbad4c6c295"></a>2.1.2.2.3.22 Field **ids**

##### 2.1.2.2.3.22.1 **ids** Tree Diagram

##### 2.1.2.2.3.22.2 **ids** Hierarchy

Parent field: **Event**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d6b0423b-d51b-4909-b0bf-a410b1bf0b56 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.22.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="d6b0423b-d51b-4909-b0bf-a410b1bf0b56"></a>2.1.2.2.3.23 Field **\[0\]**

##### 2.1.2.2.3.23.1 **\[0\]** Tree Diagram

##### 2.1.2.2.3.23.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b9661cd0-49df-4455-811c-19ec49d35441 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.23.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="b9661cd0-49df-4455-811c-19ec49d35441"></a>2.1.2.2.3.24 Field **anyOf**

##### 2.1.2.2.3.24.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image41.png?raw=true)

##### 2.1.2.2.3.24.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e6b90ca4-4a91-4a08-acb7-4aa76204d85b class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#53e21acd-dcd7-4f96-8933-87cd832e0a92 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.24.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="e6b90ca4-4a91-4a08-acb7-4aa76204d85b"></a>2.1.2.2.3.25 Field **\[0\] houseId**

##### 2.1.2.2.3.25.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image42.png?raw=true)

##### 2.1.2.2.3.25.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5a0c60d2-d4a0-460a-89b2-f762b047fad0 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.25.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="5a0c60d2-d4a0-460a-89b2-f762b047fad0"></a>2.1.2.2.3.26 Field **houseId**

##### 2.1.2.2.3.26.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image43.png?raw=true)

##### 2.1.2.2.3.26.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Foreign collection</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Foreign field</td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>houseId</a></td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="53e21acd-dcd7-4f96-8933-87cd832e0a92"></a>2.1.2.2.3.27 Field **\[1\] anyOtherID**

##### 2.1.2.2.3.27.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image44.png?raw=true)

##### 2.1.2.2.3.27.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3ba4dd26-a539-41d6-8066-ca832f7f88d9 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3.27.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="3ba4dd26-a539-41d6-8066-ca832f7f88d9"></a>2.1.2.2.3.28 Field **anyOtherID**

##### 2.1.2.2.3.28.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image45.png?raw=true)

##### 2.1.2.2.3.28.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 2.1.2.2.4 **Event** JSON Schema

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

##### 2.1.2.2.5 **Event** JSON data

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

### <a id="56b58da0-bebc-41b1-9ce3-6472881e4247"></a>2.1.2.3 Document **Person**

##### 2.1.2.3.1 **Person** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image46.png?raw=true)

##### 2.1.2.3.2 **Person** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Person</td></tr><tr><td>Technical name</td><td>person</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td>bua_person</td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3 **Person** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#660a132f-d776-4a6d-b9cb-b1ad6d88e175 class="margin-0">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#0b2a3bc9-7926-4b44-b8f7-3798bd2a96c8 class="margin-0">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#90acb9c1-4dd9-419d-807f-54413cfa9f05 class="margin-0">middleName</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#3281b95e-3bd9-478a-b1fe-d2a4ea1066d6 class="margin-0">description</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#52243dc3-7056-4b37-95f3-4d2108a19d89 class="margin-0">birthday</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#3f85edd4-56b6-43ff-b5c2-45b604932038 class="margin-0">gender</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#95dc3047-eb11-4fc9-89da-f3cf4bd7a25a class="margin-0">nationality</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#275fd0e2-3084-4124-bff9-3b01b639cd4c class="margin-0">address</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#edc06d05-64ab-4503-a2f2-be469fa12398 class="margin-0">email</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ecec2147-b36b-44ba-9e7b-be0b455f5579 class="margin-0">phone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f63711c8-97a5-40f2-a1f5-4dd485f18a44 class="margin-0">webpages</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5eb984e5-c02d-48df-b616-e01345abab18 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#98f82a8f-f70a-48c1-a917-10cb806b8645 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#38150804-10f9-4016-83fd-9d164ea461b0 class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#49ab42a9-1641-48b0-ad54-b7b4690b687a class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e21eb9b7-1943-467c-9ec8-9751367708a8 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#133278b5-d902-4ca3-8a82-1c57ce54c71a class="margin-0">doctoralEligibility</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#b93b648e-bb34-4b67-a6f2-d12ef64e10d5 class="margin-0">doctoralEligibilityFrom</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e14a569d-0627-4799-847e-004f9f67bdce class="margin-0">isPhD</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#0f8b08e0-2cea-48e1-a0aa-98c48b57400b class="margin-0">primarySupervisor</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#d0936c79-2ed6-4dab-9501-e38a5346cf73 class="margin-0">doctoralCooperationPartner</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1c1807c4-1497-4db8-b079-38e0bbcff87b class="margin-0">qualificationProcess</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#e3366950-27ab-4b90-a5e7-3a7351e198c1 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d9eb393b-51ba-40d2-ad2e-a0eb2f049c7c class="margin-10">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#cf124c72-6d1a-4d34-b111-95cad6db5a15 class="margin-10">completionDate</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#e9fcb004-ebc3-4862-803d-631906e47b06 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a544e127-e24c-4a94-8513-92d88986330d class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8584873a-a00d-4433-bc08-e4e07925e1e6 class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#786c5450-ecaf-49ad-b21d-37aee6b17679 class="margin-15">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#38908bb7-7583-43f8-964c-0cef0df684f3 class="margin-20">houseID</a></td><td class="no-break-word">string</td><td>false</td><td>fk</td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#942e8800-8d33-4adb-83d3-1e19ac4bd129 class="margin-15">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a2f365cf-2790-4f74-9758-1b544f203842 class="margin-20">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#03899de4-0006-4330-ae46-8ea98997e8d3 class="margin-15">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#64b63c54-2fe9-4502-b02a-740305dded7c class="margin-20">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a28a576e-11e5-4739-9308-b57f8aeaa2c4 class="margin-0">positions</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#255bb252-1f06-4f0c-b7a5-3f2f1fd7713f class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c895f6f8-0c4a-4041-b51e-99fc1b2981c7 class="margin-10">positionName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5f050309-db31-409d-8af7-5f8b788ed4a2 class="margin-10">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#51dd2e47-893b-41ed-ab8c-50475053093d class="margin-10">organisationalUnitID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#32747756-ecb6-44ac-893c-becf43f4dd08 class="margin-10">staffCategory</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1c9fd2a3-f19a-4044-8c2b-a5f8fbb193b7 class="margin-10">timeLimit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8912e4f3-d5b8-4000-88bd-538b9f0617a1 class="margin-10">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#a8d28001-fa3b-4438-92ee-ad3bc0407f0e class="margin-15">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7f3363f7-6e6d-48e8-b35c-c6a1ecc5dd7b class="margin-10">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#405293f9-a193-4bd5-97b1-3b3553ca8724 class="margin-15">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3cf897c8-1d16-4781-986a-73b771eee8ef class="margin-0">roles</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#974e2d39-e8ee-4913-bb8f-e1c01a9f8bb7 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4053dce3-ce35-4b3d-a2d2-e9ec40f3dab0 class="margin-10">roleName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8914d2e9-4802-4b98-b8ff-606c0815ae38 class="margin-10">unit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#144bbb80-8c73-41eb-8430-6480fa20b445 class="margin-10">unitIds</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f388aeeb-7ad7-40df-b031-baff0a767f75 class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ff58b21d-ece2-4534-bdee-33c09a8b0e85 class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#da8ba30d-60ae-4ecd-b510-d3b441aa8bf8 class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td>dk</td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2aa25e56-fd2a-4439-93d5-cd80bfdb46da class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#dc42dfd2-29a6-4c9f-bc22-5f01f369a42b class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e2725355-e75b-41fb-bed9-bd2f0779f1f2 class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#dbc3af7b-067f-4f07-9ce1-0b3cd26cda87 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="660a132f-d776-4a6d-b9cb-b1ad6d88e175"></a>2.1.2.3.3.1 Field **firstName**

##### 2.1.2.3.3.1.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image47.png?raw=true)

##### 2.1.2.3.3.1.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="0b2a3bc9-7926-4b44-b8f7-3798bd2a96c8"></a>2.1.2.3.3.2 Field **lastName**

##### 2.1.2.3.3.2.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image48.png?raw=true)

##### 2.1.2.3.3.2.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="90acb9c1-4dd9-419d-807f-54413cfa9f05"></a>2.1.2.3.3.3 Field **middleName**

##### 2.1.2.3.3.3.1 **middleName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image49.png?raw=true)

##### 2.1.2.3.3.3.2 **middleName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>middleName</td></tr><tr><td>Technical name</td><td>middleName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="3281b95e-3bd9-478a-b1fe-d2a4ea1066d6"></a>2.1.2.3.3.4 Field **description**

##### 2.1.2.3.3.4.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image50.png?raw=true)

##### 2.1.2.3.3.4.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="52243dc3-7056-4b37-95f3-4d2108a19d89"></a>2.1.2.3.3.5 Field **birthday**

##### 2.1.2.3.3.5.1 **birthday** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image51.png?raw=true)

##### 2.1.2.3.3.5.2 **birthday** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>birthday</td></tr><tr><td>Technical name</td><td>birthday</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="3f85edd4-56b6-43ff-b5c2-45b604932038"></a>2.1.2.3.3.6 Field **gender**

##### 2.1.2.3.3.6.1 **gender** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image52.png?raw=true)

##### 2.1.2.3.3.6.2 **gender** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>gender</td></tr><tr><td>Technical name</td><td>gender</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="95dc3047-eb11-4fc9-89da-f3cf4bd7a25a"></a>2.1.2.3.3.7 Field **nationality**

##### 2.1.2.3.3.7.1 **nationality** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image53.png?raw=true)

##### 2.1.2.3.3.7.2 **nationality** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>nationality</td></tr><tr><td>Technical name</td><td>nationality</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="275fd0e2-3084-4124-bff9-3b01b639cd4c"></a>2.1.2.3.3.8 Field **address**

##### 2.1.2.3.3.8.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image54.png?raw=true)

##### 2.1.2.3.3.8.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="edc06d05-64ab-4503-a2f2-be469fa12398"></a>2.1.2.3.3.9 Field **email**

##### 2.1.2.3.3.9.1 **email** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image55.png?raw=true)

##### 2.1.2.3.3.9.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td>email</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr><tr><td>Pattern</td><td>/^([\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+\.)*[\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+@((((([a-z0-9]{1}[a-z0-9\-]{0,62}[a-z0-9]{1})|[a-z])\.)+[a-z]{2,6})|(\d{1,3}\.){3}\d{1,3}(\:\d{1,5})?)$/i</td></tr></tbody></table>

### <a id="ecec2147-b36b-44ba-9e7b-be0b455f5579"></a>2.1.2.3.3.10 Field **phone**

##### 2.1.2.3.3.10.1 **phone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image56.png?raw=true)

##### 2.1.2.3.3.10.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td>phone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Pattern</td><td>^\+(?:[0-9] ?){6,25}[0-9]$</td></tr></tbody></table>

### <a id="f63711c8-97a5-40f2-a1f5-4dd485f18a44"></a>2.1.2.3.3.11 Field **webpages**

##### 2.1.2.3.3.11.1 **webpages** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image57.png?raw=true)

##### 2.1.2.3.3.11.2 **webpages** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5eb984e5-c02d-48df-b616-e01345abab18 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.11.3 **webpages** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>webpages</td></tr><tr><td>Technical name</td><td>webpages</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="5eb984e5-c02d-48df-b616-e01345abab18"></a>2.1.2.3.3.12 Field **\[0\]**

##### 2.1.2.3.3.12.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image58.png?raw=true)

##### 2.1.2.3.3.12.2 **\[0\]** Hierarchy

Parent field: **webpages**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#98f82a8f-f70a-48c1-a917-10cb806b8645 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#38150804-10f9-4016-83fd-9d164ea461b0 class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.12.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="98f82a8f-f70a-48c1-a917-10cb806b8645"></a>2.1.2.3.3.13 Field **name**

##### 2.1.2.3.3.13.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image59.png?raw=true)

##### 2.1.2.3.3.13.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="38150804-10f9-4016-83fd-9d164ea461b0"></a>2.1.2.3.3.14 Field **url**

##### 2.1.2.3.3.14.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image60.png?raw=true)

##### 2.1.2.3.3.14.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="49ab42a9-1641-48b0-ad54-b7b4690b687a"></a>2.1.2.3.3.15 Field **disciplinaryResearchAreas**

##### 2.1.2.3.3.15.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image61.png?raw=true)

##### 2.1.2.3.3.15.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e21eb9b7-1943-467c-9ec8-9751367708a8 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.15.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="e21eb9b7-1943-467c-9ec8-9751367708a8"></a>2.1.2.3.3.16 Field **\[0\]**

##### 2.1.2.3.3.16.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image62.png?raw=true)

##### 2.1.2.3.3.16.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="133278b5-d902-4ca3-8a82-1c57ce54c71a"></a>2.1.2.3.3.17 Field **doctoralEligibility**

##### 2.1.2.3.3.17.1 **doctoralEligibility** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image63.png?raw=true)

##### 2.1.2.3.3.17.2 **doctoralEligibility** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralEligibility</td></tr><tr><td>Technical name</td><td>doctoralEligibility</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="b93b648e-bb34-4b67-a6f2-d12ef64e10d5"></a>2.1.2.3.3.18 Field **doctoralEligibilityFrom**

##### 2.1.2.3.3.18.1 **doctoralEligibilityFrom** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image64.png?raw=true)

##### 2.1.2.3.3.18.2 **doctoralEligibilityFrom** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralEligibilityFrom</td></tr><tr><td>Technical name</td><td>doctoralEligibilityFrom</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Default</td><td>domes</td></tr><tr><td>Enum</td><td>domestic,foreign</td></tr></tbody></table>

### <a id="e14a569d-0627-4799-847e-004f9f67bdce"></a>2.1.2.3.3.19 Field **isPhD**

##### 2.1.2.3.3.19.1 **isPhD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image65.png?raw=true)

##### 2.1.2.3.3.19.2 **isPhD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>isPhD</td></tr><tr><td>Technical name</td><td>isPhD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="0f8b08e0-2cea-48e1-a0aa-98c48b57400b"></a>2.1.2.3.3.20 Field **primarySupervisor**

##### 2.1.2.3.3.20.1 **primarySupervisor** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image66.png?raw=true)

##### 2.1.2.3.3.20.2 **primarySupervisor** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>primarySupervisor</td></tr><tr><td>Technical name</td><td>primarySupervisor</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="d0936c79-2ed6-4dab-9501-e38a5346cf73"></a>2.1.2.3.3.21 Field **doctoralCooperationPartner**

##### 2.1.2.3.3.21.1 **doctoralCooperationPartner** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image67.png?raw=true)

##### 2.1.2.3.3.21.2 **doctoralCooperationPartner** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doctoralCooperationPartner</td></tr><tr><td>Technical name</td><td>doctoralCooperationPartner</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1c1807c4-1497-4db8-b079-38e0bbcff87b"></a>2.1.2.3.3.22 Field **qualificationProcess**

##### 2.1.2.3.3.22.1 **qualificationProcess** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image68.png?raw=true)

##### 2.1.2.3.3.22.2 **qualificationProcess** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e3366950-27ab-4b90-a5e7-3a7351e198c1 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.22.3 **qualificationProcess** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>qualificationProcess</td></tr><tr><td>Technical name</td><td>qualificationProcess</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="e3366950-27ab-4b90-a5e7-3a7351e198c1"></a>2.1.2.3.3.23 Field **\[0\]**

##### 2.1.2.3.3.23.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image69.png?raw=true)

##### 2.1.2.3.3.23.2 **\[0\]** Hierarchy

Parent field: **qualificationProcess**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d9eb393b-51ba-40d2-ad2e-a0eb2f049c7c class="margin-NaN">type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#cf124c72-6d1a-4d34-b111-95cad6db5a15 class="margin-NaN">completionDate</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

##### 2.1.2.3.3.23.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="d9eb393b-51ba-40d2-ad2e-a0eb2f049c7c"></a>2.1.2.3.3.24 Field **type**

##### 2.1.2.3.3.24.1 **type** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image70.png?raw=true)

##### 2.1.2.3.3.24.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td>type</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>habilitation,doctoral thesis</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="cf124c72-6d1a-4d34-b111-95cad6db5a15"></a>2.1.2.3.3.25 Field **completionDate**

##### 2.1.2.3.3.25.1 **completionDate** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image71.png?raw=true)

##### 2.1.2.3.3.25.2 **completionDate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>completionDate</td></tr><tr><td>Technical name</td><td>completionDate</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="e9fcb004-ebc3-4862-803d-631906e47b06"></a>2.1.2.3.3.26 Field **ids**

##### 2.1.2.3.3.26.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image72.png?raw=true)

##### 2.1.2.3.3.26.2 **ids** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a544e127-e24c-4a94-8513-92d88986330d class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.26.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="a544e127-e24c-4a94-8513-92d88986330d"></a>2.1.2.3.3.27 Field **\[0\]**

##### 2.1.2.3.3.27.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image73.png?raw=true)

##### 2.1.2.3.3.27.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8584873a-a00d-4433-bc08-e4e07925e1e6 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.27.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="8584873a-a00d-4433-bc08-e4e07925e1e6"></a>2.1.2.3.3.28 Field **anyOf**

##### 2.1.2.3.3.28.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image74.png?raw=true)

##### 2.1.2.3.3.28.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#786c5450-ecaf-49ad-b21d-37aee6b17679 class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#942e8800-8d33-4adb-83d3-1e19ac4bd129 class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#03899de4-0006-4330-ae46-8ea98997e8d3 class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.28.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="786c5450-ecaf-49ad-b21d-37aee6b17679"></a>2.1.2.3.3.29 Field **\[0\] houseID**

##### 2.1.2.3.3.29.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image75.png?raw=true)

##### 2.1.2.3.3.29.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#38908bb7-7583-43f8-964c-0cef0df684f3 class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.29.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="38908bb7-7583-43f8-964c-0cef0df684f3"></a>2.1.2.3.3.30 Field **houseID**

##### 2.1.2.3.3.30.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image76.png?raw=true)

##### 2.1.2.3.3.30.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Foreign collection</td><td><a href=#482b0df2-d80e-4871-89e5-ea8b028eabb4>Publication</a></td></tr><tr><td>Foreign field</td><td><a href=#a34ac963-748a-482e-a073-0296b6471780></a></td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="942e8800-8d33-4adb-83d3-1e19ac4bd129"></a>2.1.2.3.3.31 Field **\[1\] ORCiD**

##### 2.1.2.3.3.31.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image77.png?raw=true)

##### 2.1.2.3.3.31.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a2f365cf-2790-4f74-9758-1b544f203842 class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.31.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="a2f365cf-2790-4f74-9758-1b544f203842"></a>2.1.2.3.3.32 Field **ORCiD**

##### 2.1.2.3.3.32.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image78.png?raw=true)

##### 2.1.2.3.3.32.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="03899de4-0006-4330-ae46-8ea98997e8d3"></a>2.1.2.3.3.33 Field **\[2\] anyOtherID**

##### 2.1.2.3.3.33.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image79.png?raw=true)

##### 2.1.2.3.3.33.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#64b63c54-2fe9-4502-b02a-740305dded7c class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.33.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="64b63c54-2fe9-4502-b02a-740305dded7c"></a>2.1.2.3.3.34 Field **id**

##### 2.1.2.3.3.34.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image80.png?raw=true)

##### 2.1.2.3.3.34.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a28a576e-11e5-4739-9308-b57f8aeaa2c4"></a>2.1.2.3.3.35 Field **positions**

##### 2.1.2.3.3.35.1 **positions** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image81.png?raw=true)

##### 2.1.2.3.3.35.2 **positions** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#255bb252-1f06-4f0c-b7a5-3f2f1fd7713f class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.35.3 **positions** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>positions</td></tr><tr><td>Technical name</td><td>positions</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="255bb252-1f06-4f0c-b7a5-3f2f1fd7713f"></a>2.1.2.3.3.36 Field **\[0\]**

##### 2.1.2.3.3.36.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image82.png?raw=true)

##### 2.1.2.3.3.36.2 **\[0\]** Hierarchy

Parent field: **positions**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c895f6f8-0c4a-4041-b51e-99fc1b2981c7 class="margin-NaN">positionName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5f050309-db31-409d-8af7-5f8b788ed4a2 class="margin-NaN">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#51dd2e47-893b-41ed-ab8c-50475053093d class="margin-NaN">organisationalUnitID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#32747756-ecb6-44ac-893c-becf43f4dd08 class="margin-NaN">staffCategory</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1c9fd2a3-f19a-4044-8c2b-a5f8fbb193b7 class="margin-NaN">timeLimit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8912e4f3-d5b8-4000-88bd-538b9f0617a1 class="margin-NaN">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#7f3363f7-6e6d-48e8-b35c-c6a1ecc5dd7b class="margin-NaN">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

##### 2.1.2.3.3.36.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="c895f6f8-0c4a-4041-b51e-99fc1b2981c7"></a>2.1.2.3.3.37 Field **positionName**

##### 2.1.2.3.3.37.1 **positionName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image83.png?raw=true)

##### 2.1.2.3.3.37.2 **positionName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>positionName</td></tr><tr><td>Technical name</td><td>positionName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="5f050309-db31-409d-8af7-5f8b788ed4a2"></a>2.1.2.3.3.38 Field **organisationalUnit**

##### 2.1.2.3.3.38.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image84.png?raw=true)

##### 2.1.2.3.3.38.2 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="51dd2e47-893b-41ed-ab8c-50475053093d"></a>2.1.2.3.3.39 Field **organisationalUnitID**

##### 2.1.2.3.3.39.1 **organisationalUnitID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image85.png?raw=true)

##### 2.1.2.3.3.39.2 **organisationalUnitID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnitID</td></tr><tr><td>Technical name</td><td>organisationalUnitID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="32747756-ecb6-44ac-893c-becf43f4dd08"></a>2.1.2.3.3.40 Field **staffCategory**

##### 2.1.2.3.3.40.1 **staffCategory** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image86.png?raw=true)

##### 2.1.2.3.3.40.2 **staffCategory** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>staffCategory</td></tr><tr><td>Technical name</td><td>staffCategory</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1c9fd2a3-f19a-4044-8c2b-a5f8fbb193b7"></a>2.1.2.3.3.41 Field **timeLimit**

##### 2.1.2.3.3.41.1 **timeLimit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image87.png?raw=true)

##### 2.1.2.3.3.41.2 **timeLimit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>timeLimit</td></tr><tr><td>Technical name</td><td>timeLimit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>befristet,unbefristet</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="8912e4f3-d5b8-4000-88bd-538b9f0617a1"></a>2.1.2.3.3.42 Field **subjects**

##### 2.1.2.3.3.42.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image88.png?raw=true)

##### 2.1.2.3.3.42.2 **subjects** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a8d28001-fa3b-4438-92ee-ad3bc0407f0e class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.42.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="a8d28001-fa3b-4438-92ee-ad3bc0407f0e"></a>2.1.2.3.3.43 Field **\[0\]**

##### 2.1.2.3.3.43.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image89.png?raw=true)

##### 2.1.2.3.3.43.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="7f3363f7-6e6d-48e8-b35c-c6a1ecc5dd7b"></a>2.1.2.3.3.44 Field **disciplinaryResearchAreas**

##### 2.1.2.3.3.44.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image90.png?raw=true)

##### 2.1.2.3.3.44.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#405293f9-a193-4bd5-97b1-3b3553ca8724 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.44.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="405293f9-a193-4bd5-97b1-3b3553ca8724"></a>2.1.2.3.3.45 Field **\[0\]**

##### 2.1.2.3.3.45.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image91.png?raw=true)

##### 2.1.2.3.3.45.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="3cf897c8-1d16-4781-986a-73b771eee8ef"></a>2.1.2.3.3.46 Field **roles**

##### 2.1.2.3.3.46.1 **roles** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image92.png?raw=true)

##### 2.1.2.3.3.46.2 **roles** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#974e2d39-e8ee-4913-bb8f-e1c01a9f8bb7 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.46.3 **roles** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>roles</td></tr><tr><td>Technical name</td><td>roles</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="974e2d39-e8ee-4913-bb8f-e1c01a9f8bb7"></a>2.1.2.3.3.47 Field **\[0\]**

##### 2.1.2.3.3.47.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image93.png?raw=true)

##### 2.1.2.3.3.47.2 **\[0\]** Hierarchy

Parent field: **roles**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#4053dce3-ce35-4b3d-a2d2-e9ec40f3dab0 class="margin-NaN">roleName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8914d2e9-4802-4b98-b8ff-606c0815ae38 class="margin-NaN">unit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#144bbb80-8c73-41eb-8430-6480fa20b445 class="margin-NaN">unitIds</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.47.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="4053dce3-ce35-4b3d-a2d2-e9ec40f3dab0"></a>2.1.2.3.3.48 Field **roleName**

##### 2.1.2.3.3.48.1 **roleName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image94.png?raw=true)

##### 2.1.2.3.3.48.2 **roleName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>roleName</td></tr><tr><td>Technical name</td><td>roleName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="8914d2e9-4802-4b98-b8ff-606c0815ae38"></a>2.1.2.3.3.49 Field **unit**

##### 2.1.2.3.3.49.1 **unit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image95.png?raw=true)

##### 2.1.2.3.3.49.2 **unit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>unit</td></tr><tr><td>Technical name</td><td>unit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>projects,clusters,etc.</td></tr></tbody></table>

### <a id="144bbb80-8c73-41eb-8430-6480fa20b445"></a>2.1.2.3.3.50 Field **unitIds**

##### 2.1.2.3.3.50.1 **unitIds** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image96.png?raw=true)

##### 2.1.2.3.3.50.2 **unitIds** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f388aeeb-7ad7-40df-b031-baff0a767f75 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.50.3 **unitIds** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>unitIds</td></tr><tr><td>Technical name</td><td>unitIds</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f388aeeb-7ad7-40df-b031-baff0a767f75"></a>2.1.2.3.3.51 Field **\[0\]**

##### 2.1.2.3.3.51.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image97.png?raw=true)

##### 2.1.2.3.3.51.2 **\[0\]** Hierarchy

Parent field: **unitIds**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ff58b21d-ece2-4534-bdee-33c09a8b0e85 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.51.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="ff58b21d-ece2-4534-bdee-33c09a8b0e85"></a>2.1.2.3.3.52 Field **anyOf**

##### 2.1.2.3.3.52.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image98.png?raw=true)

##### 2.1.2.3.3.52.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#da8ba30d-60ae-4ecd-b510-d3b441aa8bf8 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2aa25e56-fd2a-4439-93d5-cd80bfdb46da class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.52.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="da8ba30d-60ae-4ecd-b510-d3b441aa8bf8"></a>2.1.2.3.3.53 Field **\[0\] houseId**

##### 2.1.2.3.3.53.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image99.png?raw=true)

##### 2.1.2.3.3.53.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.53.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="5a5bb19e-983c-455e-b734-121b7937e7cb"></a>2.1.2.3.3.54 Field **houseId**

##### 2.1.2.3.3.54.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image100.png?raw=true)

##### 2.1.2.3.3.54.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="2aa25e56-fd2a-4439-93d5-cd80bfdb46da"></a>2.1.2.3.3.55 Field **\[1\] anyOtherID**

##### 2.1.2.3.3.55.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image101.png?raw=true)

##### 2.1.2.3.3.55.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#dc42dfd2-29a6-4c9f-bc22-5f01f369a42b class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.55.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="dc42dfd2-29a6-4c9f-bc22-5f01f369a42b"></a>2.1.2.3.3.56 Field **anyOtherID**

##### 2.1.2.3.3.56.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image102.png?raw=true)

##### 2.1.2.3.3.56.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e2725355-e75b-41fb-bed9-bd2f0779f1f2"></a>2.1.2.3.3.57 Field **interDisciplinaryResearchAreas**

##### 2.1.2.3.3.57.1 **interDisciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image103.png?raw=true)

##### 2.1.2.3.3.57.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Person**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#dbc3af7b-067f-4f07-9ce1-0b3cd26cda87 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.57.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="dbc3af7b-067f-4f07-9ce1-0b3cd26cda87"></a>2.1.2.3.3.58 Field **\[0\]**

##### 2.1.2.3.3.58.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image104.png?raw=true)

##### 2.1.2.3.3.58.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 2.1.2.3.4 **Person** JSON Schema

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

##### 2.1.2.3.5 **Person** JSON data

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
    "email": "/2*@10.9.214.719/i",
    "phone": "+59 081 8250 3 33 3 33249 3 5 6 6 2",
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

### <a id="4f72014b-c421-4a4c-8aa8-a56403100ac5"></a>2.1.2.4 Document **Project**

##### 2.1.2.4.1 **Project** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image105.png?raw=true)

##### 2.1.2.4.2 **Project** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Project</td></tr><tr><td>Technical name</td><td>project</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3 **Project** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d21e8677-a340-4646-8edc-3b9517916bd0 class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#46da3d03-9f77-43ca-a334-953cd5b91066 class="margin-0">address</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a03fa701-36ca-48fa-8024-dad58c73b805 class="margin-0">phone</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1aafa631-f888-4e06-8ad1-e12237451142 class="margin-0">emails</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#429b6354-77da-409d-b282-bcf5e539ce78 class="margin-5">[0]</a></td><td class="no-break-word">email</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0658e2a4-d281-4886-ae6d-3e0b102b2aae class="margin-0">organisationalUnit</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#c4e8076f-876c-45cb-ac84-ab12ea7fe0bb class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9664177c-0612-464f-90c2-1bafc385a753 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7379ce7e-74d3-42bc-8523-9c1f992953bd class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#39fd6b6e-0b14-4b74-b356-347761fa8bba class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b4da53e-5ac6-4ebc-a6e4-0501c3ca124f class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7fc4dbc9-16ce-492b-a668-f90613dd8f67 class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#99f3efe4-a7da-4e38-a2c8-a3dcbe0f6213 class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0b24a814-407c-48f1-b4b2-b6ca8ad84049 class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b40d4f8-df13-410c-9ec2-6b803546e356 class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1ed6bd98-ce08-4fac-813e-5e10f979959b class="margin-10">coordinatorUnit</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#20f454dd-ac88-4e09-bebd-25e4bf7fe46c class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#725b32ed-b2ba-4e29-a77f-4e07ef52b5c3 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9f66a275-463c-4d92-9080-8847f4b6458d class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#10e8d627-bf02-487a-8b32-657a7bf77936 class="margin-15">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#274035a2-0621-463e-bd07-711ac475fe76 class="margin-20">houseId</a></td><td class="no-break-word">string</td><td>false</td><td>fk</td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fa27f12f-9d32-457f-b978-3b22266e017e class="margin-15">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ebcd04bc-942e-442b-b16a-f8b7141d9403 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#31944860-5080-4851-b78c-c3524e5d7f3d class="margin-0">parentProject</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#490183cf-75d1-419c-ac88-66a25999c63a class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#22cec81e-ebb1-45b7-89ca-34ece24a4cc5 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#82634313-e7a9-40d4-a74a-6cf70984603c class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#27631f31-0519-454a-b2da-864e9fa32ee7 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ff9c67f1-cf0e-44c7-a086-2478d818c03b class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6f9cf413-f9f3-45ff-a927-b660634b8106 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f1e54daa-6f7b-42c3-b6e7-9e4f963ae0a6 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4dd67582-418b-47c3-9fa1-4453cf355c11 class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7ef64d4f-bb19-4748-8def-732185109a59 class="margin-0">projectCoordinatorOrganisation</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8f4925e1-e524-4c12-af06-6f1430f82f0b class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cfe3741b-d5ae-4339-a157-a196825f1ce9 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#816cb498-00e4-4977-bf3e-9b681156ac74 class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1df42081-93f7-4390-9a16-34768af78b70 class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5a755009-4d18-46d6-bcf0-8d1cdd297845 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2a218466-7a75-431a-bba9-e83d35cb3ac6 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc25f5c7-f068-4184-a148-d1aa16c4ca41 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e78b82bd-af0e-42e3-adf3-f8c9511738d5 class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#92554922-e631-4e02-a3a4-74f8e02c20e0 class="margin-0">scientificProjectLead</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#ce02eefa-e74a-43da-8fb9-79b91e06a74a class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6036ff65-be07-4401-a0ba-2f52a0ffb51f class="margin-10">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fccf89e8-c156-4505-8635-63055ba4bf13 class="margin-10">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#588ec6f8-24a3-4799-9c01-ecb2b6ea5804 class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7f251443-0160-4dff-a43c-4a13e5d646dd class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3c66028a-408c-4d28-a02b-6657d77890af class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cb2ebf6b-1a2a-4658-a674-62c3fffabad0 class="margin-25">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#df5e024a-b9bc-466c-b711-373dd8369063 class="margin-30">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f6de375a-4a7d-47c4-b54f-7fa4294400dd class="margin-25">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dcdd82c-248d-4871-ad07-7040cc34655d class="margin-30">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b06f9bb-3f03-47cd-8506-7e65c72e98d6 class="margin-25">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bda4e3bf-0a90-4691-80b1-34412746865f class="margin-30">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b8209ee9-62d4-408d-9570-ea1f158285a8 class="margin-0">keywords</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#63f684a7-bf03-4706-8734-80d9dbe6c92f class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6dee2d28-520a-4b24-82b6-f9bd67fe00f0 class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#3027d0ab-d9eb-4777-81e1-d5ab9a70c22d class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#01d090e2-8995-4c67-b0c7-fedceb80f587 class="margin-0">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#bfa8235f-44f6-456a-8dc3-a0b2d9cbaea2 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fb51a340-e2a8-4f10-88d8-4f8e762237c6 class="margin-0">description</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#135fc519-1bb9-4646-8ecc-ba4ff7f8b8cd class="margin-0">projectObjective</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#4eb09caa-11b3-464c-bf18-3cd245c4b3c3 class="margin-0">funderCategories</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#e1711402-ee75-4f0d-984a-c74e02b0201a class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4368a3e4-16ae-47f5-b282-8b5b4e4b2fb2 class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b3ce7371-c2ca-4c61-a1c1-1867464cb344 class="margin-10">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#aa1feb8a-93f7-4f89-8f34-1bb93922f18f class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#d7cd4eeb-20ed-42f6-95a4-fee58dbfdc49 class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8a9966c3-f793-4183-8869-803c278309e5 class="margin-25">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#498619cd-1532-4d59-95f3-c1ca036a993a class="margin-30">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#474dcf40-8b4c-4cb3-a026-88908c9bf665 class="margin-25">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#71e111b6-7efb-49e2-9224-0899df32ccd6 class="margin-30">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6fb5114d-3a8e-4346-8957-b902a9314849 class="margin-0">funders</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1d544b33-207b-4837-9c25-37aeee1bc7b6 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0c43cb06-fe61-43f7-9b3d-c2c1fb2f659a class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#522bcce3-5c54-487d-b716-bf7a96724332 class="margin-10">country</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcf211e2-c1af-483b-84b0-32989b2c74f9 class="margin-10">funderAbbrevation</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8b507411-127f-48fc-85fa-248c3b0c4f6e class="margin-10">fundRef</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5f7c84ba-431f-4d08-b34f-c9a77a9d4f54 class="margin-10">ror</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e4e92c1b-5939-4dd0-bbf6-04be035e0088 class="margin-10">isoCountryCode</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a0b0b282-b748-40f7-8626-b1d47cb4b148 class="margin-0">projectStart</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#12a92436-510c-4478-bca7-6cf618e1de30 class="margin-0">projectEnd</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#ba6cfd29-20af-4bde-bace-157f3e7ac57d class="margin-0">thirdPartyFunding</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#904a92e1-f2cb-4e71-b200-01dee837e223 class="margin-0">grantAmount</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#2e47399c-42a8-492f-9fc6-7530030c1268 class="margin-0">projectStatus</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b0ebab6d-1eb2-4a7c-90f2-9a4dfc363503 class="margin-0">webpages</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f4406aa6-3992-4a62-9b62-2fe50d2ca0ac class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#45e7c62c-945a-41fd-bceb-f1dd18acb3da class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#faf46be6-4606-45ad-885c-321bf04e879c class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0378dbef-814c-4e29-824e-d1e42bc6bf2a class="margin-0">repositories</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f5af3d2a-ad69-4e1b-85b2-129c97c4e3b3 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#12d19dd0-d452-4553-bc54-b2b9d9957b2b class="margin-10">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fe479747-e215-4425-bd26-dae435e96841 class="margin-10">url</a></td><td class="no-break-word">uri</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b9661cd0-49df-4455-811c-19ec49d35441 class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#53e21acd-dcd7-4f96-8933-87cd832e0a92 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="d21e8677-a340-4646-8edc-3b9517916bd0"></a>2.1.2.4.3.1 Field **name**

##### 2.1.2.4.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image106.png?raw=true)

##### 2.1.2.4.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="46da3d03-9f77-43ca-a334-953cd5b91066"></a>2.1.2.4.3.2 Field **address**

##### 2.1.2.4.3.2.1 **address** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image107.png?raw=true)

##### 2.1.2.4.3.2.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td>address</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a03fa701-36ca-48fa-8024-dad58c73b805"></a>2.1.2.4.3.3 Field **phone**

##### 2.1.2.4.3.3.1 **phone** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image108.png?raw=true)

##### 2.1.2.4.3.3.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td>phone</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Pattern</td><td>^\+(?:[0-9] ?){6,25}[0-9]$</td></tr></tbody></table>

### <a id="1aafa631-f888-4e06-8ad1-e12237451142"></a>2.1.2.4.3.4 Field **emails**

##### 2.1.2.4.3.4.1 **emails** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image109.png?raw=true)

##### 2.1.2.4.3.4.2 **emails** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#429b6354-77da-409d-b282-bcf5e539ce78 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.4.3 **emails** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>emails</td></tr><tr><td>Technical name</td><td>emails</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="429b6354-77da-409d-b282-bcf5e539ce78"></a>2.1.2.4.3.5 Field **\[0\]**

##### 2.1.2.4.3.5.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image110.png?raw=true)

##### 2.1.2.4.3.5.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>email</td></tr><tr><td>Pattern</td><td>/^([\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+\.)*[\w\!\#$\%\&amp;\'\*\+\-\/\=\?\^\`{\|\}\~]+@((((([a-z0-9]{1}[a-z0-9\-]{0,62}[a-z0-9]{1})|[a-z])\.)+[a-z]{2,6})|(\d{1,3}\.){3}\d{1,3}(\:\d{1,5})?)$/i</td></tr></tbody></table>

### <a id="0658e2a4-d281-4886-ae6d-3e0b102b2aae"></a>2.1.2.4.3.6 Field **organisationalUnit**

##### 2.1.2.4.3.6.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image111.png?raw=true)

##### 2.1.2.4.3.6.2 **organisationalUnit** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c4e8076f-876c-45cb-ac84-ab12ea7fe0bb class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.6.3 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="c4e8076f-876c-45cb-ac84-ab12ea7fe0bb"></a>2.1.2.4.3.7 Field **\[0\]**

##### 2.1.2.4.3.7.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image112.png?raw=true)

##### 2.1.2.4.3.7.2 **\[0\]** Hierarchy

Parent field: **organisationalUnit**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9664177c-0612-464f-90c2-1bafc385a753 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7379ce7e-74d3-42bc-8523-9c1f992953bd class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1ed6bd98-ce08-4fac-813e-5e10f979959b class="margin-NaN">coordinatorUnit</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.7.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="9664177c-0612-464f-90c2-1bafc385a753"></a>2.1.2.4.3.8 Field **name**

##### 2.1.2.4.3.8.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image113.png?raw=true)

##### 2.1.2.4.3.8.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="7379ce7e-74d3-42bc-8523-9c1f992953bd"></a>2.1.2.4.3.9 Field **ids**

##### 2.1.2.4.3.9.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image114.png?raw=true)

##### 2.1.2.4.3.9.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#39fd6b6e-0b14-4b74-b356-347761fa8bba class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.9.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="39fd6b6e-0b14-4b74-b356-347761fa8bba"></a>2.1.2.4.3.10 Field **\[0\]**

##### 2.1.2.4.3.10.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image115.png?raw=true)

##### 2.1.2.4.3.10.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9b4da53e-5ac6-4ebc-a6e4-0501c3ca124f class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.10.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="9b4da53e-5ac6-4ebc-a6e4-0501c3ca124f"></a>2.1.2.4.3.11 Field **anyOf**

##### 2.1.2.4.3.11.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image116.png?raw=true)

##### 2.1.2.4.3.11.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7fc4dbc9-16ce-492b-a668-f90613dd8f67 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0b24a814-407c-48f1-b4b2-b6ca8ad84049 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.11.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="7fc4dbc9-16ce-492b-a668-f90613dd8f67"></a>2.1.2.4.3.12 Field **\[0\] houseId**

##### 2.1.2.4.3.12.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image117.png?raw=true)

##### 2.1.2.4.3.12.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#99f3efe4-a7da-4e38-a2c8-a3dcbe0f6213 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.12.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="99f3efe4-a7da-4e38-a2c8-a3dcbe0f6213"></a>2.1.2.4.3.13 Field **houseId**

##### 2.1.2.4.3.13.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image118.png?raw=true)

##### 2.1.2.4.3.13.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="0b24a814-407c-48f1-b4b2-b6ca8ad84049"></a>2.1.2.4.3.14 Field **\[1\] anyOtherID**

##### 2.1.2.4.3.14.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image119.png?raw=true)

##### 2.1.2.4.3.14.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9b40d4f8-df13-410c-9ec2-6b803546e356 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.14.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="9b40d4f8-df13-410c-9ec2-6b803546e356"></a>2.1.2.4.3.15 Field **anyOtherID**

##### 2.1.2.4.3.15.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image120.png?raw=true)

##### 2.1.2.4.3.15.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="1ed6bd98-ce08-4fac-813e-5e10f979959b"></a>2.1.2.4.3.16 Field **coordinatorUnit**

##### 2.1.2.4.3.16.1 **coordinatorUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image121.png?raw=true)

##### 2.1.2.4.3.16.2 **coordinatorUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>coordinatorUnit</td></tr><tr><td>Technical name</td><td>coordinatorUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr></tbody></table>

### <a id="20f454dd-ac88-4e09-bebd-25e4bf7fe46c"></a>2.1.2.4.3.17 Field **ids**

##### 2.1.2.4.3.17.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image122.png?raw=true)

##### 2.1.2.4.3.17.2 **ids** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#725b32ed-b2ba-4e29-a77f-4e07ef52b5c3 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.17.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="725b32ed-b2ba-4e29-a77f-4e07ef52b5c3"></a>2.1.2.4.3.18 Field **\[0\]**

##### 2.1.2.4.3.18.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image123.png?raw=true)

##### 2.1.2.4.3.18.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9f66a275-463c-4d92-9080-8847f4b6458d class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.18.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="9f66a275-463c-4d92-9080-8847f4b6458d"></a>2.1.2.4.3.19 Field **anyOf**

##### 2.1.2.4.3.19.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image124.png?raw=true)

##### 2.1.2.4.3.19.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#10e8d627-bf02-487a-8b32-657a7bf77936 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fa27f12f-9d32-457f-b978-3b22266e017e class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.19.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="10e8d627-bf02-487a-8b32-657a7bf77936"></a>2.1.2.4.3.20 Field **\[0\] houseId**

##### 2.1.2.4.3.20.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image125.png?raw=true)

##### 2.1.2.4.3.20.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#274035a2-0621-463e-bd07-711ac475fe76 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.20.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="274035a2-0621-463e-bd07-711ac475fe76"></a>2.1.2.4.3.21 Field **houseId**

##### 2.1.2.4.3.21.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image126.png?raw=true)

##### 2.1.2.4.3.21.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Foreign collection</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Foreign field</td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>houseId</a></td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="fa27f12f-9d32-457f-b978-3b22266e017e"></a>2.1.2.4.3.22 Field **\[1\] anyOtherID**

##### 2.1.2.4.3.22.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image127.png?raw=true)

##### 2.1.2.4.3.22.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ebcd04bc-942e-442b-b16a-f8b7141d9403 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.22.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="ebcd04bc-942e-442b-b16a-f8b7141d9403"></a>2.1.2.4.3.23 Field **anyOtherID**

##### 2.1.2.4.3.23.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image128.png?raw=true)

##### 2.1.2.4.3.23.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="31944860-5080-4851-b78c-c3524e5d7f3d"></a>2.1.2.4.3.24 Field **parentProject**

##### 2.1.2.4.3.24.1 **parentProject** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image129.png?raw=true)

##### 2.1.2.4.3.24.2 **parentProject** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#490183cf-75d1-419c-ac88-66a25999c63a class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#22cec81e-ebb1-45b7-89ca-34ece24a4cc5 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.24.3 **parentProject** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>parentProject</td></tr><tr><td>Technical name</td><td>parentProject</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="490183cf-75d1-419c-ac88-66a25999c63a"></a>2.1.2.4.3.25 Field **name**

##### 2.1.2.4.3.25.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image130.png?raw=true)

##### 2.1.2.4.3.25.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="22cec81e-ebb1-45b7-89ca-34ece24a4cc5"></a>2.1.2.4.3.26 Field **ids**

##### 2.1.2.4.3.26.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image131.png?raw=true)

##### 2.1.2.4.3.26.2 **ids** Hierarchy

Parent field: **parentProject**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#82634313-e7a9-40d4-a74a-6cf70984603c class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.26.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="82634313-e7a9-40d4-a74a-6cf70984603c"></a>2.1.2.4.3.27 Field **\[0\]**

##### 2.1.2.4.3.27.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image132.png?raw=true)

##### 2.1.2.4.3.27.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#27631f31-0519-454a-b2da-864e9fa32ee7 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.27.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="27631f31-0519-454a-b2da-864e9fa32ee7"></a>2.1.2.4.3.28 Field **anyOf**

##### 2.1.2.4.3.28.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image133.png?raw=true)

##### 2.1.2.4.3.28.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ff9c67f1-cf0e-44c7-a086-2478d818c03b class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f1e54daa-6f7b-42c3-b6e7-9e4f963ae0a6 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.28.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="ff9c67f1-cf0e-44c7-a086-2478d818c03b"></a>2.1.2.4.3.29 Field **\[0\] houseId**

##### 2.1.2.4.3.29.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image134.png?raw=true)

##### 2.1.2.4.3.29.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6f9cf413-f9f3-45ff-a927-b660634b8106 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.29.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="6f9cf413-f9f3-45ff-a927-b660634b8106"></a>2.1.2.4.3.30 Field **houseId**

##### 2.1.2.4.3.30.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image135.png?raw=true)

##### 2.1.2.4.3.30.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="f1e54daa-6f7b-42c3-b6e7-9e4f963ae0a6"></a>2.1.2.4.3.31 Field **\[1\] anyOtherID**

##### 2.1.2.4.3.31.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image136.png?raw=true)

##### 2.1.2.4.3.31.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#4dd67582-418b-47c3-9fa1-4453cf355c11 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.31.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="4dd67582-418b-47c3-9fa1-4453cf355c11"></a>2.1.2.4.3.32 Field **anyOtherID**

##### 2.1.2.4.3.32.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image137.png?raw=true)

##### 2.1.2.4.3.32.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="7ef64d4f-bb19-4748-8def-732185109a59"></a>2.1.2.4.3.33 Field **projectCoordinatorOrganisation**

##### 2.1.2.4.3.33.1 **projectCoordinatorOrganisation** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image138.png?raw=true)

##### 2.1.2.4.3.33.2 **projectCoordinatorOrganisation** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8f4925e1-e524-4c12-af06-6f1430f82f0b class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cfe3741b-d5ae-4339-a157-a196825f1ce9 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.33.3 **projectCoordinatorOrganisation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectCoordinatorOrganisation</td></tr><tr><td>Technical name</td><td>projectCoordinatorOrganisation</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="8f4925e1-e524-4c12-af06-6f1430f82f0b"></a>2.1.2.4.3.34 Field **name**

##### 2.1.2.4.3.34.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image139.png?raw=true)

##### 2.1.2.4.3.34.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="cfe3741b-d5ae-4339-a157-a196825f1ce9"></a>2.1.2.4.3.35 Field **ids**

##### 2.1.2.4.3.35.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image140.png?raw=true)

##### 2.1.2.4.3.35.2 **ids** Hierarchy

Parent field: **projectCoordinatorOrganisation**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#816cb498-00e4-4977-bf3e-9b681156ac74 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.35.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="816cb498-00e4-4977-bf3e-9b681156ac74"></a>2.1.2.4.3.36 Field **\[0\]**

##### 2.1.2.4.3.36.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image141.png?raw=true)

##### 2.1.2.4.3.36.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1df42081-93f7-4390-9a16-34768af78b70 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.36.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="1df42081-93f7-4390-9a16-34768af78b70"></a>2.1.2.4.3.37 Field **anyOf**

##### 2.1.2.4.3.37.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image142.png?raw=true)

##### 2.1.2.4.3.37.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5a755009-4d18-46d6-bcf0-8d1cdd297845 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc25f5c7-f068-4184-a148-d1aa16c4ca41 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.37.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="5a755009-4d18-46d6-bcf0-8d1cdd297845"></a>2.1.2.4.3.38 Field **\[0\] houseId**

##### 2.1.2.4.3.38.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image143.png?raw=true)

##### 2.1.2.4.3.38.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2a218466-7a75-431a-bba9-e83d35cb3ac6 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.38.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="2a218466-7a75-431a-bba9-e83d35cb3ac6"></a>2.1.2.4.3.39 Field **houseId**

##### 2.1.2.4.3.39.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image144.png?raw=true)

##### 2.1.2.4.3.39.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="cc25f5c7-f068-4184-a148-d1aa16c4ca41"></a>2.1.2.4.3.40 Field **\[1\] anyOtherID**

##### 2.1.2.4.3.40.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image145.png?raw=true)

##### 2.1.2.4.3.40.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e78b82bd-af0e-42e3-adf3-f8c9511738d5 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.40.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="e78b82bd-af0e-42e3-adf3-f8c9511738d5"></a>2.1.2.4.3.41 Field **anyOtherID**

##### 2.1.2.4.3.41.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image146.png?raw=true)

##### 2.1.2.4.3.41.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="92554922-e631-4e02-a3a4-74f8e02c20e0"></a>2.1.2.4.3.42 Field **scientificProjectLead**

##### 2.1.2.4.3.42.1 **scientificProjectLead** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image147.png?raw=true)

##### 2.1.2.4.3.42.2 **scientificProjectLead** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#ce02eefa-e74a-43da-8fb9-79b91e06a74a class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.42.3 **scientificProjectLead** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>scientificProjectLead</td></tr><tr><td>Technical name</td><td>scientificProjectLead</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="ce02eefa-e74a-43da-8fb9-79b91e06a74a"></a>2.1.2.4.3.43 Field **\[0\]**

##### 2.1.2.4.3.43.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image148.png?raw=true)

##### 2.1.2.4.3.43.2 **\[0\]** Hierarchy

Parent field: **scientificProjectLead**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6036ff65-be07-4401-a0ba-2f52a0ffb51f class="margin-NaN">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fccf89e8-c156-4505-8635-63055ba4bf13 class="margin-NaN">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#588ec6f8-24a3-4799-9c01-ecb2b6ea5804 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.43.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="6036ff65-be07-4401-a0ba-2f52a0ffb51f"></a>2.1.2.4.3.44 Field **firstName**

##### 2.1.2.4.3.44.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image149.png?raw=true)

##### 2.1.2.4.3.44.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="fccf89e8-c156-4505-8635-63055ba4bf13"></a>2.1.2.4.3.45 Field **lastName**

##### 2.1.2.4.3.45.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image150.png?raw=true)

##### 2.1.2.4.3.45.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="588ec6f8-24a3-4799-9c01-ecb2b6ea5804"></a>2.1.2.4.3.46 Field **ids**

##### 2.1.2.4.3.46.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image151.png?raw=true)

##### 2.1.2.4.3.46.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#7f251443-0160-4dff-a43c-4a13e5d646dd class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.46.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="7f251443-0160-4dff-a43c-4a13e5d646dd"></a>2.1.2.4.3.47 Field **\[0\]**

##### 2.1.2.4.3.47.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image152.png?raw=true)

##### 2.1.2.4.3.47.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3c66028a-408c-4d28-a02b-6657d77890af class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.47.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="3c66028a-408c-4d28-a02b-6657d77890af"></a>2.1.2.4.3.48 Field **anyOf**

##### 2.1.2.4.3.48.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image153.png?raw=true)

##### 2.1.2.4.3.48.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cb2ebf6b-1a2a-4658-a674-62c3fffabad0 class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f6de375a-4a7d-47c4-b54f-7fa4294400dd class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9b06f9bb-3f03-47cd-8506-7e65c72e98d6 class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.48.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="cb2ebf6b-1a2a-4658-a674-62c3fffabad0"></a>2.1.2.4.3.49 Field **\[0\] houseID**

##### 2.1.2.4.3.49.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image154.png?raw=true)

##### 2.1.2.4.3.49.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#df5e024a-b9bc-466c-b711-373dd8369063 class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.49.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="df5e024a-b9bc-466c-b711-373dd8369063"></a>2.1.2.4.3.50 Field **houseID**

##### 2.1.2.4.3.50.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image155.png?raw=true)

##### 2.1.2.4.3.50.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="f6de375a-4a7d-47c4-b54f-7fa4294400dd"></a>2.1.2.4.3.51 Field **\[1\] ORCiD**

##### 2.1.2.4.3.51.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image156.png?raw=true)

##### 2.1.2.4.3.51.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dcdd82c-248d-4871-ad07-7040cc34655d class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.51.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="5dcdd82c-248d-4871-ad07-7040cc34655d"></a>2.1.2.4.3.52 Field **ORCiD**

##### 2.1.2.4.3.52.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image157.png?raw=true)

##### 2.1.2.4.3.52.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="9b06f9bb-3f03-47cd-8506-7e65c72e98d6"></a>2.1.2.4.3.53 Field **\[2\] anyOtherID**

##### 2.1.2.4.3.53.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image158.png?raw=true)

##### 2.1.2.4.3.53.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#bda4e3bf-0a90-4691-80b1-34412746865f class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.53.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="bda4e3bf-0a90-4691-80b1-34412746865f"></a>2.1.2.4.3.54 Field **id**

##### 2.1.2.4.3.54.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image159.png?raw=true)

##### 2.1.2.4.3.54.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="b8209ee9-62d4-408d-9570-ea1f158285a8"></a>2.1.2.4.3.55 Field **keywords**

##### 2.1.2.4.3.55.1 **keywords** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image160.png?raw=true)

##### 2.1.2.4.3.55.2 **keywords** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#63f684a7-bf03-4706-8734-80d9dbe6c92f class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.55.3 **keywords** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>keywords</td></tr><tr><td>Technical name</td><td>keywords</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="63f684a7-bf03-4706-8734-80d9dbe6c92f"></a>2.1.2.4.3.56 Field **\[0\]**

##### 2.1.2.4.3.56.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image161.png?raw=true)

##### 2.1.2.4.3.56.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="6dee2d28-520a-4b24-82b6-f9bd67fe00f0"></a>2.1.2.4.3.57 Field **disciplinaryResearchAreas**

##### 2.1.2.4.3.57.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image162.png?raw=true)

##### 2.1.2.4.3.57.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3027d0ab-d9eb-4777-81e1-d5ab9a70c22d class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.57.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="3027d0ab-d9eb-4777-81e1-d5ab9a70c22d"></a>2.1.2.4.3.58 Field **\[0\]**

##### 2.1.2.4.3.58.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image163.png?raw=true)

##### 2.1.2.4.3.58.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="01d090e2-8995-4c67-b0c7-fedceb80f587"></a>2.1.2.4.3.59 Field **subjects**

##### 2.1.2.4.3.59.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image164.png?raw=true)

##### 2.1.2.4.3.59.2 **subjects** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#bfa8235f-44f6-456a-8dc3-a0b2d9cbaea2 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.59.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="bfa8235f-44f6-456a-8dc3-a0b2d9cbaea2"></a>2.1.2.4.3.60 Field **\[0\]**

##### 2.1.2.4.3.60.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image165.png?raw=true)

##### 2.1.2.4.3.60.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="fb51a340-e2a8-4f10-88d8-4f8e762237c6"></a>2.1.2.4.3.61 Field **description**

##### 2.1.2.4.3.61.1 **description** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image166.png?raw=true)

##### 2.1.2.4.3.61.2 **description** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>description</td></tr><tr><td>Technical name</td><td>description</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="135fc519-1bb9-4646-8ecc-ba4ff7f8b8cd"></a>2.1.2.4.3.62 Field **projectObjective**

##### 2.1.2.4.3.62.1 **projectObjective** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image167.png?raw=true)

##### 2.1.2.4.3.62.2 **projectObjective** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectObjective</td></tr><tr><td>Technical name</td><td>projectObjective</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="4eb09caa-11b3-464c-bf18-3cd245c4b3c3"></a>2.1.2.4.3.63 Field **funderCategories**

##### 2.1.2.4.3.63.1 **funderCategories** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image168.png?raw=true)

##### 2.1.2.4.3.63.2 **funderCategories** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e1711402-ee75-4f0d-984a-c74e02b0201a class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.63.3 **funderCategories** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funderCategories</td></tr><tr><td>Technical name</td><td>funderCategories</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="e1711402-ee75-4f0d-984a-c74e02b0201a"></a>2.1.2.4.3.64 Field **\[0\]**

##### 2.1.2.4.3.64.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image169.png?raw=true)

##### 2.1.2.4.3.64.2 **\[0\]** Hierarchy

Parent field: **funderCategories**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#4368a3e4-16ae-47f5-b282-8b5b4e4b2fb2 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b3ce7371-c2ca-4c61-a1c1-1867464cb344 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.64.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="4368a3e4-16ae-47f5-b282-8b5b4e4b2fb2"></a>2.1.2.4.3.65 Field **name**

##### 2.1.2.4.3.65.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image170.png?raw=true)

##### 2.1.2.4.3.65.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="b3ce7371-c2ca-4c61-a1c1-1867464cb344"></a>2.1.2.4.3.66 Field **ids**

##### 2.1.2.4.3.66.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image171.png?raw=true)

##### 2.1.2.4.3.66.2 **ids** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#aa1feb8a-93f7-4f89-8f34-1bb93922f18f class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.66.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="aa1feb8a-93f7-4f89-8f34-1bb93922f18f"></a>2.1.2.4.3.67 Field **\[0\]**

##### 2.1.2.4.3.67.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image172.png?raw=true)

##### 2.1.2.4.3.67.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#d7cd4eeb-20ed-42f6-95a4-fee58dbfdc49 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.67.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="d7cd4eeb-20ed-42f6-95a4-fee58dbfdc49"></a>2.1.2.4.3.68 Field **anyOf**

##### 2.1.2.4.3.68.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image173.png?raw=true)

##### 2.1.2.4.3.68.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8a9966c3-f793-4183-8869-803c278309e5 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#474dcf40-8b4c-4cb3-a026-88908c9bf665 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.68.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="8a9966c3-f793-4183-8869-803c278309e5"></a>2.1.2.4.3.69 Field **\[0\] houseId**

##### 2.1.2.4.3.69.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image174.png?raw=true)

##### 2.1.2.4.3.69.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#498619cd-1532-4d59-95f3-c1ca036a993a class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.69.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="498619cd-1532-4d59-95f3-c1ca036a993a"></a>2.1.2.4.3.70 Field **houseId**

##### 2.1.2.4.3.70.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image175.png?raw=true)

##### 2.1.2.4.3.70.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="474dcf40-8b4c-4cb3-a026-88908c9bf665"></a>2.1.2.4.3.71 Field **\[1\] anyOtherID**

##### 2.1.2.4.3.71.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image176.png?raw=true)

##### 2.1.2.4.3.71.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#71e111b6-7efb-49e2-9224-0899df32ccd6 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.71.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="71e111b6-7efb-49e2-9224-0899df32ccd6"></a>2.1.2.4.3.72 Field **anyOtherID**

##### 2.1.2.4.3.72.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image177.png?raw=true)

##### 2.1.2.4.3.72.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="6fb5114d-3a8e-4346-8957-b902a9314849"></a>2.1.2.4.3.73 Field **funders**

##### 2.1.2.4.3.73.1 **funders** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image178.png?raw=true)

##### 2.1.2.4.3.73.2 **funders** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1d544b33-207b-4837-9c25-37aeee1bc7b6 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.73.3 **funders** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funders</td></tr><tr><td>Technical name</td><td>funders</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1d544b33-207b-4837-9c25-37aeee1bc7b6"></a>2.1.2.4.3.74 Field **\[0\]**

##### 2.1.2.4.3.74.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image179.png?raw=true)

##### 2.1.2.4.3.74.2 **\[0\]** Hierarchy

Parent field: **funders**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0c43cb06-fe61-43f7-9b3d-c2c1fb2f659a class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#522bcce3-5c54-487d-b716-bf7a96724332 class="margin-NaN">country</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcf211e2-c1af-483b-84b0-32989b2c74f9 class="margin-NaN">funderAbbrevation</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#8b507411-127f-48fc-85fa-248c3b0c4f6e class="margin-NaN">fundRef</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5f7c84ba-431f-4d08-b34f-c9a77a9d4f54 class="margin-NaN">ror</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e4e92c1b-5939-4dd0-bbf6-04be035e0088 class="margin-NaN">isoCountryCode</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.74.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="0c43cb06-fe61-43f7-9b3d-c2c1fb2f659a"></a>2.1.2.4.3.75 Field **name**

##### 2.1.2.4.3.75.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image180.png?raw=true)

##### 2.1.2.4.3.75.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="522bcce3-5c54-487d-b716-bf7a96724332"></a>2.1.2.4.3.76 Field **country**

##### 2.1.2.4.3.76.1 **country** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image181.png?raw=true)

##### 2.1.2.4.3.76.2 **country** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>country</td></tr><tr><td>Technical name</td><td>country</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="bcf211e2-c1af-483b-84b0-32989b2c74f9"></a>2.1.2.4.3.77 Field **funderAbbrevation**

##### 2.1.2.4.3.77.1 **funderAbbrevation** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image182.png?raw=true)

##### 2.1.2.4.3.77.2 **funderAbbrevation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>funderAbbrevation</td></tr><tr><td>Technical name</td><td>funderAbbrevation</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="8b507411-127f-48fc-85fa-248c3b0c4f6e"></a>2.1.2.4.3.78 Field **fundRef**

##### 2.1.2.4.3.78.1 **fundRef** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image183.png?raw=true)

##### 2.1.2.4.3.78.2 **fundRef** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>fundRef</td></tr><tr><td>Technical name</td><td>fundRef</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="5f7c84ba-431f-4d08-b34f-c9a77a9d4f54"></a>2.1.2.4.3.79 Field **ror**

##### 2.1.2.4.3.79.1 **ror** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image184.png?raw=true)

##### 2.1.2.4.3.79.2 **ror** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ror</td></tr><tr><td>Technical name</td><td>ror</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e4e92c1b-5939-4dd0-bbf6-04be035e0088"></a>2.1.2.4.3.80 Field **isoCountryCode**

##### 2.1.2.4.3.80.1 **isoCountryCode** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image185.png?raw=true)

##### 2.1.2.4.3.80.2 **isoCountryCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>isoCountryCode</td></tr><tr><td>Technical name</td><td>isoCountryCode</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a0b0b282-b748-40f7-8626-b1d47cb4b148"></a>2.1.2.4.3.81 Field **projectStart**

##### 2.1.2.4.3.81.1 **projectStart** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image186.png?raw=true)

##### 2.1.2.4.3.81.2 **projectStart** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectStart</td></tr><tr><td>Technical name</td><td>projectStart</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="12a92436-510c-4478-bca7-6cf618e1de30"></a>2.1.2.4.3.82 Field **projectEnd**

##### 2.1.2.4.3.82.1 **projectEnd** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image187.png?raw=true)

##### 2.1.2.4.3.82.2 **projectEnd** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectEnd</td></tr><tr><td>Technical name</td><td>projectEnd</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="ba6cfd29-20af-4bde-bace-157f3e7ac57d"></a>2.1.2.4.3.83 Field **thirdPartyFunding**

##### 2.1.2.4.3.83.1 **thirdPartyFunding** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image188.png?raw=true)

##### 2.1.2.4.3.83.2 **thirdPartyFunding** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>thirdPartyFunding</td></tr><tr><td>Technical name</td><td>thirdPartyFunding</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Unit</td><td>euro</td></tr><tr><td>Default</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="904a92e1-f2cb-4e71-b200-01dee837e223"></a>2.1.2.4.3.84 Field **grantAmount**

##### 2.1.2.4.3.84.1 **grantAmount** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image189.png?raw=true)

##### 2.1.2.4.3.84.2 **grantAmount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>grantAmount</td></tr><tr><td>Technical name</td><td>grantAmount</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Unit</td><td>euro</td></tr><tr><td>Default</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="2e47399c-42a8-492f-9fc6-7530030c1268"></a>2.1.2.4.3.85 Field **projectStatus**

##### 2.1.2.4.3.85.1 **projectStatus** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image190.png?raw=true)

##### 2.1.2.4.3.85.2 **projectStatus** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>projectStatus</td></tr><tr><td>Technical name</td><td>projectStatus</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>open,closed,proposal submitted,rejected</td></tr></tbody></table>

### <a id="b0ebab6d-1eb2-4a7c-90f2-9a4dfc363503"></a>2.1.2.4.3.86 Field **webpages**

##### 2.1.2.4.3.86.1 **webpages** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image191.png?raw=true)

##### 2.1.2.4.3.86.2 **webpages** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f4406aa6-3992-4a62-9b62-2fe50d2ca0ac class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.86.3 **webpages** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>webpages</td></tr><tr><td>Technical name</td><td>webpages</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f4406aa6-3992-4a62-9b62-2fe50d2ca0ac"></a>2.1.2.4.3.87 Field **\[0\]**

##### 2.1.2.4.3.87.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image192.png?raw=true)

##### 2.1.2.4.3.87.2 **\[0\]** Hierarchy

Parent field: **webpages**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#45e7c62c-945a-41fd-bceb-f1dd18acb3da class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#faf46be6-4606-45ad-885c-321bf04e879c class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.87.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="45e7c62c-945a-41fd-bceb-f1dd18acb3da"></a>2.1.2.4.3.88 Field **name**

##### 2.1.2.4.3.88.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image193.png?raw=true)

##### 2.1.2.4.3.88.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="faf46be6-4606-45ad-885c-321bf04e879c"></a>2.1.2.4.3.89 Field **url**

##### 2.1.2.4.3.89.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image194.png?raw=true)

##### 2.1.2.4.3.89.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="0378dbef-814c-4e29-824e-d1e42bc6bf2a"></a>2.1.2.4.3.90 Field **repositories**

##### 2.1.2.4.3.90.1 **repositories** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image195.png?raw=true)

##### 2.1.2.4.3.90.2 **repositories** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f5af3d2a-ad69-4e1b-85b2-129c97c4e3b3 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.90.3 **repositories** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>repositories</td></tr><tr><td>Technical name</td><td>repositories</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="f5af3d2a-ad69-4e1b-85b2-129c97c4e3b3"></a>2.1.2.4.3.91 Field **\[0\]**

##### 2.1.2.4.3.91.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image196.png?raw=true)

##### 2.1.2.4.3.91.2 **\[0\]** Hierarchy

Parent field: **repositories**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#12d19dd0-d452-4553-bc54-b2b9d9957b2b class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#fe479747-e215-4425-bd26-dae435e96841 class="margin-NaN">url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.91.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="12d19dd0-d452-4553-bc54-b2b9d9957b2b"></a>2.1.2.4.3.92 Field **name**

##### 2.1.2.4.3.92.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image197.png?raw=true)

##### 2.1.2.4.3.92.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="fe479747-e215-4425-bd26-dae435e96841"></a>2.1.2.4.3.93 Field **url**

##### 2.1.2.4.3.93.1 **url** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image198.png?raw=true)

##### 2.1.2.4.3.93.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td>url</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>uri</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="b9661cd0-49df-4455-811c-19ec49d35441"></a>2.1.2.4.3.94 Field **interDisciplinaryResearchAreas**

##### 2.1.2.4.3.94.1 **interDisciplinaryResearchAreas** Tree Diagram

##### 2.1.2.4.3.94.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Project**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#53e21acd-dcd7-4f96-8933-87cd832e0a92 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3.94.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="53e21acd-dcd7-4f96-8933-87cd832e0a92"></a>2.1.2.4.3.95 Field **\[0\]**

##### 2.1.2.4.3.95.1 **\[0\]** Tree Diagram

##### 2.1.2.4.3.95.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 2.1.2.4.4 **Project** JSON Schema

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

##### 2.1.2.4.5 **Project** JSON data

```
{
    "name": "Lorem",
    "address": "Lorem",
    "phone": "+2 3 73 68232 14 40 3827 2 448 4 37 3",
    "emails": [
        "/4X5sZghATBpO+ETdgCDjYBal.+T#S%fdlv^lzCv_E.8ES}f-o0TYy_K~Nd51J?1=.TPnNXmqhLA9`JRpnrI4roE.Aacw'h!GZ.*ygY/Q4T4wkhrVQU#n-%8PZz.1*9medukP%i#rql&g!YV9}n`GA0l&-.w=ioXZBTHUyi`kjTP{lo.J&nLK1eK5?MGF+_hg=.+7V3Sxh.-v`U6SeMrKgUl.&Zl0s_0FbrmjM4Z`TdssoAAh=PcUGXU.4!*'.uTvtPvEV7Xy8=gseT9$x^!%qt{&s{c.D31+fxF4OzsnD$R$wJr=3q-tMnY5Ya.LBnB.TSyqT6D`~PzuBDUpdWLClbdqHzXB^C5.ok|jIKt|GH'H94sdx.Vrat.bW.SSzaPX=QTq&vC.&a+nc/+e.b_XY/P6$fXycIu$8uP7oBsO.~d$iHYWyW&b?D'5aM=VzWxGSxdO7.MYZ4~dIv'FsoygIRcG~iB}#2NLqWr@o.d.h.q.x.tpgya9k3pu1oldcllvxw2oke1bfn5xn2gkp5lbzwi8w98f.a.b.sm0tfvevrurrz5rf1b3p94t03-pnwsgz-dn95hdj7vg5mrbh-xj9t.l.b6yy3nw4xi9y-n78xvjc.t.l.8zl4jukxk.ranbl335d8x0j5r8fw9qyyuizrmj8hl0zzn7k.65a33y050lirtojqv6ycw0yfg4g5-tul-28c40s.dz6n53bhbri-0-53otml9t6cqm3pluvuf1x.x.fx40fhrt-cje5qpcip5dm8pzk-j7uqm3783jc8-9g.j.l.qv-xz7bgm0yh0tflbok16p5u4dd-7vnwvrufa8zu-bzilxzjy0l81v6imw.i.lckrpf/i"
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

### <a id="482b0df2-d80e-4871-89e5-ea8b028eabb4"></a>2.1.2.5 Document **Publication**

##### 2.1.2.5.1 **Publication** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image199.png?raw=true)

##### 2.1.2.5.2 **Publication** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>Publication</td></tr><tr><td>Technical name</td><td>publication</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3 **Publication** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#09164ad6-e8b6-4340-acb7-adef288d8211 class="margin-0">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7eba1665-4ad8-4dae-b1f8-f94d96561ee6 class="margin-0">documentType</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#4869b255-16c9-4405-bcdf-d2cf66f133b1 class="margin-0">abstract</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e28bc9b8-37a2-4c58-b313-07503eb95b51 class="margin-0">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#cfc23b28-c88b-4884-bed4-dfbaaccb1932 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#b1fbc312-1341-4029-a925-3d67ff53a1e4 class="margin-10">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#07d18606-efc1-4aae-9f2a-0574bf494464 class="margin-15">[0]&nbsp;doi</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e59862a6-6271-4212-87c8-7e6f18411724 class="margin-20">doi</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7fb373c-c2fc-4e9f-835f-3f948d782fae class="margin-15">[1]&nbsp;Scopus&nbsp;EID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#419143f0-db1f-406a-8ec9-d9b7f3b9d3cd class="margin-20">Scopus&nbsp;EID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#71605cad-6652-485a-a666-04ddc3afe4dd class="margin-15">[2]&nbsp;WOSut</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3e65aa82-318c-4bec-9cba-a9b0de8f5b62 class="margin-20">WOSut</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ae6caaf3-6cc9-44ee-8c64-f8da1937b8c8 class="margin-15">[3]&nbsp;PMID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#81e88506-1c4b-45bd-ab61-9a6366dcf4db class="margin-20">PMID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4382e6d5-5291-49f2-baee-d749bf51a525 class="margin-15">[4]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#504421b3-fde9-44a9-9142-400cdb196374 class="margin-20">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e1f1348-049a-4544-9fdc-0047e597a61a class="margin-0">startPage</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5c60c845-58d4-4e63-9de5-62a27feefebb class="margin-0">endPage</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#d38e61d5-7901-4758-b162-8d09658b3a8d class="margin-0">volume</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#1ca6b056-b981-42ad-af80-4fe32367c371 class="margin-0">year</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7457521d-ea4a-4042-b48f-e016ac48d9e7 class="margin-0">journal</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e926187f-4535-4d78-bfa7-b12456b5469f class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f807f92d-73d5-48c9-8f92-4cf93efc88e5 class="margin-5">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c0c46263-6317-412f-8a19-51f90adf3d2c class="margin-10">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1ee9ac74-42cd-4c55-bae4-19728bad3f7f class="margin-15">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5415f2cb-cc41-4c67-b49e-402529906bf7 class="margin-20">[0]&nbsp;houseId</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#43718a1a-012b-4ba3-9b51-3a075dcc35d8 class="margin-25">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#55b16a08-ad24-4fd8-a28c-77a1d5fed8c6 class="margin-20">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a2310783-2d05-487f-9d6b-f5a619eb10eb class="margin-25">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1c4b0128-abb1-406a-868e-c2dcb2abaf6f class="margin-0">publicationType</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#e1946cc6-9e07-4e85-b6ac-d1ac76755911 class="margin-0">publisher</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#972ea74f-dded-4135-841a-c214644d1501 class="margin-0">subjects</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr><tr><td><a href=#f896b04a-9fcd-45e0-828c-e3fda6e69f7c class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#52ab06ba-2c0f-4f16-849a-ffe938ffe104 class="margin-0">disciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#40eecc20-d872-4528-8372-ea3a9428eec7 class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#51425fef-d42b-4ef5-b60e-0aafa50d09bc class="margin-0">keywords</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c7b245f0-fe00-495e-9c1b-c6c5c47331ce class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f4354720-c52f-4782-92f0-ab0a18a7aa06 class="margin-0">organisationalUnit</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#5a126229-898f-4601-bb24-71e513b45bf7 class="margin-0">presentedAtConference</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#93aed1ca-b642-432f-97f8-30bbb3b8b224 class="margin-5">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#431be31d-7c93-46fc-a8a2-a36af0d26fb4 class="margin-5">location</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a1c8ae46-8f83-4f99-b545-2d664a1afb9f class="margin-5">date</a></td><td class="no-break-word">date</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a634c0c9-6b02-4149-a019-a54b5ff6d37d class="margin-0">typeOfThesis</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#786c0a7d-9d2f-4e9f-acdf-d01e7083276e class="margin-0">authors</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr><tr><td><a href=#60805094-84a5-46e3-90d4-03ce16089323 class="margin-5">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#eb00ac98-ef6a-432d-b5ce-edecfc8e3db4 class="margin-10">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#42b3ee7a-49ef-4542-9d45-8f6a1078b7d7 class="margin-10">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8d25a194-f221-49bb-ba7a-6a6ae27949eb class="margin-10">ids(1)</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8baefd56-774b-46cf-8493-45d753d47af7 class="margin-15">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f53f7f80-506b-4896-83b7-4b0c7b7f854b class="margin-20">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#42ae5c4c-ccf9-4bf5-98ac-0d9c4af96e77 class="margin-25">[0]&nbsp;houseID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a34ac963-748a-482e-a073-0296b6471780 class="margin-30">houseID</a></td><td class="no-break-word">string</td><td>false</td><td>dk</td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0891bfd1-fb22-4f61-ba5a-e3dbebe9933e class="margin-25">[1]&nbsp;ORCiD</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cad9334e-2df0-4d72-90e4-ed3a8dbc2783 class="margin-30">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c8115c7d-ae48-40a5-ac41-59dd05ecf765 class="margin-25">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#6a2a1cfc-d2fa-4407-afe3-c5bc18be1485 class="margin-30">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4599814e-9f1a-4ba2-8fe3-f66184babfa7 class="margin-10">listingRank</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#12160c87-e139-49c4-8e6a-d4960b6ea22b class="margin-10">correspondingAuthor</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3ba4dd26-a539-41d6-8066-ca832f7f88d9 class="margin-0">interDisciplinaryResearchAreas</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#56267fe0-0364-420b-9ca5-57ce997216cd class="margin-5">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="09164ad6-e8b6-4340-acb7-adef288d8211"></a>2.1.2.5.3.1 Field **name**

##### 2.1.2.5.3.1.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image200.png?raw=true)

##### 2.1.2.5.3.1.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="7eba1665-4ad8-4dae-b1f8-f94d96561ee6"></a>2.1.2.5.3.2 Field **documentType**

##### 2.1.2.5.3.2.1 **documentType** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image201.png?raw=true)

##### 2.1.2.5.3.2.2 **documentType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>documentType</td></tr><tr><td>Technical name</td><td>documentType</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Bibliographie, Editorial, Letter to the Editor, Quellenedition, Review, Rezension, Wissenschaftlicher Artikel, Sonstiger Dokumenttyp</td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="4869b255-16c9-4405-bcdf-d2cf66f133b1"></a>2.1.2.5.3.3 Field **abstract**

##### 2.1.2.5.3.3.1 **abstract** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image202.png?raw=true)

##### 2.1.2.5.3.3.2 **abstract** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>abstract</td></tr><tr><td>Technical name</td><td>abstract</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="e28bc9b8-37a2-4c58-b313-07503eb95b51"></a>2.1.2.5.3.4 Field **ids**

##### 2.1.2.5.3.4.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image203.png?raw=true)

##### 2.1.2.5.3.4.2 **ids** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cfc23b28-c88b-4884-bed4-dfbaaccb1932 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.4.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="cfc23b28-c88b-4884-bed4-dfbaaccb1932"></a>2.1.2.5.3.5 Field **\[0\]**

##### 2.1.2.5.3.5.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image204.png?raw=true)

##### 2.1.2.5.3.5.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#b1fbc312-1341-4029-a925-3d67ff53a1e4 class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.5.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="b1fbc312-1341-4029-a925-3d67ff53a1e4"></a>2.1.2.5.3.6 Field **anyOf**

##### 2.1.2.5.3.6.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image205.png?raw=true)

##### 2.1.2.5.3.6.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#07d18606-efc1-4aae-9f2a-0574bf494464 class="margin-NaN">[0]&nbsp;doi</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a7fb373c-c2fc-4e9f-835f-3f948d782fae class="margin-NaN">[1]&nbsp;Scopus&nbsp;EID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#71605cad-6652-485a-a666-04ddc3afe4dd class="margin-NaN">[2]&nbsp;WOSut</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#ae6caaf3-6cc9-44ee-8c64-f8da1937b8c8 class="margin-NaN">[3]&nbsp;PMID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4382e6d5-5291-49f2-baee-d749bf51a525 class="margin-NaN">[4]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.6.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="07d18606-efc1-4aae-9f2a-0574bf494464"></a>2.1.2.5.3.7 Field **\[0\] doi**

##### 2.1.2.5.3.7.1 **\[0\] doi** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image206.png?raw=true)

##### 2.1.2.5.3.7.2 **\[0\] doi** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e59862a6-6271-4212-87c8-7e6f18411724 class="margin-NaN">doi</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.7.3 **\[0\] doi** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>doi</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="e59862a6-6271-4212-87c8-7e6f18411724"></a>2.1.2.5.3.8 Field **doi**

##### 2.1.2.5.3.8.1 **doi** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image207.png?raw=true)

##### 2.1.2.5.3.8.2 **doi** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>doi</td></tr><tr><td>Technical name</td><td>doi</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a7fb373c-c2fc-4e9f-835f-3f948d782fae"></a>2.1.2.5.3.9 Field **\[1\] Scopus EID**

##### 2.1.2.5.3.9.1 **\[1\] Scopus EID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image208.png?raw=true)

##### 2.1.2.5.3.9.2 **\[1\] Scopus EID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#419143f0-db1f-406a-8ec9-d9b7f3b9d3cd class="margin-NaN">Scopus&nbsp;EID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.9.3 **\[1\] Scopus EID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>Scopus EID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="419143f0-db1f-406a-8ec9-d9b7f3b9d3cd"></a>2.1.2.5.3.10 Field **Scopus EID**

##### 2.1.2.5.3.10.1 **Scopus EID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image209.png?raw=true)

##### 2.1.2.5.3.10.2 **Scopus EID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Scopus EID</td></tr><tr><td>Technical name</td><td>scopusEID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="71605cad-6652-485a-a666-04ddc3afe4dd"></a>2.1.2.5.3.11 Field **\[2\] WOSut**

##### 2.1.2.5.3.11.1 **\[2\] WOSut** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image210.png?raw=true)

##### 2.1.2.5.3.11.2 **\[2\] WOSut** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#3e65aa82-318c-4bec-9cba-a9b0de8f5b62 class="margin-NaN">WOSut</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.11.3 **\[2\] WOSut** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>WOSut</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="3e65aa82-318c-4bec-9cba-a9b0de8f5b62"></a>2.1.2.5.3.12 Field **WOSut**

##### 2.1.2.5.3.12.1 **WOSut** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image211.png?raw=true)

##### 2.1.2.5.3.12.2 **WOSut** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>WOSut</td></tr><tr><td>Technical name</td><td>WOSut</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="ae6caaf3-6cc9-44ee-8c64-f8da1937b8c8"></a>2.1.2.5.3.13 Field **\[3\] PMID**

##### 2.1.2.5.3.13.1 **\[3\] PMID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image212.png?raw=true)

##### 2.1.2.5.3.13.2 **\[3\] PMID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#81e88506-1c4b-45bd-ab61-9a6366dcf4db class="margin-NaN">PMID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.13.3 **\[3\] PMID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>PMID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="81e88506-1c4b-45bd-ab61-9a6366dcf4db"></a>2.1.2.5.3.14 Field **PMID**

##### 2.1.2.5.3.14.1 **PMID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image213.png?raw=true)

##### 2.1.2.5.3.14.2 **PMID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>PMID</td></tr><tr><td>Technical name</td><td>PMID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4382e6d5-5291-49f2-baee-d749bf51a525"></a>2.1.2.5.3.15 Field **\[4\] anyOtherID**

##### 2.1.2.5.3.15.1 **\[4\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image214.png?raw=true)

##### 2.1.2.5.3.15.2 **\[4\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#504421b3-fde9-44a9-9142-400cdb196374 class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.15.3 **\[4\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="504421b3-fde9-44a9-9142-400cdb196374"></a>2.1.2.5.3.16 Field **anyOtherID**

##### 2.1.2.5.3.16.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image215.png?raw=true)

##### 2.1.2.5.3.16.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="5e1f1348-049a-4544-9fdc-0047e597a61a"></a>2.1.2.5.3.17 Field **startPage**

##### 2.1.2.5.3.17.1 **startPage** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image216.png?raw=true)

##### 2.1.2.5.3.17.2 **startPage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>startPage</td></tr><tr><td>Technical name</td><td>startPage</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="5c60c845-58d4-4e63-9de5-62a27feefebb"></a>2.1.2.5.3.18 Field **endPage**

##### 2.1.2.5.3.18.1 **endPage** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image217.png?raw=true)

##### 2.1.2.5.3.18.2 **endPage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>endPage</td></tr><tr><td>Technical name</td><td>endPage</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="d38e61d5-7901-4758-b162-8d09658b3a8d"></a>2.1.2.5.3.19 Field **volume**

##### 2.1.2.5.3.19.1 **volume** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image218.png?raw=true)

##### 2.1.2.5.3.19.2 **volume** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>volume</td></tr><tr><td>Technical name</td><td>volume</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="1ca6b056-b981-42ad-af80-4fe32367c371"></a>2.1.2.5.3.20 Field **year**

##### 2.1.2.5.3.20.1 **year** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image219.png?raw=true)

##### 2.1.2.5.3.20.2 **year** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>year</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr></tbody></table>

### <a id="7457521d-ea4a-4042-b48f-e016ac48d9e7"></a>2.1.2.5.3.21 Field **journal**

##### 2.1.2.5.3.21.1 **journal** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image220.png?raw=true)

##### 2.1.2.5.3.21.2 **journal** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e926187f-4535-4d78-bfa7-b12456b5469f class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f807f92d-73d5-48c9-8f92-4cf93efc88e5 class="margin-NaN">ids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.21.3 **journal** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>journal</td></tr><tr><td>Technical name</td><td>journal</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="e926187f-4535-4d78-bfa7-b12456b5469f"></a>2.1.2.5.3.22 Field **name**

##### 2.1.2.5.3.22.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image221.png?raw=true)

##### 2.1.2.5.3.22.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="f807f92d-73d5-48c9-8f92-4cf93efc88e5"></a>2.1.2.5.3.23 Field **ids**

##### 2.1.2.5.3.23.1 **ids** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image222.png?raw=true)

##### 2.1.2.5.3.23.2 **ids** Hierarchy

Parent field: **journal**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c0c46263-6317-412f-8a19-51f90adf3d2c class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.23.3 **ids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids</td></tr><tr><td>Technical name</td><td>ids</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="c0c46263-6317-412f-8a19-51f90adf3d2c"></a>2.1.2.5.3.24 Field **\[0\]**

##### 2.1.2.5.3.24.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image223.png?raw=true)

##### 2.1.2.5.3.24.2 **\[0\]** Hierarchy

Parent field: **ids**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1ee9ac74-42cd-4c55-bae4-19728bad3f7f class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.24.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="1ee9ac74-42cd-4c55-bae4-19728bad3f7f"></a>2.1.2.5.3.25 Field **anyOf**

##### 2.1.2.5.3.25.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image224.png?raw=true)

##### 2.1.2.5.3.25.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5415f2cb-cc41-4c67-b49e-402529906bf7 class="margin-NaN">[0]&nbsp;houseId</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#55b16a08-ad24-4fd8-a28c-77a1d5fed8c6 class="margin-NaN">[1]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.25.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="5415f2cb-cc41-4c67-b49e-402529906bf7"></a>2.1.2.5.3.26 Field **\[0\] houseId**

##### 2.1.2.5.3.26.1 **\[0\] houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image225.png?raw=true)

##### 2.1.2.5.3.26.2 **\[0\] houseId** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#43718a1a-012b-4ba3-9b51-3a075dcc35d8 class="margin-NaN">houseId</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.26.3 **\[0\] houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="43718a1a-012b-4ba3-9b51-3a075dcc35d8"></a>2.1.2.5.3.27 Field **houseId**

##### 2.1.2.5.3.27.1 **houseId** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image226.png?raw=true)

##### 2.1.2.5.3.27.2 **houseId** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseId</td></tr><tr><td>Technical name</td><td>houseId</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Foreign collection</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Foreign field</td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>houseId</a></td></tr><tr><td>Relationship type</td><td>Foreign Key</td></tr></tbody></table>

### <a id="55b16a08-ad24-4fd8-a28c-77a1d5fed8c6"></a>2.1.2.5.3.28 Field **\[1\] anyOtherID**

##### 2.1.2.5.3.28.1 **\[1\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image227.png?raw=true)

##### 2.1.2.5.3.28.2 **\[1\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a2310783-2d05-487f-9d6b-f5a619eb10eb class="margin-NaN">anyOtherID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.28.3 **\[1\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="a2310783-2d05-487f-9d6b-f5a619eb10eb"></a>2.1.2.5.3.29 Field **anyOtherID**

##### 2.1.2.5.3.29.1 **anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image228.png?raw=true)

##### 2.1.2.5.3.29.2 **anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>anyOtherID</td></tr><tr><td>Technical name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="1c4b0128-abb1-406a-868e-c2dcb2abaf6f"></a>2.1.2.5.3.30 Field **publicationType**

##### 2.1.2.5.3.30.1 **publicationType** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image229.png?raw=true)

##### 2.1.2.5.3.30.2 **publicationType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publicationType</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>Buch, Artikel, Konferenzbeitrag, Software, Herausgeberschaft eines Sonderhefts einer Zeitschrift, Forschungsdaten, Beitrag in nicht-wissenschaftlichen Medien, Beitrag in wissenschaftlichen Blogs, Arbeitspapier/Forschungsbericht, Integrierende Ressource, Sonstiger Publikationstyp</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="e1946cc6-9e07-4e85-b6ac-d1ac76755911"></a>2.1.2.5.3.31 Field **publisher**

##### 2.1.2.5.3.31.1 **publisher** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image230.png?raw=true)

##### 2.1.2.5.3.31.2 **publisher** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publisher</td></tr><tr><td>Technical name</td><td>publisher</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="972ea74f-dded-4135-841a-c214644d1501"></a>2.1.2.5.3.32 Field **subjects**

##### 2.1.2.5.3.32.1 **subjects** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image231.png?raw=true)

##### 2.1.2.5.3.32.2 **subjects** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f896b04a-9fcd-45e0-828c-e3fda6e69f7c class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.32.3 **subjects** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>subjects</td></tr><tr><td>Technical name</td><td>subjects</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF; Grundlage für die Fachzuordnung sind die Fächersystematiken des Statistischen Bundesamtes.</p></div></td></tr></tbody></table>

### <a id="f896b04a-9fcd-45e0-828c-e3fda6e69f7c"></a>2.1.2.5.3.33 Field **\[0\]**

##### 2.1.2.5.3.33.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image232.png?raw=true)

##### 2.1.2.5.3.33.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="52ab06ba-2c0f-4f16-849a-ffe938ffe104"></a>2.1.2.5.3.34 Field **disciplinaryResearchAreas**

##### 2.1.2.5.3.34.1 **disciplinaryResearchAreas** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image233.png?raw=true)

##### 2.1.2.5.3.34.2 **disciplinaryResearchAreas** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#40eecc20-d872-4528-8372-ea3a9428eec7 class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.34.3 **disciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>disciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="40eecc20-d872-4528-8372-ea3a9428eec7"></a>2.1.2.5.3.35 Field **\[0\]**

##### 2.1.2.5.3.35.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image234.png?raw=true)

##### 2.1.2.5.3.35.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="51425fef-d42b-4ef5-b60e-0aafa50d09bc"></a>2.1.2.5.3.36 Field **keywords**

##### 2.1.2.5.3.36.1 **keywords** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image235.png?raw=true)

##### 2.1.2.5.3.36.2 **keywords** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c7b245f0-fe00-495e-9c1b-c6c5c47331ce class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.36.3 **keywords** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>keywords</td></tr><tr><td>Technical name</td><td>keywords</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="c7b245f0-fe00-495e-9c1b-c6c5c47331ce"></a>2.1.2.5.3.37 Field **\[0\]**

##### 2.1.2.5.3.37.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image236.png?raw=true)

##### 2.1.2.5.3.37.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="f4354720-c52f-4782-92f0-ab0a18a7aa06"></a>2.1.2.5.3.38 Field **organisationalUnit**

##### 2.1.2.5.3.38.1 **organisationalUnit** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image237.png?raw=true)

##### 2.1.2.5.3.38.2 **organisationalUnit** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>organisationalUnit</td></tr><tr><td>Technical name</td><td>organisationalUnit</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="5a126229-898f-4601-bb24-71e513b45bf7"></a>2.1.2.5.3.39 Field **presentedAtConference**

##### 2.1.2.5.3.39.1 **presentedAtConference** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image238.png?raw=true)

##### 2.1.2.5.3.39.2 **presentedAtConference** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#93aed1ca-b642-432f-97f8-30bbb3b8b224 class="margin-NaN">name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#431be31d-7c93-46fc-a8a2-a36af0d26fb4 class="margin-NaN">location</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#a1c8ae46-8f83-4f99-b545-2d664a1afb9f class="margin-NaN">date</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.39.3 **presentedAtConference** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>presentedAtConference</td></tr><tr><td>Technical name</td><td>presentedAtConference</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="93aed1ca-b642-432f-97f8-30bbb3b8b224"></a>2.1.2.5.3.40 Field **name**

##### 2.1.2.5.3.40.1 **name** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image239.png?raw=true)

##### 2.1.2.5.3.40.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td>name</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="431be31d-7c93-46fc-a8a2-a36af0d26fb4"></a>2.1.2.5.3.41 Field **location**

##### 2.1.2.5.3.41.1 **location** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image240.png?raw=true)

##### 2.1.2.5.3.41.2 **location** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>location</td></tr><tr><td>Technical name</td><td>location</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="a1c8ae46-8f83-4f99-b545-2d664a1afb9f"></a>2.1.2.5.3.42 Field **date**

##### 2.1.2.5.3.42.1 **date** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image241.png?raw=true)

##### 2.1.2.5.3.42.2 **date** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>date</td></tr><tr><td>Technical name</td><td>date</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Format</td><td>date</td></tr></tbody></table>

### <a id="a634c0c9-6b02-4149-a019-a54b5ff6d37d"></a>2.1.2.5.3.43 Field **typeOfThesis**

##### 2.1.2.5.3.43.1 **typeOfThesis** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image242.png?raw=true)

##### 2.1.2.5.3.43.2 **typeOfThesis** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>typeOfThesis</td></tr><tr><td>Technical name</td><td>typeOfThesis</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Enum</td><td>dissertation,habilitation</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="786c0a7d-9d2f-4e9f-acdf-d01e7083276e"></a>2.1.2.5.3.44 Field **authors**

##### 2.1.2.5.3.44.1 **authors** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image243.png?raw=true)

##### 2.1.2.5.3.44.2 **authors** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#60805094-84a5-46e3-90d4-03ce16089323 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.44.3 **authors** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>authors</td></tr><tr><td>Technical name</td><td>authors</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"><p>Empfohlen von KDSF</p></div></td></tr></tbody></table>

### <a id="60805094-84a5-46e3-90d4-03ce16089323"></a>2.1.2.5.3.45 Field **\[0\]**

##### 2.1.2.5.3.45.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image244.png?raw=true)

##### 2.1.2.5.3.45.2 **\[0\]** Hierarchy

Parent field: **authors**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#eb00ac98-ef6a-432d-b5ce-edecfc8e3db4 class="margin-NaN">firstName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#42b3ee7a-49ef-4542-9d45-8f6a1078b7d7 class="margin-NaN">lastName</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8d25a194-f221-49bb-ba7a-6a6ae27949eb class="margin-NaN">ids(1)</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#4599814e-9f1a-4ba2-8fe3-f66184babfa7 class="margin-NaN">listingRank</a></td><td class="no-break-word">number</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#12160c87-e139-49c4-8e6a-d4960b6ea22b class="margin-NaN">correspondingAuthor</a></td><td class="no-break-word">boolean</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.45.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>false</td></tr></tbody></table>

### <a id="eb00ac98-ef6a-432d-b5ce-edecfc8e3db4"></a>2.1.2.5.3.46 Field **firstName**

##### 2.1.2.5.3.46.1 **firstName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image245.png?raw=true)

##### 2.1.2.5.3.46.2 **firstName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>firstName</td></tr><tr><td>Technical name</td><td>firstName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="42b3ee7a-49ef-4542-9d45-8f6a1078b7d7"></a>2.1.2.5.3.47 Field **lastName**

##### 2.1.2.5.3.47.1 **lastName** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image246.png?raw=true)

##### 2.1.2.5.3.47.2 **lastName** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lastName</td></tr><tr><td>Technical name</td><td>lastName</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Required</td><td>true</td></tr></tbody></table>

### <a id="8d25a194-f221-49bb-ba7a-6a6ae27949eb"></a>2.1.2.5.3.48 Field **ids(1)**

##### 2.1.2.5.3.48.1 **ids(1)** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image247.png?raw=true)

##### 2.1.2.5.3.48.2 **ids(1)** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8baefd56-774b-46cf-8493-45d753d47af7 class="margin-NaN">[0]</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.48.3 **ids(1)** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ids(1)</td></tr><tr><td>Technical name</td><td>ids(1)</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="8baefd56-774b-46cf-8493-45d753d47af7"></a>2.1.2.5.3.49 Field **\[0\]**

##### 2.1.2.5.3.49.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image248.png?raw=true)

##### 2.1.2.5.3.49.2 **\[0\]** Hierarchy

Parent field: **ids(1)**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#f53f7f80-506b-4896-83b7-4b0c7b7f854b class="margin-NaN">anyOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.49.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="f53f7f80-506b-4896-83b7-4b0c7b7f854b"></a>2.1.2.5.3.50 Field **anyOf**

##### 2.1.2.5.3.50.1 **anyOf** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image249.png?raw=true)

##### 2.1.2.5.3.50.2 **anyOf** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#42ae5c4c-ccf9-4bf5-98ac-0d9c4af96e77 class="margin-NaN">[0]&nbsp;houseID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0891bfd1-fb22-4f61-ba5a-e3dbebe9933e class="margin-NaN">[1]&nbsp;ORCiD</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c8115c7d-ae48-40a5-ac41-59dd05ecf765 class="margin-NaN">[2]&nbsp;anyOtherID</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.50.3 **anyOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>anyOf</td></tr><tr><td>Activated</td><td>true</td></tr></tbody></table>

### <a id="42ae5c4c-ccf9-4bf5-98ac-0d9c4af96e77"></a>2.1.2.5.3.51 Field **\[0\] houseID**

##### 2.1.2.5.3.51.1 **\[0\] houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image250.png?raw=true)

##### 2.1.2.5.3.51.2 **\[0\] houseID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#a34ac963-748a-482e-a073-0296b6471780 class="margin-NaN">houseID</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.51.3 **\[0\] houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="a34ac963-748a-482e-a073-0296b6471780"></a>2.1.2.5.3.52 Field **houseID**

##### 2.1.2.5.3.52.1 **houseID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image251.png?raw=true)

##### 2.1.2.5.3.52.2 **houseID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>houseID</td></tr><tr><td>Technical name</td><td>houseID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="0891bfd1-fb22-4f61-ba5a-e3dbebe9933e"></a>2.1.2.5.3.53 Field **\[1\] ORCiD**

##### 2.1.2.5.3.53.1 **\[1\] ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image252.png?raw=true)

##### 2.1.2.5.3.53.2 **\[1\] ORCiD** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cad9334e-2df0-4d72-90e4-ed3a8dbc2783 class="margin-NaN">ORCiD</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.53.3 **\[1\] ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>ORCiD</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Additional properties</td><td>true</td></tr></tbody></table>

### <a id="cad9334e-2df0-4d72-90e4-ed3a8dbc2783"></a>2.1.2.5.3.54 Field **ORCiD**

##### 2.1.2.5.3.54.1 **ORCiD** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image253.png?raw=true)

##### 2.1.2.5.3.54.2 **ORCiD** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ORCiD</td></tr><tr><td>Technical name</td><td>orcid</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="c8115c7d-ae48-40a5-ac41-59dd05ecf765"></a>2.1.2.5.3.55 Field **\[2\] anyOtherID**

##### 2.1.2.5.3.55.1 **\[2\] anyOtherID** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image254.png?raw=true)

##### 2.1.2.5.3.55.2 **\[2\] anyOtherID** Hierarchy

Parent field: **anyOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6a2a1cfc-d2fa-4407-afe3-c5bc18be1485 class="margin-NaN">id</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.55.3 **\[2\] anyOtherID** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td>anyOtherID</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>object</td></tr></tbody></table>

### <a id="6a2a1cfc-d2fa-4407-afe3-c5bc18be1485"></a>2.1.2.5.3.56 Field **id**

##### 2.1.2.5.3.56.1 **id** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image255.png?raw=true)

##### 2.1.2.5.3.56.2 **id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>id</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

### <a id="4599814e-9f1a-4ba2-8fe3-f66184babfa7"></a>2.1.2.5.3.57 Field **listingRank**

##### 2.1.2.5.3.57.1 **listingRank** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image256.png?raw=true)

##### 2.1.2.5.3.57.2 **listingRank** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>listingRank</td></tr><tr><td>Technical name</td><td>listingRank</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>number</td></tr><tr><td>Min value</td><td>1</td></tr><tr><td>Default</td><td>1</td></tr></tbody></table>

### <a id="12160c87-e139-49c4-8e6a-d4960b6ea22b"></a>2.1.2.5.3.58 Field **correspondingAuthor**

##### 2.1.2.5.3.58.1 **correspondingAuthor** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image257.png?raw=true)

##### 2.1.2.5.3.58.2 **correspondingAuthor** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>correspondingAuthor</td></tr><tr><td>Technical name</td><td>correspondingAuthor</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>boolean</td></tr></tbody></table>

### <a id="3ba4dd26-a539-41d6-8066-ca832f7f88d9"></a>2.1.2.5.3.59 Field **interDisciplinaryResearchAreas**

##### 2.1.2.5.3.59.1 **interDisciplinaryResearchAreas** Tree Diagram

##### 2.1.2.5.3.59.2 **interDisciplinaryResearchAreas** Hierarchy

Parent field: **Publication**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#56267fe0-0364-420b-9ca5-57ce997216cd class="margin-NaN">[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.59.3 **interDisciplinaryResearchAreas** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Technical name</td><td>interDisciplinaryResearchAreas</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Additional items</td><td>true</td></tr></tbody></table>

### <a id="56267fe0-0364-420b-9ca5-57ce997216cd"></a>2.1.2.5.3.60 Field **\[0\]**

##### 2.1.2.5.3.60.1 **\[0\]** Tree Diagram

![Hackolade image](BUA%20API%20MODEL%20documentation/image258.png?raw=true)

##### 2.1.2.5.3.60.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Activated</td><td>true</td></tr><tr><td>Type</td><td>string</td></tr></tbody></table>

##### 2.1.2.5.4 **Publication** JSON Schema

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

##### 2.1.2.5.5 **Publication** JSON data

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

### <a id="relationships"></a>

##### 3\. Relationships

### <a id="87f1244c-f6c8-4812-b1af-02f716d398f8"></a>3.1 Relationship **project\_role**

##### 3.1.1 **project\_role** Diagram

<table><thead><tr><td>Parent Table</td><td>Parent field</td></tr></thead><tbody><tr><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>roles.[-1].unitIds.[-1].[-1].[-1].houseId</a></td></tr></tbody></table>

![Hackolade image](BUA%20API%20MODEL%20documentation/image259.png?raw=true)![Hackolade image](BUA%20API%20MODEL%20documentation/image260.png?raw=true)

<table><thead><tr><td>Child Table</td><td>Child field</td></tr></thead><tbody><tr><td><a href=#4f72014b-c421-4a4c-8aa8-a56403100ac5>Project</a></td><td><a href=#274035a2-0621-463e-bd07-711ac475fe76>ids.[-1].[-1].[-1].houseId</a></td></tr></tbody></table>

##### 3.1.2 **project\_role** Properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>project_role</td></tr><tr><td>Description</td><td></td></tr><tr><td>Parent Document</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Parent field</td><td><a href=#5a5bb19e-983c-455e-b734-121b7937e7cb>houseId</a></td></tr><tr><td>Parent Cardinality</td><td>1</td></tr><tr><td>Child Document</td><td><a href=#4f72014b-c421-4a4c-8aa8-a56403100ac5>Project</a></td></tr><tr><td>Child field</td><td><a href=#274035a2-0621-463e-bd07-711ac475fe76>houseId</a></td></tr><tr><td>Child Cardinality</td><td>1</td></tr><tr><td>Comments</td><td></td></tr></tbody></table>

### <a id="9776efff-92fd-4f84-b454-c60737bdb4df"></a>3.2 Relationship **publication\_author**

##### 3.2.1 **publication\_author** Diagram

<table><thead><tr><td>Parent Table</td><td>Parent field</td></tr></thead><tbody><tr><td><a href=#482b0df2-d80e-4871-89e5-ea8b028eabb4>Publication</a></td><td><a href=#a34ac963-748a-482e-a073-0296b6471780>authors.[-1].ids(1).[-1].[-1].[-1].[-1]</a></td></tr></tbody></table>

![Hackolade image](BUA%20API%20MODEL%20documentation/image261.png?raw=true)![Hackolade image](BUA%20API%20MODEL%20documentation/image262.png?raw=true)

<table><thead><tr><td>Child Table</td><td>Child field</td></tr></thead><tbody><tr><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td><td><a href=#38908bb7-7583-43f8-964c-0cef0df684f3>ids.[-1].[-1].[-1].houseID</a></td></tr></tbody></table>

##### 3.2.2 **publication\_author** Properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publication_author</td></tr><tr><td>Description</td><td></td></tr><tr><td>Parent Document</td><td><a href=#482b0df2-d80e-4871-89e5-ea8b028eabb4>Publication</a></td></tr><tr><td>Parent field</td><td><a href=#a34ac963-748a-482e-a073-0296b6471780></a></td></tr><tr><td>Parent Cardinality</td><td>1</td></tr><tr><td>Child Document</td><td><a href=#56b58da0-bebc-41b1-9ce3-6472881e4247>Person</a></td></tr><tr><td>Child field</td><td><a href=#38908bb7-7583-43f8-964c-0cef0df684f3>houseID</a></td></tr><tr><td>Child Cardinality</td><td>1</td></tr><tr><td>Comments</td><td></td></tr></tbody></table>

### <a id="edges"></a>