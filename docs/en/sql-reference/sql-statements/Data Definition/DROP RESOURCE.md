---
{
    "title": "DROP RESOURCE",
    "language": "en"
}
---

<!-- 
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

# DROP RESOURCE

## Description

    This statement is used to delete an existing resource. Only the root or admin user can delete resources.
    
    Syntax:
        DROP RESOURCE 'resource_name'

    Note: ODBC/S3 resources that are in use cannot be deleted.

## Example

    1. Delete the Spark resource named spark0:
        DROP RESOURCE 'spark0';


## keyword

    DROP, RESOURCE
