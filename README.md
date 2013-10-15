PHPUnit MigrationToSelenium2 Class
==========================

### Description

Implements adapter between PHPUnit_Extensions_SeleniumTestCase
and PHPUnit_Extensions_Selenium2TestCase.

If user's TestCase class is implemented with old format 
(with commands like open, type, waitForPageToLoad), 
it should extend MigrationToSelenium2 for Selenium 2 WebDriver support.


## Implemented methods

Class provides bindings for methods:

* open
* type
* click
* select
* isTextPresent

### License
    Copyright 2013 Roman Nix
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
