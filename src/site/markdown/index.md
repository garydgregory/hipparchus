<!--
 Licensed to the Hipparchus project under one or more
 contributor license agreements.  See the NOTICE file distributed with
 this work for additional information regarding copyright ownership.
 The Hipparchus project licenses this file to You under the Apache License, Version 2.0
 (the "License"); you may not use this file except in compliance with
 the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->
## Hipparchus: a mathematics Library

Hipparchus is a library of lightweight, self-contained
 mathematics and statistics components addressing the most common
 problems not available in the Java programming language.

## Modularized

Hipparchus is a large library, so it has been split into several
modules. Users can select only the modules they need
and developers can update modules more easily and more
often than what would be possible in a large monolithic library.

---

## Guiding principles

  * Real-world application use cases determine development priority.
  * This package emphasizes small, easily integrated components
     rather than large libraries with complex dependencies and
     configurations.
  * All algorithms are fully documented and follow generally
     accepted best practices.
  * In situations where multiple standard algorithms exist, a
     Strategy pattern is used to support multiple implementations.
  * Limited dependencies. No external dependencies beyond the
     core Java platform (at least Java 1.8 starting with version
     1.0 of the library).

 ---


## Fork
 
Hipparchus started as a fork of [Apache Commons Math](https://commons.apache.org/math/).
The fork was initiated by most of the main developers and a few contributors of
Apache Commons Math.

Version 1.0 of Hipparchus is therefore very similar to
Apache Commons Math 3.6.1 with some elements of the development version
that would ultimately lead to Apache Commons Math 4.0 which was not released
at fork time.

In order to help users who would like to follow Hipparchus, a
[migration module](hipparchus-migration/index.html)
has been set up with some temporary classes that can be used to continue
using some of the initial APIs and migration scripts that can be applied to
source code in order to convert them to rely on Hipparchus.
