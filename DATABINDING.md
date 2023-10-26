# XML schema databinding 
## Naive databinding
A set of Python dataclasses are autogenerated after each new version release. The databinding are generated using the [ocx_databinding](https://pypi.org/project/ocx-databinding/) 
package which embeds the python pakcage `xsData` providing naive XML databindings.

### xsdata
We use the python package `xsData` to create conformance classes for the schema.
xsData is a complete data binding library for python allowing developers to access and
use XML and JSON documents as simple objects rather than using DOM.

[xsdata](https://xsdata.readthedocs.io/en/latest/)

The code generator supports XML schemas, DTD, WSDL definitions, XML & JSON documents.
It produces simple dataclasses with type hints and simple binding metadata.

### Features
- Generate code from:
    - XML Schemas 1.0 & 1.1
    - WSDL 1.1 definitions with SOAP 1.1 bindings
    - DTD external definitions
    - Directly from XML and JSON Documents
    - Extensive configuration to customize output
    - Pluggable code writer for custom output formats
- Default Output:
    - Pure python dataclasses with metadata
    - Type hints with support for forward references and unions
    - Enumerations and inner classes
    - Support namespace qualified elements and attributes
- Data Binding:
    - XML and JSON parser, serializer
    - PyCode serializer
    - Handlers and Writers based on lxml and native xml python
    - Support wildcard elements and attributes
    - Support xinclude statements and unknown properties
    - Customize behaviour through config

## OCX Public License
The OCX standard is governed by the 3Docx.org (https://3Docx.org) Consortium Members and published under the
Apache 2.0 Public License conditions (the License).

You may obtain a copy of the License at:

[LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, the 3Docx standard and software distributed under the License
is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
The OCX Consortium is not liable to any use whatsoever of the distributed standard or software based on the standard.

See the License for the specific language governing permissions and limitations under the License.