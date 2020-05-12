
<div id="schema-header-title">
  <h2>TableData <span id="schema-header-title-project">sb-discovery-search <a href="https://github.com/ga4gh-schemablocks/sb-discovery-search" target="_BLANK">&nearr;</a></span> </h2>
</div>

<table id="schema-header-table">
  <tr>
    <th>{S}[B] Status <a href="https://schemablocks.org/about/sb-status-levels.html">[i]</a></th>
    <td><div id="schema-header-status">playground</div></td>
  </tr>

  <tr>
    <th>Provenance</th>
    <td>
      <ul>
<li><a href="https://github.com/ga4gh-discovery/ga4gh-discovery-search">Discovery Search</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Used by</th>
    <td>
      <ul>
<li><a href="https://github.com/ga4gh-discovery/ga4gh-discovery-search/tree/develop/spec">Discovery Search</a></li>
      </ul>
    </td>
  </tr>

<!--more-->

  <tr>
    <th>Contributors</th>
    <td>
      <ul>
<li>Miro Cupak</li>
<li><a href="https://orcid.org/0000-0002-9769-375X">Marc Fiume</a></li>
<li><a href="https://orcid.org/0000-0002-9903-4248">Michael Baudis</a></li>
<li>GA4GH Discovery developers...</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Source (0.1.0)</th>
    <td>
      <ul>
        <li><a href="current/TableData.json" target="_BLANK">raw source [JSON]</a></li>
        <li><a href="https://github.com/ga4gh-schemablocks/sb-discovery-search/blob/master/schemas/TableData.yaml" target="_BLANK">Github</a></li>
      </ul>
    </td>
  </tr>
</table>

<div id="schema-attributes-title">
  <h3>Attributes</h3>
</div>

  
__Type:__ object  
__Description:__ A paginated collection of tabular data
### Properties

<table id="schema-properties-table">
  <tr>
    <th>Property</th>
    <th>Type</th>
  </tr>
  <tr>
    <th>data</th>
    <td>array of "object"</td>
  </tr>
  <tr>
    <th>data_model</th>
    <td>http://json-schema.org/draft-07/schema#</td>
  </tr>
  <tr>
    <th>pagination</th>
    <td>./Pagination</td>
  </tr>

</table>


#### data

* type: array of "object"

Page of JSON values, each adhering to the schema given in the "data_model" property


#### data_model

* type: http://json-schema.org/draft-07/schema#




#### pagination

* type: ./Pagination




