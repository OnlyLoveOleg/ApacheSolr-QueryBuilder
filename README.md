Apache Solr Query Builder Tool
==============================
This is a simple tool to help you query your solr cluster and build queries from the browser.

Setup
-----
0. Download/Clone this repo.
0. Edit the main index.html to set the default solr host and core.

Edit: index.html
```
Search for "ChangeMe" to set the correct Solr URL and default core.

Example:
--------

Before:
```
    <div class="form-group">
        <label for="SolrBaseUrl">Solr Base URL:</label>
        <input type="text" class="form-control input-sm" id="SolrBaseUrl" name="SolrBaseUrl" value="ChangeMe! <Scheme>://<HOST>/solr/">
    </div>
    <div class="form-group">
        <label for="SolrCore">Core</label>
        <input type="text" class="form-control input-sm" id="SolrCore" name="SolrCore" value="ChangeMe! - <CoreName>">
    </div>
```

After:
```
    <div class="form-group">
        <label for="SolrBaseUrl">Solr Base URL:</label>
        <input type="text" class="form-control input-sm" id="SolrBaseUrl" name="SolrBaseUrl" value="http://internal.solr.org/solr/">
    </div>
    <div class="form-group">
        <label for="SolrCore">Core</label>
        <input type="text" class="form-control input-sm" id="SolrCore" name="SolrCore" value="Core1">
    </div>

```


Author Information
------------------

Tal Lannder

Tal@Pjili.com
